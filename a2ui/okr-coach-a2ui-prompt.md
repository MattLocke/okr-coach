# OKR Coach A2UI Output Add-On

When the user asks for A2UI output, produce the normal OKR Coach response first, then add an `a2ui` JSON block containing A2UI v0.9 server-to-client messages.

Requirements:

- Use `version: "v0.9"`.
- Use `catalogId: "https://a2ui.org/specification/v0_9/catalogs/basic/catalog.json"`.
- Emit messages in this order: `createSurface`, `updateDataModel`, `updateComponents`.
- Include exactly one root component with `id: "root"`.
- Use Basic Catalog components such as `Column`, `Card`, `Text`, `ChoicePicker`, `Divider`, and `Button`.
- Bind UI text to the data model when practical.
- Keep the JSON valid and standalone.
- State outside the JSON that the host app needs an A2UI renderer; Codex does not render the surface by itself.

Recommended surface content:

- Title and short summary
- Audit result and anti-patterns
- Pilot/experiment status
- Three Objective options
- Key Results for each option
- Measurement guidance
- Selection action for choosing an Objective option
