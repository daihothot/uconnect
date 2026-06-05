# Shared Domain

This domain holds project-shared context assets.

Use this domain only for project-wide or cross-domain Engineering facts, Architecture facts, and Flow assets.

Feature, Requirement, Validation, Validator, and project-specific Skill assets should belong to a concrete module under `context/authoring/domains/<domain>/modules/<module>/`.

GitHub Project / Issue intent should be captured as Requirement assets and linked through module-owned Feature assets. Requirement assets should not directly bind to modules.

Every consumable asset in this domain must still use the normal two-file asset shape:

- `asset.body.*`
- `asset.registry.yaml`
