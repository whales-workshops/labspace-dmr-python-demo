# Stream completion

## Prerequisites

```bash
docker model pull ai/qwen2.5:0.5B-F16
```


## Start the Python script

```bash terminal-id=terminal-03
cd 03-stream-completion
```

```bash terminal-id=terminal-03
python main.py
```

## Try with bigger models

```bash terminal-id=terminal-03
docker model pull ai/qwen2.5:1.5B-F16
```
Or from Hugging Face:
```bash terminal-id=terminal-03
docker model pull hf.co/menlo/jan-nano-gguf:q4_k_m
```
🤚 **Change the content of `.env`**, choose between:
- `ai/qwen2.5:1.5B-F16`
- `hf.co/menlo/jan-nano-gguf:q4_k_m`

Then:
```bash terminal-id=terminal-03
python main.py
```