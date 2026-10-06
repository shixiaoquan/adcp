---
"adcontextprotocol": minor
---

Add optional, advisory `refinement_scope` (`style` | `copy` | `layout` | `mixed`) on `build_creative` refinement requests (valid only with `refine_from_build_variant_id`) and a `refinement_scope_applied` echo on `BuildCreativeVariantSuccess`, mirroring `keep_mode`/`keep_mode_applied`. A buyer-side routing hint only; it is not an authorization or compliance control.
