# Lab 2 — A neural network from scratch

Two-hidden-layer neural network (64 → W → ReLU → W → ReLU → 10 → softmax) on `load_digits`, written with NumPy only: forward pass, cross-entropy loss, backpropagation, numerical gradient check, SGD training and forward/backward timing.

Full write-up with results: [REPORT.md](REPORT.md).

## Run

```bash
pip install numpy matplotlib scikit-learn
python lab2.py
```

Outputs are written to `results/`: loss curves, `summary.txt` (gradient check, accuracy, timing) and `training_log.txt` (per-epoch log).
