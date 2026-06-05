# Shared Assets

Shared assets are project-neutral authoring capabilities used by Fact assets, graph build, Router, and Skills.

This directory should contain reusable vocabularies, schemas, templates, policies, and authoring Skills. It should not contain project-specific architecture notes, diagrams, version baselines, validation constraints, or validation touchpoints.

Project-shared context belongs under `context/authoring/domains/shared/` and must be represented as normal assets with `asset.registry.yaml`; routable content assets also require `asset.body.*`. Feature assets may remain item-only when the registry item is sufficient. Behavior assets are the default navigation center and should be modeled explicitly.
