# COMS 4705 Final Paper — CoT and Self-Consistency on GSM8K

Jiayi (Alisa) He · jh5111

## Layout

```
Paper/
├── Paper_Proposal__4705-2.pdf              # approved proposal
├── cot_self_consistency_gsm8k.ipynb    # code
│                                             
├── results/                                # JSON outputs
└── README.md
```

## Configuration

| Variable | Default | Notes |
|---|---|---|
| `MODEL_NAME` | `Qwen/Qwen2.5-1.5B-Instruct` | ungated; swap to Llama after HF access lands |
| `N_EVAL` | 200 | size of frozen GSM8K eval slice |
| `SC_SAMPLES` | 20 | # of trajectories per question for Self-Consistency |
| `SC_TEMPERATURE` | 0.7 | sampling temperature for Self-Consistency |
| `SEED` | 42 | Controls evaluation slice |
