# IntelliMate
IntelliMate: Empowering JetBrains IDEs with intelligent collaboration, real-time assistance, and seamless code navigation. Elevate your coding experience.
## Roadmap

### Phase 1
- Develop the IntelliMate CLI tool in Rust with features for ingesting files into a vector database and automating git commits.
- Set up a development environment using Docker that includes Qdrant for vector search and integrates with locally compiled Llama models.
- Develop a CLI tool in Rust for automated git commits, ensuring compatibility with OpenAI and local Llama models.

### Phase 2
- Implement a basic UI feature for generating git commit messages.

### Phase 3
- Introduce a ChatGPT window that provides context-sensitive assistance based on the current folder and user profile, with specializations for Spark data engineering and programming languages.
### Roadmap Progress

Phase | Feature | Status |
------|---------|--------|
 1    | CLI Tool Development | :x: |
 1    | Dev Environment Setup | :x: |
 1    | Git Automation Tool | :x: |
 2    | UI for Git Messages | :x: |
 3    | ChatGPT Integration | :x: |


##System Overview
 ```mermaid
 graph LR
     A[User] -->|Input| B(VectorDB)
     B -->|User Input + Context| C[Llama]
     C -->|Reply| A
 ```
