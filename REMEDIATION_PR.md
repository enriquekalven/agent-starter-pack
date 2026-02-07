# 🛡️ fix: A2UI Surface Alignment for Governance 🎭

## 🚀 Summary
This PR implements critical **A2UI Surface Mappings** across the core frontend templates and documentation. These identifiers are aligned with **industry best practices** for agentic observability and situational governance.

## 🛠️ Changes Recommended & Applied
*   **🎭 Surface ID Mapping (Frontend)**:
    *   Added `data-surface-id="live-react-root"` to the root mounting point in `agent_starter_pack/frontends/adk_live_react/frontend/index.html`.
*   **📚 Surface ID Mapping (Docs)**:
    *   Added `data-surface-id="docs-container"` to the documentation layout in `docs/.vitepress/theme/index.js`.

## 💎 Why this matters
These mappings allow for improved agent operations and:
1.  **Attribute Actions**: Track which UI surface triggered a specific agent reasoning trajectory.
2.  **Apply Contextual Policies**: Enforce different safety or cost guardrails depending on whether a user is interacting with the live agent or the developer documentation.

## ✅ Verification
- [x] Verified `data-surface-id` presence in the rendered DOM.
- [x] Confirmed zero regression on existing template generation workflows.

---
*Created with ⚡ by the Antigravity Agentic Remediation Engine.*
