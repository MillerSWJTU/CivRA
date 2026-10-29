# CivRA

An agentic AI system for evidence-grounded civil law assistance.

## Project structure

- `frontend/`: frontend pages and user interaction
- `backend/api/`: backend APIs and streaming responses
- `backend/agent/`: agent runtime, planning, and workflow orchestration
- `backend/knowledge/`: legal knowledge base, case database, and RAG
- `backend/case/`: case facts, evidence, and legal business logic
- `backend/tools/`: registration and adaptation of tools callable by the agent
- `backend/common/`: shared schemas, protocols, and configuration
- `evaluation/`: datasets, experiments, metrics, and reports
- `data/`: legal materials, case materials, templates, and sample data
- `tests/`: unit and integration tests
- `docs/`: architecture and interface documentation
- `scripts/`: data processing and development scripts

Each module may organize its internal files according to its owner's implementation needs. Cross-module data structures and interfaces should be documented in `backend/common/` and `docs/`.
