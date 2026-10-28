# EV_PnC_Consent_contracts

Single source of every interface: OpenAPI, AsyncAPI, JSON Schema; generated SDKs; consumer-driven contract tests.

Part of the **EV Owners Roaming Consent** project: a central, neutral consent registry and decision point for EV owners' roaming data (which hub may receive which data, for which purpose, under which KVKK safeguard). Repo family plan: `repo-plan/consent/README.md` in the project files.

## Scope

- OpenAPI: grant API, decision API (PDP), DPO API, rights API
- AsyncAPI: RoamingGrantActive, RoamingGrantRevoked, SafeguardChanged
- JSON Schema: consent receipt (ISO/IEC TS 27560 fields), decision, audit record
- Generated clients: Java (fail-closed PDP client with cache), TypeScript
- Pact-style contract tests consumed by EV_PNC_ocpi-emsp and EV_PNC_roaming-hubs

## Requirements

RC-GATE-001, RC-GATE-003, RC-REV-001, RC-REC-001 (see `EV_PnC_Consent_docs`, specs from `roaming-consent/spec.md`)

## Tech stack

OpenAPI 3.1, AsyncAPI 3, JSON Schema, Gradle publishing

## Infrastructure (BOM)

-

## Scaling

Versioned with semver; breaking change = new major, two majors live

## Ownership

Tech lead · Visibility: public · Wave 1: now (Phase 0–1, Nov 2026 – Feb 2027)

## Status

Scaffold only. Not production ready.

## License

Apache-2.0 (proposed)
