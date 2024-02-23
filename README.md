#   <img src="assets/icon.png" width = "20" height = "40" alt="图片名称" align=center /> LLaMA Pro: Progressive LLaMA with Block Expansion
<p align="center">
📃 <a href="https://arxiv.org/abs/2401.02415" target="_blank">Paper</a> • 🤗 <a href="https://huggingface.co/TencentARC/LLaMA-Pro-8B" target="_blank">Demo & Model</a> 
</p>

## TODO List
* Add the pretrain code of [Mistral-Pro-8B-v0.1](https://huggingface.co/TencentARC/Mistral_Pro_8B_v0.1)

## News
* [2024/01/06] We open source the [LLaMA-Pro repository](https://github.com/TencentARC/LLaMA-Pro) and [Demo & Model](https://huggingface.co/TencentARC/LLaMA-Pro-8B). 
* [2024/01/07] Add how to run gradio demo locally in [demo](./demo/app.py)
* [2024/01/18] Add the training code in [open-instruct](https://github.com/hills-code/open-instruct/tree/llama-pro).
* [2024/02/23] We release the [Mistral-Pro-8B-v0.1](https://huggingface.co/TencentARC/Mistral_Pro_8B_v0.1) with superior performance on a range of benchmarks. It enhances the code and math performance of Mistral and matches the performance of the recently dominant model, [Gemma](https://huggingface.co/google/gemma-7b).
* [2024/02/23] We release the evaluation code of [Mistral-Pro-8B-v0.1](https://huggingface.co/TencentARC/Mistral_Pro_8B_v0.1) in [lm-evaluation-harness](https://github.com/hills-code/lm-evaluation-harness).

## Acknowledgement
The code of instruction tuning is based on the official implementation of [open-instruct](https://github.com/allenai/open-instruct).

Thanks [huggingface](https://huggingface.co/TencentARC/LLaMA-Pro-8B) & [wisemodel](https://wisemodel.cn/models/TencentARC/LLaMA-Pro-8B) for hosting our checkpoint.

## Citation
The code and model in this repository is mostly developed for or derived from the paper below. Please cite it if you find the repository helpful.
```
@misc{wu2024llama,
      title={LLaMA Pro: Progressive LLaMA with Block Expansion}, 
      author={Chengyue Wu and Yukang Gan and Yixiao Ge and Zeyu Lu and Jiahao Wang and Ye Feng and Ping Luo and Ying Shan},
      year={2024},
      eprint={2401.02415},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
