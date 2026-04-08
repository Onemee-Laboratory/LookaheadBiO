# LookaheadBio: Bilevel Optimization with Lookahead Moving Averages for LLM Data Reweighting
This repo contains the code for our paper [LookaheadBio: Bilevel Optimization with Lookahead Moving Averages for LLM Data Reweighting]({https://openreview.net/pdf?id=mFgvP3HQX1). In this work, we introduce LookaheadBiO, the first bilevel optimization algorithm that incorporates Lookahead's slow-fast weight mechanism for both model parameters and data weights, achieving comprehensive variance reduction

## Latest News
* [04-08-2026] Preview version - we release the demo data reweighting code (https://huggingface.co/ONEMEE/LookaheadBiO/upload/main)

## Quick Start

### Setup
```
pip install -r requirements.txt
```

### Reweighting
export WANDB_API_KEY=<your_wandb_api_key> and turn on --use_wandb in the script

### Recommended Hardware Configuration
8x A40/A100 GPUs and 2TB Memory

## Citation
If you find this repository useful, please consider giving ⭐ and citing our [paper]({https://openreview.net/pdf?id=mFgvP3HQX1):
```
@misc{Xie2026Bio,
  title={LookaheadBio: Bilevel Optimization with Lookahead Moving Averages for LLM Data Reweighting},
  author={Xie, Ruijie and Zhao, Chaoyue and \textbf{Oz T. Jang}},
  year={2025},
  primaryClass={cs.AI},
  url= {https://openreview.net/pdf?id=mFgvP3HQX1},
  note={}
}
```
