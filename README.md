<p align="center">
<h1 align="center">《LLMs-Zero-to-Hero》</h1>
<h4 align="right">从大模型无名小卒到LLM大师</h4>
</p>

开个新坑，从无名小卒到大模型（LLM）大英雄~ 欢迎关注[B站后续更新](https://space.bilibili.com/12420432)！！！

目前(2025-10-19)已经**开始在写自己的书籍**了，欢迎大家跟踪[公众号--chaofa用代码打点酱油](https://bruceyuan.com/llms-zero-to-hero/chaofa-wechat-official-account.png)追踪更新～

当然也可以在 个人 [blog——yuanchaofa.com](https://yuanchaofa.com) 获取到全部内容


## 特点
- 完全从零手写，边写边讲知识点，致敬 Andrej Karpathy
- 体系化，具有完整的实践路线
- 配套视频讲解，[B站视频](https://www.bilibili.com/video/BV1qWwke5E3K)
- 配套镜像 GPU，用于模型的训练，有演示和展示 Demo
- 最小使用 3090，4090 即可训练~
- 完全从零训练的 miniLLM 可以参考个人仓库 [BitBrain——比特大脑](https://github.com/bbruceyuan/bit-brain) 获取可以体验的 demo，欢迎体验学习～

> 大家可以用我的 [AIStackDC 注册链接](https://aistackdc.com/phone-register?invite_code=D872A9)获得额外的 GPU 优惠券，2 张 1 折优惠券（4 小时）和 3 张 8 折优惠券（8 小时）。

## 目录
- 大模型基础，介绍大模型训练的流程
    - [Dense Model](https://github.com/bbruceyuan/LLMs-Zero-to-Hero/blob/master/src/video/build_gpt.ipynb) （[B站视频](https://www.bilibili.com/video/BV1qWwke5E3K)）
    - [MOE Model](https://github.com/bbruceyuan/LLMs-Zero-to-Hero/blob/master/src/video/build_moe_model.ipynb)，（[B站视频](https://www.bilibili.com/video/BV1ZbFpeHEYr/)）
    - ...
- 完全从零到一训练 LLM (Pre-Training)
- 完全从零到一微调 LLM (Supervised Fine-Tuning, SFT)
- 完全从零到一微调 LLM (Direct Preference Optimization, DPO)
- 完全从零到一微调 LLM (Reinforcement Learning from Human Feedback, RLHF)
- 用于写 Python 代码的 Code-LLM
- 大模型的部署
    - 推理优化，量化等
- ...

> 如果本套教程对你有难度，可以看看 [Hands-On Large Language Models CN(ZH) -- 动手学大模型](https://github.com/bbruceyuan/Hands-On-Large-Language-Models-CN)，先使用 `transformers` 入门，然后再来手把手自己实现大模型。

## 已更新内容目录
| 章节 | 文章解读 | 中文 Notebook<br/>复制后可直接运行| 视频讲解 <br/> (可点击)|
|---|---|------|------|
| 完全从零手写一个nanoGPT | todo | [![中文可运行 Notebook](https://img.shields.io/badge/notebook-代码-pink)](https://github.com/bbruceyuan/LLMs-Zero-to-Hero/blob/master/src/video/build_gpt.ipynb) | [![bilibili](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1qWwke5E3K)](https://www.bilibili.com/video/BV1qWwke5E3K/)<br />[![Youtube](https://img.shields.io/youtube/views/2g5-aHYWiio)](https://www.youtube.com/watch?v=2g5-aHYWiio) |
| LLM MOE 的进化之路 | [LLM MOE的进化之路，从普通简化 MOE，到 sparse_moe，再到 deepseek 使用的 share_expert_sparse_moe](https://bruceyuan.com/llms-zero-to-hero/the-way-of-moe-model-evolution.html) | [![中文可运行 Notebook](https://img.shields.io/badge/notebook-代码-pink)](https://github.com/bbruceyuan/LLMs-Zero-to-Hero/blob/master/src/video/build_moe_model.ipynb) | [![bilibili](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1ZbFpeHEYr)](https://www.bilibili.com/video/BV1ZbFpeHEYr/)<br /> [![Youtube](https://img.shields.io/youtube/views/0BodppoiloM)](https://www.youtube.com/watch?v=0BodppoiloM) | 
| DeepSeek-MLA 算法-无矩阵吸收 | [Part1: 从代码角度学习和彻底理解 DeepSeek MLA 算法](https://bruceyuan.com/post/hands-on-deepseek-mla.html)</br></br> [自顶向下方式深度解读 DeepSeek-R1，内含大量细节](https://bruceyuan.com/post/deepseek-r1-paper-reading-notes.html) |[![中文可运行 Notebook](https://img.shields.io/badge/notebook-代码-pink)](https://github.com/bbruceyuan/LLMs-Zero-to-Hero/blob/master/src/video/deepseek-mla-part1.ipynb)| [![bilibili-矩阵吸收](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV19aP1epEUc)](https://www.bilibili.com/video/BV19aP1epEUc/)<br /> [![Youtube-无矩阵吸收](https://img.shields.io/youtube/views/3SsAgBJuVvg)](https://www.youtube.com/watch?v=3SsAgBJuVvg) |
| DeepSeek-MLA 算法-矩阵吸收版 | [Part2: 从代码和公式角度理解 DeepSeek MLA 的矩阵吸收 (Projection Absorption)](https://bruceyuan.com/post/hands-on-deepseek-mla-projection-absorption.html)</br> |[![中文可运行 Notebook](https://img.shields.io/badge/notebook-代码-pink)](https://github.com/bbruceyuan/LLMs-Zero-to-Hero/blob/master/src/video/deepseek-mla-part2.ipynb)| [![bilibili-矩阵吸收](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1wjQvY6Enm)](https://www.bilibili.com/video/BV1wjQvY6Enm/)<br /> |
| 从零实现 GRPO (Agent RL），用于 Agentic RAG 训练 | [RAG 进化之路：传统 RAG 到工具与强化学习双轮驱动的 Agentic RAG](https://yuanchaofa.com/post/from-native-rag-to-agentic-rag.html) |[![中文可运行 Notebook](https://img.shields.io/badge/python-code%E5%B9%B3%E5%8F%B0-pink)](https://github.com/bbruceyuan/Hands-On-Large-Language-Models-CN/tree/master/chapter08) | [![bilibili](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1yX4aznE9s)](https://www.bilibili.com/video/BV1yX4aznE9s/)<br />[![Youtube](https://img.shields.io/youtube/views/TLDj0Cob_jk?style=social)](https://www.youtube.com/watch?v=TLDj0Cob_jk) |
| 激活函数优化| [LLM activate function激活函数的进化之路，从 ReLU，GELU 到 swishGLU](https://bruceyuan.com/llms-zero-to-hero/activate-function-from-relu-gelu-to-swishglu.html) | todo | todo | 


## 代码仓库结构
```
├── chapter01   # 不同章节的学习笔记，最终会形成一本书籍
│   ├── README.md
│   ├── ...
├── chapter02
│   ├── README.md
│   ├── train.py
│   ├── ...
├── src/
│   ├── hero/  # 最终自研实现的大模型等会放到这个地方；
│   ├── chapter01/  # 这里会存放 chapter01 的代码；
│   ├── chapter02/  # 这里会存放 chapter02 的代码；
│   ├── video/  # 录制视频的时候用到的代码；
├── README.md
```


陆续会更新，欢迎关注！！！
- 方式 1：可以加我 wx: bbruceyuan ([扫码链接(如果搜索账号添加不了)](https://bruceyuan.com/llms-zero-to-hero/wechat-account-bbruceyuan.png)) 来群里催更或者**反馈问题**～ 
- 方式 2：关注我的博客：[chaofa用代码打点酱油](https://www.bbruceyuan.com/)  **(推荐)**
- 方式 3： 关注我的公众号: [chafa用代码打点酱油](https://bruceyuan.com/llms-zero-to-hero/chaofa-wechat-official-account.png)
> 公众号是 blog 的备份，也是一种提醒方式，也可以➕我好友，但是更好的阅读体验需要是 blog。

<div style="display: flex; 
            justify-content: center; 
            gap: 20px;
            flex-wrap: wrap;
            align-items: center;">
  <img src="https://bruceyuan.com/llms-zero-to-hero/chaofa-wechat-official-account.png" 
       alt="chaofa用代码打点酱油-公众号" 
       style="max-width: 80%; 
              min-width: 300px;
              height: auto;"/>
  <!-- <img src="https://bruceyuan.com/llms-zero-to-hero/wechat-account-bbruceyuan.png" 
       alt="chaofa-微信号-bbruceyuan" 
       style="max-width: 20%;
              min-width: 150px;
              height: auto;"/> -->
</div>


> 最后欢迎大家使用 [AIStackDC](https://aistackdc.com/phone-register?invite_code=D872A9) 算力平台，主打一个便宜方便（有专门的客服支持），如果你需要的话可以使用我的邀请链接: [https://aistackdc.com/phone-register?invite_code=D872A9](https://aistackdc.com/phone-register?invite_code=D872A9)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=bbruceyuan/LLMs-Zero-to-Hero&type=Date)](https://star-history.com/#bbruceyuan/LLMs-Zero-to-Hero&Date)
