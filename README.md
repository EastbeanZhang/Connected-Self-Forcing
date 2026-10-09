# Connected Self Forcing: Beyond Local Learning in Video Autoregression

Dongbin Zhang<sup>1</sup>, Chaoda Zheng<sup>1,*</sup>, Kangjie Chen<sup>1</sup>, Xiangyu Li<sup>1</sup>, Shijia Chen<sup>1</sup>, Jinhao Deng<sup>1</sup>, Yuqi Zhang<sup>1</sup><br>
Guangfeng Jiang<sup>1</sup>, Hongbin Lin<sup>2</sup>, Choo Sin Wai<sup>3</sup>, Minqi Wang<sup>2</sup>, Puyi Wang<sup>2</sup>, Jingye Zhang<sup>3</sup><br>
Yu Zhang<sup>1</sup>, Xianming Liu<sup>1</sup>, Boyang Wang<sup>1,†</sup>

<sup>1</sup> XPeng · <sup>2</sup> The Chinese University of Hong Kong · <sup>3</sup> Tsinghua University

<sup>*</sup> Project lead. <sup>†</sup> Corresponding author.

[**Paper**](https://arxiv.org/abs/2610.12156) · [**Project Page**](https://eastbeanzhang.github.io/CSF/)

## Introduction

Connected Self Forcing reconnects selected gradient paths across autoregressive video chunks, allowing later predictions to guide how earlier context is generated. Shortcut Gradient Replay recovers this feedback without retaining the full rollout computation graph. The autoregressive inference procedure remains unchanged.

## Pipeline

![Connected Self Forcing pipeline](assets/pipeline.webp)

Feedback from later chunks passes through historical KV states and generated latents to the computations that produced earlier context.

## Code

Code coming soon.
