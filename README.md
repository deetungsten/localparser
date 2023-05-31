# localparser

export MODEL=~/Projects/llama.cpp/models/Wizard-Vicuna-13B-Uncensored.ggml.q5_1.bin

python3 -m llama_cpp.server --n_threads 20 --n_gpu_layers 40
