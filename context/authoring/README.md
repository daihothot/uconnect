# UConnect Authoring

This directory is the authoring workspace for UConnect context assets.

Only assets that pass build gates should be published to `context/consumption/context_service`.
Router and Skill consumers must not read files from this directory directly.

## Layout

- `domains/`: domain-owned context assets.
- `shared_assets/`: project-neutral vocabularies, schemas, policies, templates, and authoring Skills.
- `asset_graph/`: authoring-side module asset graph and diagnostics.
- `execution_evidence/`: internal evidence store inputs for validation backflow.
- `build/`: build diagnostics and source snapshots.
