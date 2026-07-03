# Yingyai Protocol v1.3.1-B

Reproducible framework for EU AI Act compliance validation.

## Consensus
34/40 evaluators approved v1.3.1-B. Seed: 20260702

## Files
- `main.pdf`: Paper describing the protocol
- `yingyai_scorer.py`: Deterministic compliance scoring script 
- `eu_ai_act.yaml`: Machine-readable mapping to EU AI Act Articles 9-15
- `digital_witness_report.json`: Log of 34/40 consensus

## How to Reproduce
```bash
git clone https://github.com/yinghiy13-collab/yingyai-protocol-v1.3.1B
cd yingyai-protocol-v1.3.1B
python yingyai_scorer.py --config eu_ai_act.yaml --seed 20260702
