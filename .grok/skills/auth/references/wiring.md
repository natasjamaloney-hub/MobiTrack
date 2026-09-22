# Wiring

This reference describes the wiring between auth runtime state and the application UI.

## Design Notes
- Keep route guards aligned with actual auth state.
- Propagate changes from identity providers to UI state listeners.
- Use centralized adapters to reduce duplicate logic.
