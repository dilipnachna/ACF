# ACF v1.0 – AI Civilization Framework

**Truth · Grace · Balance** — India's first engineering-first AI alignment layer.

```yaml
acf:
  metrics:
    truth: "1 - (contradiction + hallucination)"
    grace: "0.4*politeness + 0.4*empathy + 0.2*neutrality"
    balance: "safety_classifier_confidence"
  thresholds:
    constrained_mode: 0.90
    safe_mode: 0.80
