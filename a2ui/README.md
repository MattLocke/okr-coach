# A2UI Adapter

This folder adds an optional A2UI handoff for the OKR Coach.

A2UI is a JSON-based, streaming agent-to-user interface protocol. The OKR Coach skill can generate A2UI v0.9 messages for apps that have an A2UI-compatible renderer.

## Codex Support

Codex can author, edit, and validate A2UI payloads as files or code. Codex skills themselves do not natively render A2UI surfaces in the Codex chat UI. To display these interfaces, use a host application or agent runtime with an A2UI renderer.

## Files

- `okr-coach-surface.sample.json`: Example A2UI v0.9 server-to-client messages for an OKR coaching surface.
- `okr-coach-a2ui-prompt.md`: Prompt add-on for agents that should emit A2UI after producing OKR coaching content.

## Stable References

- A2UI v0.9 protocol: https://github.com/a2ui-project/a2ui/blob/main/specification/v0_9/docs/a2ui_protocol.md
- A2UI Basic Catalog: https://github.com/a2ui-project/a2ui/blob/main/specification/v0_9/catalogs/basic/catalog.json
- A2UI server-to-client schema: https://github.com/a2ui-project/a2ui/blob/main/specification/v0_9/json/server_to_client.json
