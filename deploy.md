

uv sync --default-index "https://mirrors.aliyun.com/pypi/simple

uv pip install torch==2.8.0+cu128 torchaudio==2.8.0+cu128 --extra-index-url https://download.pytorch.org/whl/cu128 --default-index "https://mirrors.aliyun.com/pypi/simple"

omnivoice-demo --ip 0.0.0.0 --port 8001



$env:HF_ENDPOINT = "https://hf-mirror.com"
hf download k2-fsa/OmniVoice --local-dir . 