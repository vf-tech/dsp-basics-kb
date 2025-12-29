# Personal Knowledge Base

Welcome to my personal engineering knowledge base.

This site contains structured notes on:

- Mathematics and signal processing
- DSP algorithms
- Embedded systems
- Standards and technical references

## Local preview (MkDocs)

```bash
python -m venv .venv
source .venv/bin/activate  # Windows (PowerShell): .venv\\Scripts\\Activate.ps1
python -m pip install -r requirements.txt
mkdocs serve
```

## Example Equation

$$
X(k) = \sum_{n=0}^{N-1} x(n) e^{-j 2 \pi k n / N}
$$
