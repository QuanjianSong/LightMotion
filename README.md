<div align="center">
<h1>
LightMotion: A Light and Tuning-free Method for Simulating Camera Motion in Video Generation [Official Code of PyTorch]
</h1>

<div>
    <a href='https://github.com/QuanjianSong' target='_blank' style='text-decoration:none'>Quanjian Song<sup>1</sup></a>, &ensp;
    <a href='https://scholar.google.com/citations?user=UpqNGLYAAAAJ&hl=zh-CN&oi=ao' target='_blank' style='text-decoration:none'>Zhihang Lin<sup>1,2</sup></a>, &ensp;
    <a href='https://scholar.google.com/citations?hl=zh-CN&user=P9ctuRUAAAAJ&view_op=list_works&sortby=pubdate' target='_blank' style='text-decoration:none'>Zhanpeng Zeng<sup>1</sup></a>, &ensp;
    <a href='https://scholar.google.com/citations?hl=zh-CN&user=6b9pVLIAAAAJ' target='_blank' style='text-decoration:none'>Ziyue Zhang<sup>1</sup></a>, &ensp;
    <a href='https://mac.xmu.edu.cn/ljcao/' target='_blank' style='text-decoration:none'>Liujuan Cao<sup>1,†</sup></a>, &ensp;
    <a href='https://mac.xmu.edu.cn/rrji/' target='_blank' style='text-decoration:none'>Rongrong Ji<sup>1</sup></a>
</div>

<div>
    <sup>1</sup> Key Laboratory of Multimedia Trusted Perception and Efficient Computing, <br> Ministry of Education of China, Xiamen University, China.
    <br>
    <sup>2</sup> Shanghai Innovation Institute.  &ensp;
    <sup>†</sup> Corresponding Author.
    
</div>

<sub></sub>

<p align="center">
    <span>
        <a href="https://arxiv.org/abs/2503.06508" target="_blank"> 
        <img src='https://img.shields.io/badge/arXiv%202503.06508-LightMotion-red' alt='Paper PDF'></a> &emsp;  &emsp; 
    </span>
    <span> 
        <a href='https://quanjiansong.github.io/projects/UniVST' target="_blank">
        <img src='https://img.shields.io/badge/Project_Page-LightMotion-green' alt='Project Page'></a>  &emsp;  &emsp;
    </span>
    <span> 
        <a href='https://huggingface.co/papers/2503.06508' target="_blank"> 
        <img src='https://img.shields.io/badge/Hugging_Face-LightMotion-yellow' alt='Hugging Face'></a> &emsp;  &emsp;
    </span>
</p>
</div>

## 🎉 News
<pre>
• <strong>2026.01</strong>: 🔥 The <a href="https://quanjiansong.github.io/projects/LightMotion">project page</a> of LightMotion is now available.
• <strong>2025.03</strong>: 🔥 The paper of UniVST has been submitted to <a href="https://arxiv.org/abs/2503.06508">arXiv</a>
</pre>


## 🎬 Overview
<div align="justify">
Existing camera motion-controlled video generation methods face computational bottlenecks in fine-tuning and inference. This paper proposes LightMotion, a light and tuning-free method for simulating camera motion in video generation. Operating in the latent space, it eliminates additional fine-tuning, inpainting, and depth estimation, making it more streamlined than existing methods. The endeavors of this paper comprise: (i) The latent space permutation operation effectively simulates various camera motions like panning, zooming, and rotation. (ii) The latent space resampling strategy combines background-aware sampling and cross-frame alignment to accurately fill new perspectives while maintaining coherence across frames. (iii) Our in-depth analysis shows that the permutation and resampling cause an SNR shift in latent space, leading to poor-quality generation. To address this, we propose latent space correction, which reintroduces noise during denoising to mitigate SNR shift and enhance video generation quality. Exhaustive experiments show that our LightMotion outperforms existing methods, both quantitatively and qualitatively. The overall framework is illustrated as follows:
</div>
<img src="assets/overall_framework.png" style="width:100%; height:100%;"/>



## 🌈 Comparison with Existing Methods
<img src="assets/comparison.png" style="width:100%; height:100%;"/>


## 🌊 More Camera Parameters Combinations
<img src="assets/combination.png" style="width:100%; height:100%;"/>

## 🎓 Bibtex
🤗 If you find this code helpful for your research, please cite:
```
@article{song2025lightmotion,
  title={LightMotion: A Light and Tuning-free Method for Simulating Camera Motion in Video Generation},
  author={Song, Quanjian and Lin, Zhihang and Zeng, Zhanpeng and Zhang, Ziyue and Cao, Liujuan and Ji, Rongrong},
  journal={arXiv preprint arXiv:2503.06508},
  year={2025}
}
```
