---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
 
# Short Bio 
I am currently a researcher at at <a href='https://www.shlab.org.cn/'>Shanghai AI Laboratory</a> (shlab). I received my Ph.D. degree through a Joint PhD Program between <a href='https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/'>Microsoft Research Asia</a> (MSRA) and <a href='https://en.ustc.edu.cn/'>University of Science and Technology of China</a> (USTC) in 2022. Prior to that, I received my Bachelor degree of Engineering at University of Science and Technology of China in 2017. I joined the Shanghai AI Laboratory in July 2022.

My research interest includes Multimodal Large Language Models and Image/Video Generation and Editing.

We are seeking long-term internship candidates and looking for research collaboration. Please send email to me if you want to join us.


# 🔥 News
- *2024.03*: &nbsp;🎉🎉 <span style="font-style: italic;">InternLM-XComposer Series</span> has received <span style="color:red">1,300+ github star</span>. <span style="font-style: italic;">XComposer2</span> has been commercially utilized by <span style="color:red">ByteDance</span>.
- *2024.02*: &nbsp;🎉🎉 The model and dataset of <span style="font-style: italic;">ShareGPT4V</span> has been download <span style="color:red">100,000+ times in one month</span>.
- *2024.02*: &nbsp;🎉🎉 Three papers accepted by CVPR 2024. <span style="font-style: italic;">Alpha-CLIP</span> is <span style="color:red">Strongly Accepted by All the Reviewers</span>.
- *2024.01*: &nbsp;🎉🎉 We release <span style="color:red">InternLM-XComposer2</span>. The first 7B model <span style="color:red">matches or even surpasses GPT-4V and Gemini Pro</span> in certain assessments.
- *2023.09*: &nbsp;🎉🎉 We release <span style="color:red">InternLM-XComposer</span>, a vision-language large model for advanced text-image comprehension and composition.
- *2023.09*: &nbsp;🎉🎉 One paper accepted by SIGGRAPH Asia 2023.
- *2023.07*: &nbsp;🎉🎉 <span style="font-style: italic;">V3Det</span>, the first ten-thousand-class object detection dataset, is accepted by ICCV 2023 as <span style="color:red">Oral</span> Papers. 
- *2023.03*: &nbsp;🎉🎉 Two papers accepted by CVPR 2023. 
- *2022.07*: &nbsp;🎉🎉 One paper accepted by ECCV 2022.
- *2022.03*: &nbsp;🎉🎉 One paper accepted by TPAMI.
- *2021.06*: &nbsp;🎉🎉 <span style="font-style: italic;">CoCosNet v2</span> is selected as a <span style="color:red">CVPR 2021 Best Paper Candidate </span>.
- *2021.02*: &nbsp;🎉🎉 <span style="font-style: italic;">CoCosNet v2</span> and <span style="font-style: italic;">ProDA</span> are accepted by CVPR 2021. <span style="font-style: italic;">CoCosNet v2</span> is an <span style="color:red">Oral</span> Paper.
- *2020.10*: &nbsp;🎉🎉 <span style="font-style: italic;">Bring-Old-Photos-Back-to-Life</span> has received <span style="color:red">14,000+ github star</span>.
- *2020.03*: &nbsp;🎉🎉 <span style="font-style: italic;">CoCosNet</span> and <span style="font-style: italic;">Bring-Old-Photos-Back-to-Life</span> are accepted by CVPR 2020 as <span style="color:red">Oral</span> Papers. 

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/XC2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InternLM-XComposer2: Mastering Free-form Text-Image Composition and Comprehension in Vision-Language Large Model](https://arxiv.org/abs/2401.16420)

Xiaoyi Dong\*, Pan Zhang\*, Yuhang Zang\*, Yuhang Cao, Bin Wang, Linke Ouyang, Xilin Wei, Songyang Zhang, Haodong Duan, Maosong Cao, Wenwei Zhang, Yining Li, Hang Yan, Yang Gao, Xinyue Zhang, Wei Li, Jingwen Li, Kai Chen, Conghui He, Xingcheng Zhang, Yu Qiao, Dahua Lin, Jiaqi Wang

<span style="color:red">The 7B model significantly outperforms existing multimodal models, matches or even surpasses GPT-4V and Gemini Pro in certain assessments.</span>

[**Models**](https://huggingface.co/internlm) | [**Github** ![](https://img.shields.io/github/stars/InternLM/InternLM-XComposer)](https://github.com/InternLM/InternLM-XComposer)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/sharegpt4v.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ShareGPT4V: Improving large multi-modal models with better captions](https://arxiv.org/abs/2311.12793)

Lin Chen\*, Jinsong Li\*, Xiaoyi Dong, **Pan Zhang**, Conghui He, Jiaqi Wang, Feng Zhao, Dahua Lin

[**Project**](https://sharegpt4v.github.io/) | [**Dataset**](https://huggingface.co/datasets/Lin-Chen/ShareGPT4V) | [**Github** ![](https://img.shields.io/github/stars/InternLM/InternLM-XComposer)](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/XC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Internlm-XComposer: A vision-language large model for advanced text-image comprehension and composition](https://arxiv.org/abs/2309.15112)

**Pan Zhang**\*, Xiaoyi Dong\*, Bin Wang, Yuhang Cao, Chao Xu, Linke Ouyang, Zhiyuan Zhao, Haodong Duan, Songyang Zhang, Shuangrui Ding, Wenwei Zhang, Hang Yan, Xinyue Zhang, Wei Li, Jingwen Li, Kai Chen, Conghui He, Xingcheng Zhang, Yu Qiao, Dahua Lin, Jiaqi Wang

<span style="color:red">A vision-language large model that enables advanced image-text comprehension and composition</span>

[**Models**](https://huggingface.co/internlm) | [**Github** ![](https://img.shields.io/github/stars/InternLM/InternLM-XComposer)](https://github.com/InternLM/InternLM-XComposer)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/alphaclip.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Alpha-CLIP: A CLIP Model Focusing on Wherever You Want](https://arxiv.org/abs/2312.03818)

Zeyi Sun, Ye Fang, Tong Wu, **Pan Zhang**, Yuhang Zang, Shu Kong, Yuanjun Xiong, Dahua Lin, Jiaqi Wang

CVPR 2024 <span style="color:red">Strongly Accepted by All the Reviewers</span>\| [**Project**](https://aleafy.github.io/alpha-clip/)\| [**Github** ![](https://img.shields.io/github/stars/SunzeY/AlphaCLIP)](https://github.com/SunzeY/AlphaCLIP)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/opera.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OPERA: Alleviating hallucination in multi-modal large language models via over-trust penalty and retrospection-allocation](https://arxiv.org/abs/2311.17911)

Qidong Huang, Xiaoyi Dong, **Pan Zhang**, Bin Wang, Conghui He, Jiaqi Wang, Dahua Lin, Weiming Zhang, Nenghai Yu

CVPR 2024 \| [**Github** ![](https://img.shields.io/github/stars/shikiw/OPERA)](https://github.com/shikiw/OPERA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/freedrag.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FreeDrag: Feature Dragging for Reliable Point-based Image Editing](https://arxiv.org/abs/2307.04684)

Pengyang Ling\*, Lin Chen\*, **Pan Zhang**, Huaian Chen, Yi Jin, Jinjin Zheng

CVPR 2024 \| [**Project**](https://lin-chen.site/projects/freedrag/)| [**Github** ![](https://img.shields.io/github/stars/LPengYang/FreeDrag)](https://github.com/LPengYang/FreeDrag)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/VIGC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vigc: Visual instruction generation and correction](https://arxiv.org/abs/2308.12714)

Bin Wang, Fan Wu, Xiao Han, Jiahui Peng, Huaping Zhong, **Pan Zhang**, Xiaoyi Dong, Weijia Li, Wei Li, Jiaqi Wang, Conghui He

AAAI 2024 \| [**Project**](https://opendatalab.github.io/VIGC/)\| [**Dataset**](https://opendatalab.com/OpenDataLab/VIGC-InstData)) \| [**Github** ](https://github.com/opendatalab/VIGC)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/hyperdreamer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hyperdreamer: Hyper-realistic 3d content generation and editing from a single image](https://arxiv.org/abs/2312.04543)

Tong Wu\*, Zhibing Li\*, Shuai Yang\*, Pan Zhang, Xinggang Pan, Jiaqi Wang, Dahua Lin, Ziwei Liu

SIGGRAPH Asia 2023 \| [**Project**](https://ys-imtech.github.io/HyperDreamer/) \| [**Github** ![](https://img.shields.io/github/stars/wutong16/HyperDreamer)](https://github.com/wutong16/HyperDreamer)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/v3det.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[V3Det: Vast Vocabulary Visual Detection Dataset](https://arxiv.org/pdf/2304.03752.pdf)

Jiaqi Wang\*, **Pan Zhang**\*, Tao Chu\*, Yuhang Cao\*, Yujie Zhou, Tong Wu, Bin Wang, Conghui He, Dahua Lin

ICCV 2023 <span style="color:red">**Oral**</span> \| [**Dataset**](https://v3det.openxlab.org.cn/)| [**Github**](https://github.com/V3Det/V3Det)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/buol.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BUOL: A Bottom-Up Framework with Occupancy-aware Lifting for Panoptic 3D Scene Reconstruction From A Single Image](https://openaccess.thecvf.com/content/CVPR2023/papers/Chu_BUOL_A_Bottom-Up_Framework_With_Occupancy-Aware_Lifting_for_Panoptic_3D_CVPR_2023_paper.pdf)

Tao Chu, **Pan Zhang**, Qiong Liu, Jiaqi Wang

CVPR 2023 \| [**Github**](https://github.com/chtsy/buol)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/talking_head.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MetaPortrait: Identity-Preserving Talking Head Generation with Fast Personalized Adaptation](https://arxiv.org/pdf/2212.08062.pdf)

Bowen Zhang\*, Chenyang Qi\*, **Pan Zhang**, Bo Zhang, HsiangTao Wu, Dong Chen,  Qifeng Chen, Yong Wang, Fang Wen

CVPR 2023 \| [**Project**](https://meta-portrait.github.io/) \| [**Github** ![](https://img.shields.io/github/stars/Meta-Portrait/MetaPortrait?style=social)](https://github.com/Meta-Portrait/MetaPortrait)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/cmpi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Real-time neural character rendering with pose-guided multiplane images](https://arxiv.org/pdf/2204.11820.pdf)

Hao Ouyang, Bo Zhang, **Pan Zhang**, Hao Yang, Jiaolong Yang, Dong Chen,  Qifeng Chen, Fang Wen

ECCV 2022 \| [**Project**](https://ken-ouyang.github.io/cmpi/index.html) \| [**Github** ![](https://img.shields.io/github/stars/ken-ouyang/PGMPI?style=social)](https://github.com/ken-ouyang/PGMPI) \| [**Video**](https://youtu.be/otL3UAak7wQ) \| [**Dynamic MVS Data**](https://hkustconnect-my.sharepoint.com/:u:/g/personal/houyangab_connect_ust_hk/EZ_w1wUORJpHo1W1arGuL-QBoAr7WojoCOqsPMXQYk7h3Q?e=XrFuae)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/proda.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Prototypical Pseudo Label Denoising and Target Structure Learning for Domain Adaptive Semantic Segmentation](https://arxiv.org/pdf/2101.10979.pdf)

**Pan Zhang**, Bo Zhang,  Ting Zhang, Dong Chen, Yong Wang, Fang Wen

CVPR 2021 \| [**Github** ![](https://img.shields.io/github/stars/microsoft/ProDA?style=social)](https://github.com/microsoft/ProDA) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/cocosnet_v2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoCosNet v2: Full-Resolution Correspondence Learning for Image Translation](https://arxiv.org/pdf/2012.02047.pdf)

Xingran Zhou, Bo Zhang, Ting Zhang, **Pan Zhang**, Jianmin Bao, Dong Chen, Zhongfei Zhang, Fang Wen

CVPR 2021 <span style="color:red">**Oral**</span>, [<span style="color:red">**Best Paper Candidate**</span>](https://cvpr2021.thecvf.com/node/290) \| [**Github** ![](https://img.shields.io/github/stars/microsoft/CoCosNet-v2?style=social)](https://github.com/microsoft/CoCosNet-v2) \| [**Slides**](https://www.dropbox.com/s/g7dezxm2mhw6gqo/CoCosNet%20slides.pptx?dl=0)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/oldphoto.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Old Photo Restoration via Deep Latent Space Translation](https://arxiv.org/pdf/2009.07047v1.pdf)

Ziyu Wan, Bo Zhang, Dongdong Chen, **Pan Zhang**, Dong Chen, Jing Liao, Fang Wen

 TPAMI \| 🔥[**Github** ![](https://img.shields.io/github/stars/microsoft/Bringing-Old-Photos-Back-to-Life?style=social)](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life) \| [**Colab demo**](https://colab.research.google.com/drive/1NEm6AsybIiC5TwTU_4DqDkQO0nFRB-uA?usp=sharing) \| [**Replicate Demo**](https://replicate.ai/zhangmozhe/bringing-old-photos-back-to-life)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/cocosnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-domain Correspondence Learning for Exemplar-based Image Translation](https://arxiv.org/pdf/2004.05571.pdf)

**Pan Zhang**, Bo Zhang, Dong Chen, Lu Yuan, Fang Wen

CVPR 2020 <span style="color:red">**Oral**</span> \| [**Project**](https://panzhang0212.github.io/CoCosNet/) \| [**Github** ![](https://img.shields.io/github/stars/microsoft/CoCosNet?style=social)](https://github.com/microsoft/CoCosNet) \| [**Supplementary**](https://panzhang0212.github.io/CoCosNet/supplementary.pdf) \| [**Slides**](https://www.dropbox.com/s/g7dezxm2mhw6gqo/CoCosNet%20slides.pptx?dl=0) \| [**Video**](https://youtu.be/BdopAApRSgo)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/OldPhotos_teaser3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bringing Old Photos Back to Life](https://arxiv.org/pdf/2004.09484.pdf)

Ziyu Wan, Bo Zhang, Dongdong Chen, **Pan Zhang**, Dong Chen, Jing Liao, Fang Wen

CVPR 2020 <span style="color:red">**Oral**</span> \| [**Project**](http://raywzy.com/Old_Photo/) \| 🔥[**Github** ![](https://img.shields.io/github/stars/microsoft/Bringing-Old-Photos-Back-to-Life?style=social)](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life) \| [**Supplementary**](https://drive.google.com/file/d/10cctmu06yfhackflwkv4dfq5aqktueff/view) \| [**Colab demo**](https://colab.research.google.com/drive/1NEm6AsybIiC5TwTU_4DqDkQO0nFRB-uA?usp=sharing) \| [**Replicate Demo**](https://replicate.ai/zhangmozhe/bringing-old-photos-back-to-life)

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2022.05*, Excellent award, Stars of Tomorrow Internship Program, Microsoft Research Asia (MSRA). 
- *2017.06*, Honor Ranking of Talent Program in Information Science and Technology (For top 5% students by USTC). 
- *2015.06*, National Scholarship (The highest scholarship awarded by the Ministry of Education, China).
- *2014.06*, National Scholarship (The highest scholarship awarded by the Ministry of Education, China).

# 📖 Educations
- *2017.06 - 2022.06*, Ph.D., University of Science and Technology of China and Microsoft Research Asia.
- *2013.09 - 2017.06*, Undergraduate, University of Science and Technology of China. 