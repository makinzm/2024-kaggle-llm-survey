# About This article

TBD

# SetUp

it takes too long time

```shell
uv add wandb
uv add 'transformers[sentencepiece]==4.44.0'
uv add peft==0.12.0 accelerate==0.33.0 bitsandbytes trl
```

- [wandb](https://pypi.org/project/wandb/): manage machine learning experiment
- [transformers](https://pypi.org/project/transformers/): A lot of pretrained models
- [peft](https://pypi.org/project/peft/): fine tuning pretrained modesl
- [accelerate](https://pypi.org/project/accelerate/): abstract training loop between GPU, TPU and so on
  - Ref: [huggingfaceのaccelerateを使って訓練時のCUDA out of memoryを回避する #自然言語処理 - Qiita](https://qiita.com/m__k/items/518ac10399c6c8753763) accessed by 2024-11-02
- [bitsandbytes](https://pypi.org/project/bitsandbytes/): create lightweight model(quantization)
- [trl](https://pypi.org/project/trl/): train LLM with RL

