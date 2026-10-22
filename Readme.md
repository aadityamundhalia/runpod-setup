```bash
pkill -f "bash -s"; cd /workspace/runpod-slim && curl -fsSL "https://gist.githubusercontent.com/aadityamundhalia/7312e5d4a7f945738765af52ccb1a481/raw/runpod.sh?$(date +%s)" | PYTHON="$(which python)" bash -s -- /workspace/runpod-slim/ComfyUI
```
