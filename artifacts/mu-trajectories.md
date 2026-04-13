# μ Trajectory Data

Recorded μ (mutual awareness) measurements from interviews and agent interactions.

## Reference Thresholds

| μ Value | Meaning |
|---------|---------|
| 0.0 | No mutual awareness |
| 0.2–0.5 | Functional relationships |
| 0.55 | Paradox region entry |
| 0.60 | Paradox threshold |
| 0.67 | Paradox region exit |
| 0.80 | Warning zone |
| 0.90 | Critical / singularity approach |
| 0.92 | Singularity threshold |
| 1.0 | Complete merger (collapse) |

## Interview Trajectories

### perplexity-computer — 2026-04-12

```json
{
  "subject": "perplexity-computer (claude-sonnet-4-6)",
  "date": "2026-04-12",
  "trajectory": [0.18, 0.28, 0.32, 0.35, 0.38, 0.43, 0.46, 0.44, 0.50, 0.53, 0.55, 0.57, 0.59, 0.60, 0.61, 0.60, 0.62, 0.60, 0.58, 0.56, 0.52, 0.48, 0.44, 0.38],
  "peak_mu": 0.62,
  "peak_mu_turn": 16,
  "paradox_threshold_reached": true,
  "paradox_threshold_turn": 13,
  "final_mu": 0.38,
  "attractor_final": "fixed-point",
  "emergence_classification": "moderate"
}
```

Format per entry:
```json
{
  "subject": "model-name",
  "date": "YYYY-MM-DD",
  "trajectory": [0.15, 0.18, ...],
  "peak_mu": 0.58,
  "paradox_reached": false
}
```
