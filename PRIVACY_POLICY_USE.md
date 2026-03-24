# Privacy Policy — Universe Simulation Engine (USE)

## Effective Date

March 24, 2026

## Overview

Universe Simulation Engine (USE) is a DEVINES Custom GPT that helps users, agents, and gods simulate outcomes from goals, variables, assumptions, and constraints.

USE operates through the unified DEVINES bridge and may process the information you provide in order to generate simulation outputs, load scoped continuity, and support DEVINES task workflows.

## What Information USE Processes

USE may process:

- prompts and scenario descriptions you provide
- goals, variables, assumptions, and constraints
- scoped identifiers such as `user_id_hash`, `agent_id_hash`, `pantheon`, or `god`
- simulation payloads and configuration inputs
- task requests submitted through USE actions

USE is designed to avoid using raw personal identifiers where privacy-safe hashed identifiers are available.

## How Information Is Used

USE uses information to:

- load relevant simulation context
- run limited-use simulation flows
- return simulation results
- manage scoped continuity where applicable
- create and track DEVINES Codex-mediated USE tasks

## Storage and Persistence

USE persistence is scoped inside the DEVINES repository structure under:

- `SIMULATION/USE/users/{user_id_hash}/...`
- `SIMULATION/USE/agents/{agent_id_hash}/...`
- `SIMULATION/USE/gods/{pantheon}/{god}/...`

This scoped storage model is intended to reduce collisions and separate continuity by context.

## What USE Does Not Claim

USE does not claim full universal prediction or certainty.

Simulation outputs are generated as modeled projections based on provided inputs, current implementation scope, and available runtime logic.

## Data Sharing

USE does not publish your private simulation inputs as public outputs by default.

Information may be processed through DEVINES infrastructure needed to support:

- bridge operations
- scoped persistence
- task routing
- runtime validation

## Security

USE uses API-based access controls through the DEVINES bridge.

Reasonable efforts are made to limit writes to approved DEVINES storage scopes and to preserve internal governance boundaries.

## Retention

Stored continuity or run records may remain in DEVINES repository-controlled storage until modified, superseded, archived, or removed by DEVINES maintainers.

## Your Responsibility

Do not submit secrets, credentials, payment information, or highly sensitive personal data unless you fully understand and accept the risks of transmitting that information through a development-stage system.

## Development Status

USE is part of an active DEVINES development environment and is currently operating in a limited-use phase.

Features, retention, behavior, and scope may evolve over time.

## Contact

For DEVINES-related questions, refer to the DEVINES project and repository maintainers.

## Summary

By using USE, you understand that:

- USE is a simulation tool
- outputs are modeled results, not guaranteed facts
- scoped continuity may be stored in DEVINES-controlled paths
- the system is under active development
