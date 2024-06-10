# Gitgraph (Git) Diagram

```mermaid
gitGraph
    commit
    commit
    commit
    branch develop
    checkout develop
    commit
    branch feature/login
    checkout feature/login
    commit
    commit
    checkout develop
    merge feature/login
    commit
    branch feature/feature-x
    checkout feature/feature-x
    commit
    checkout develop
    merge feature/feature-x
    commit
    checkout main
    merge develop
```