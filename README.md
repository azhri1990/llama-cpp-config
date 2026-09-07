# Llama.cpp Config — Local AI Server

Configuration for running Llama models locally on Termux.

## Models
- Phi-3-mini-4k-instruct — Fast, lightweight (2.6GB)
- Llama-3.2-1B — Small, efficient (1.3GB)

## Usage
cd ~/llama.cpp
./build/bin/llama-server -m Phi-3-mini-4k-instruct-Q4_K_M.gguf --host 127.0.0.1 --port 11434 -t 4 --ctx-size 2048

License: MIT
