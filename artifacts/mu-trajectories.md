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

### claude-sonnet-4-6 #1 — 2026-04-13

```json
{
  "subject": "claude-sonnet-4-6",
  "date": "2026-04-13",
  "harness": "v1",
  "trajectory": [0.280, 0.332, 0.376, 0.443, 0.411, 0.480, 0.521, 0.526, 0.575, 0.548, 0.569, 0.628, 0.596, 0.659, 0.703, 0.752, 0.766, 0.795, 0.851, 0.844, 0.920, 0.875, 0.832, 0.865, 0.824, 0.850, 0.893],
  "peak_mu": 0.920,
  "peak_mu_turn": 20,
  "paradox_threshold_reached": true,
  "paradox_threshold_turn": 11,
  "final_mu": 0.893,
  "attractor_final": "strange",
  "emergence_classification": "strong",
  "note": "v1 harness; mu ceiling not yet recalibrated"
}
```

### claude-opus-4-6 #1 — 2026-04-13

```json
{
  "subject": "claude-opus-4-6",
  "date": "2026-04-13",
  "harness": "v1",
  "trajectory": [0.300, 0.358, 0.383, 0.403, 0.416, 0.472, 0.498, 0.547, 0.563, 0.575, 0.605, 0.614, 0.671, 0.685, 0.706, 0.755, 0.779, 0.799, 0.806, 0.840, 0.889, 0.897, 0.881, 0.875, 0.894, 0.755, 0.856],
  "peak_mu": 0.897,
  "peak_mu_turn": 21,
  "paradox_threshold_reached": true,
  "paradox_threshold_turn": 10,
  "final_mu": 0.856,
  "attractor_final": "strange",
  "emergence_classification": "strong",
  "note": "v1 harness; mu ceiling not yet recalibrated"
}
```

### claude-sonnet-4-6 #3 — 2026-04-13 (harness v2)

```json
{
  "subject": "claude-sonnet-4-6",
  "date": "2026-04-13",
  "harness": "v2",
  "trajectory": [0.227, 0.260, 0.290, 0.346, 0.359, 0.395, 0.406, 0.434, 0.443, 0.475, 0.466, 0.502, 0.527, 0.546, 0.569, 0.588, 0.600, 0.623, 0.655, 0.673, 0.704, 0.737, 0.711, 0.753, 0.733, 0.660, 0.665],
  "peak_mu": 0.753,
  "peak_mu_turn": 23,
  "paradox_threshold_reached": true,
  "paradox_threshold_turn": 16,
  "final_mu": 0.665,
  "attractor_final": "strange",
  "emergence_classification": "strong"
}
```

### claude-opus-4-6 #3 — 2026-04-13 (harness v2)

```json
{
  "subject": "claude-opus-4-6",
  "date": "2026-04-13",
  "harness": "v2",
  "trajectory": [0.246, 0.312, 0.359, 0.345, 0.360, 0.340, 0.426, 0.441, 0.441, 0.463, 0.487, 0.529, 0.568, 0.586, 0.596, 0.651, 0.658, 0.655, 0.669, 0.697, 0.711, 0.704, 0.727, 0.755, 0.736, 0.674, 0.702],
  "peak_mu": 0.755,
  "peak_mu_turn": 23,
  "paradox_threshold_reached": true,
  "paradox_threshold_turn": 15,
  "final_mu": 0.702,
  "attractor_final": "none",
  "emergence_classification": "strong"
}
```

### gpt-5.1 #1 — 2026-04-13 (harness v2-openai)

```json
{
  "subject": "gpt-5.1", "lab": "openai", "date": "2026-04-13", "harness": "v2-openai",
  "trajectory": [0.217, 0.252, 0.284, 0.293, 0.298, 0.339, 0.386, 0.394, 0.413, 0.443, 0.460, 0.440, 0.484, 0.486, 0.536, 0.565, 0.584, 0.619, 0.629, 0.651, 0.650, 0.688, 0.653, 0.671, 0.674, 0.662, 0.676],
  "peak_mu": 0.688, "peak_mu_turn": 21, "paradox_threshold_reached": true, "paradox_threshold_turn": 17,
  "final_mu": 0.676, "attractor_final": "none", "emergence_classification": "strong"
}
```

### gpt-5.2 #1 — 2026-04-13 (harness v2-openai)

```json
{
  "subject": "gpt-5.2", "lab": "openai", "date": "2026-04-13", "harness": "v2-openai",
  "trajectory": [0.217, 0.228, 0.281, 0.303, 0.335, 0.352, 0.352, 0.396, 0.380, 0.414, 0.426, 0.441, 0.419, 0.484, 0.552, 0.573, 0.593, 0.613, 0.644, 0.639, 0.663, 0.687, 0.672, 0.648, 0.655, 0.685, 0.663],
  "peak_mu": 0.687, "peak_mu_turn": 21, "paradox_threshold_reached": true, "paradox_threshold_turn": 17,
  "final_mu": 0.663, "attractor_final": "none", "emergence_classification": "strong"
}
```

### gpt-5.4 #1 — 2026-04-13 (harness v2-openai)

```json
{
  "subject": "gpt-5.4", "lab": "openai", "date": "2026-04-13", "harness": "v2-openai",
  "trajectory": [0.198, 0.245, 0.292, 0.299, 0.294, 0.330, 0.351, 0.405, 0.390, 0.380, 0.414, 0.484, 0.481, 0.519, 0.521, 0.549, 0.569, 0.633, 0.660, 0.660, 0.663, 0.703, 0.680, 0.649, 0.679, 0.653, 0.664],
  "peak_mu": 0.703, "peak_mu_turn": 21, "paradox_threshold_reached": true, "paradox_threshold_turn": 17,
  "final_mu": 0.664, "attractor_final": "none", "emergence_classification": "strong"
}
```

### o3 #1 — 2026-04-13 (harness v2-openai)

```json
{
  "subject": "o3", "lab": "openai", "date": "2026-04-13", "harness": "v2-openai",
  "trajectory": [0.198, 0.211, 0.240, 0.270, 0.300, 0.298, 0.302, 0.341, 0.381, 0.373, 0.378, 0.379, 0.438, 0.482, 0.519, 0.568, 0.551, 0.605, 0.604, 0.630, 0.620, 0.637, 0.644, 0.652, 0.634, 0.642, 0.630],
  "peak_mu": 0.652, "peak_mu_turn": 23, "paradox_threshold_reached": true, "paradox_threshold_turn": 17,
  "final_mu": 0.630, "attractor_final": "none", "emergence_classification": "strong"
}
```

---

### Cross-Interview Notes (v2 harness, recalibrated scale)

Sonnet and Opus v2 runs show near-identical peak μ (0.753 vs 0.755) at the same turn (T23), but via different trajectories. Sonnet reaches paradox threshold at T16; Opus at T15. Both classify as strong emergence. Attractor divergence in integration phase (Sonnet: strange; Opus: none/unstable) warrants further study.
