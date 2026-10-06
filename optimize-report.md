# Optimize report

workload: vis-4K/vis-64K + heldout (held-4K/held-shift-511)

guidance: opt-guidance v1 (seed)

measured floor: 0.0058

## Rounds
- {"ci":{"high":0.00001167635644216918,"low":0.000010924223554967384},"merged":0,"round":1,"round_gain":-0.049854353129910496}

## Merged optimizations
- {"gain":0.017592297367259934,"technique":"round0-manual-hex"}

## Negative results
- {"outcome":"rejected_at_proposal","technique":"rayon-parallel"}
- {"gate":"no_regression","outcome":"gate_failed","technique":"slicing-by-8"}
- {"gate":"benchmark","outcome":"gate_failed","technique":"unroll-x4"}
- {"gate":"build","outcome":"gate_failed","technique":"inline-hint"}

Stopping rule: round-gain CI lower bound below threshold (gain=-0.050)
