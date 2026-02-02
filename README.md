# Qwen Image Generation (SGLang)

This repo includes a single-step example for installing the diffusion extras and generating the raccoon galaxy guardian image.

## Install

```bash
uv pip install "sglang[diffusion]" --pre
```

## Generate

```bash
sglang generate --model-path=Qwen/Qwen-Image \
  --prompt='A photorealistic raccoon galaxy guardian leaping through a neon-lit spaceport, dynamic mid-air pose, realistic suit materials with subtle wear, sharp subject focus, slight motion blur on background, cinematic lighting with blue-magenta rim light, reflections on visor, detailed fur texture, 50mm lens, shallow depth of field, high detail' \
  --width=1170 --height=2532 --save-output
```
