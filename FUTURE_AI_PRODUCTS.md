# Future AI Products

This file records the next long-term product repositories to create after **Zamith Assistant**.

## 1. Zamith Assistant
**Repository:** current `mini-gpt` repository, planned rename to `zamith-assistant`.

Purpose:
A local-first personal AI assistant and engineering platform with voice, memory, RAG, tools, agents, vision, privacy controls, and cross-device access.

Status: **Active development**

---

## 2. Zamith Work
**Planned repository:** `zamith-work`

Purpose:
A private AI operating layer for companies and teams.

Core product direction:
- Connect company documents, email, calendar, CRM, databases, and internal tools
- Role-based access and user isolation
- RAG over company knowledge
- Shared and scoped memory
- Agentic workflows
- Human approval for sensitive actions
- Audit logs
- On-premise / local-first option
- Evaluation and reliability metrics

Long-term reason:
Companies will continue to need secure AI systems that can work across internal data and business tools, regardless of which underlying model is best.

Status: **Future product**

---

## 3. Zamith Guardian
**Planned repository:** `zamith-guardian`

Purpose:
A control, trust, and governance layer for AI agents.

Core product direction:
- Agent permissions and policy enforcement
- Human approval gates
- Tool and data-access controls
- Audit trails
- Evaluation and regression monitoring
- Cost and latency monitoring
- Failure detection
- Agent identity and scope
- Risk controls for multi-agent systems

Long-term reason:
As companies deploy more agents, they will need a system to control what agents may access, what they may do, and how their actions can be reviewed.

Status: **Future product**

---

## Build order

1. Finish and stabilize **Zamith Assistant**
2. Build **Zamith Work**
3. Build **Zamith Guardian**

## Product rule

Each product must have its own repository.
Do not mix the source code of these products into one repository.
Shared libraries can be extracted later only when there is a real engineering need.
