<div align="center">
<h1>
LightMotion: A Light and Tuning-free Method for Simulating Camera Motion in Video Generation [Official Code of PyTorch]
</h1>

<div>
    <a href='https://github.com/QuanjianSong' target='_blank' style='text-decoration:none'>Quanjian Song<sup>1</sup></a>, &ensp;
    <a href='https://scholar.google.com/citations?user=UpqNGLYAAAAJ&hl=zh-CN&oi=ao' target='_blank' style='text-decoration:none'>Zhihang Lin<sup>1</sup></a>, &ensp;
    <a href='https://scholar.google.com/citations?hl=zh-CN&user=P9ctuRUAAAAJ&view_op=list_works&sortby=pubdate' target='_blank' style='text-decoration:none'>Zhanpeng Zeng<sup>1</sup></a>, &ensp;
    <a href='https://scholar.google.com/citations?hl=zh-CN&user=6b9pVLIAAAAJ' target='_blank' style='text-decoration:none'>Ziyue Zhang<sup>1</sup></a>, &ensp;
    <a href='https://mac.xmu.edu.cn/ljcao/' target='_blank' style='text-decoration:none'>Liujuan Cao<sup>1</sup></a>, &ensp;
    <a href='https://mac.xmu.edu.cn/rrji/' target='_blank' style='text-decoration:none'>Rongrong Ji<sup>1</sup></a>
</div>

<div>
    <sup>1</sup> Key Laboratory of Multimedia Trusted Perception and Efficient Computing, <br> Ministry of Education of China, Xiamen University, China.<br>
    <sup>2</sup> Kunlun Skywork AI.
</div>

<sub></sub>

<p align="center">
    <span>
        <a href="https://arxiv.org/abs/2410.20084" target="_blank"> 
        <img src='https://img.shields.io/badge/arXiv-2410.20084%20UniVST-red' alt='Paper PDF'></a> &emsp;  &emsp; 
    </span>
    <span> 
        <a href='https://github.com/QuanjianSong/LightMotion' target="_blank">
        <img src='https://img.shields.io/badge/Project_Page-UniVST-green' alt='Project Page'></a>  &emsp;  &emsp;
    </span>
    <span> 
        <a href='https://huggingface.co/papers/2410.20084' target="_blank"> 
        <img src='https://img.shields.io/badge/Hugging_Face-UniVST-yellow' alt='Project Page'></a> &emsp;  &emsp;
    </span>
</p>
</div>



Our code will be released as soon as possible.
## Abstract
![](assets/overall_pipeline.png)
![](assets/permutation_resampling.png)

Existing camera motion-controlled video generation methods face computational bottlenecks in fine-tuning and inference. This paper proposes LightMotion, a light and tuning-free method for simulating camera motion in video generation. Operating in the latent space, it eliminates additional fine-tuning, inpainting, and depth estimation, making it more streamlined than existing methods. The endeavors of this paper comprise: (i) The latent space permutation operation effectively simulates various camera motions like panning, zooming, and rotation. (ii) The latent space resampling strategy combines background-aware sampling and cross-frame alignment to accurately fill new perspectives while maintaining coherence across frames. (iii) Our in-depth analysis shows that the permutation and resampling cause an SNR shift in latent space, leading to poor-quality generation. To address this, we propose latent space correction, which reintroduces noise during denoising to mitigate SNR shift and enhance video generation quality. Exhaustive experiments show that our LightMotion outperforms existing methods, both quantitatively and qualitatively.

## Comparison with Existing Methods
![](assets/comparison.png)

## More Camera Parameters Combinations
![](assets/combination.png)
