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

My research interest includes 2D generation and 3D reconstrution/generation. I am also now working on open-world detection and domain adaptation/genelization. 

We are seeking long-term internship candidates and looking for research collaboration. Please send email to me if you want to join us.


# 🔥 News
- *2023.03*: &nbsp;🎉🎉 MetaPortrait and BUOL are accepted by CVPR2023. 
- *2022.07*: &nbsp;🎉🎉 PG-MPI is accepted by ECCV2022.
- *2022.04*: &nbsp;🎉🎉 Bring-Old-Photos-Back-to-Life has received 10,000+ github star.
- *2022.03*: &nbsp;🎉🎉 Old-Photo-Restoration is accepted by TPAMI.
- *2021.06*: &nbsp;🎉🎉 CoCosNet v2 is selected as a CVPR2021 Best Paper Candidate.
- *2021.02*: &nbsp;🎉🎉 CoCosNet v2 and ProDA are accepted by CVPR2021. CoCosNet v2 is an Oral Paper.
- *2020.10*: &nbsp;🎉🎉 Bring-Old-Photos-Back-to-Life has received 5,000+ github star.
- *2020.03*: &nbsp;🎉🎉 CoCosNet and Bring-Old-Photos-Back-to-Life are accepted by CVPR2020 as Oral Papers. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/buol.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BUOL: A Bottom-Up Framework with Occupancy-aware Lifting for Panoptic 3D Scene Reconstruction From A Single Image]()

Tao Chu, **Pan Zhang**, Qiong Liu, Jiaqi Wang

CVPR 2023 \| [**Code coming soon**]()
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/talking_head.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MetaPortrait: Identity-Preserving Talking Head Generation with Fast Personalized Adaptation](https://arxiv.org/pdf/2212.08062.pdf)

Bowen Zhang\*, Chenyang Qi\*, **Pan Zhang**, Bo Zhang, HsiangTao Wu, Dong Chen,  Qifeng Chen, Yong Wang, Fang Wen

CVPR 2023 \| [**Project**](https://meta-portrait.github.io/) \| [**Github** ![](https://img.shields.io/github/stars/Meta-Portrait/MetaPortrait?style=social)](https://github.com/Meta-Portrait/MetaPortrait)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/cmpi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Real-time neural character rendering with pose-guided multiplane images](https://arxiv.org/pdf/2204.11820.pdf)

Hao Ouyang, Bo Zhang, **Pan Zhang**, Hao Yang, Jiaolong Yang, Dong Chen,  Qifeng Chen, Fang Wen

ECCV 2022 \| [**Project**](https://ken-ouyang.github.io/cmpi/index.html) \| [**Github** ![](https://img.shields.io/github/stars/ken-ouyang/PGMPI?style=social)](https://github.com/ken-ouyang/PGMPI) \| [**Video**](https://youtu.be/otL3UAak7wQ) \| [**Dynamic MVS Data**](https://hkustconnect-my.sharepoint.com/:u:/g/personal/houyangab_connect_ust_hk/EZ_w1wUORJpHo1W1arGuL-QBoAr7WojoCOqsPMXQYk7h3Q?e=XrFuae)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/proda.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Prototypical Pseudo Label Denoising and Target Structure Learning for Domain Adaptive Semantic Segmentation](https://arxiv.org/pdf/2101.10979.pdf)

**Pan Zhang**, Bo Zhang,  Ting Zhang, Dong Chen, Yong Wang, Fang Wen

CVPR 2021 \| [**Github** ![](https://img.shields.io/github/stars/microsoft/ProDA?style=social)](https://github.com/microsoft/ProDA) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/cocosnet_v2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoCosNet v2: Full-Resolution Correspondence Learning for Image Translation](https://arxiv.org/pdf/2012.02047.pdf)

Xingran Zhou, Bo Zhang, Ting Zhang, **Pan Zhang**, Jianmin Bao, Dong Chen, Zhongfei Zhang, Fang Wen

CVPR 2021 <span style="color:red">**Oral**</span>, [<span style="color:red">**Best Paper Candidate**</span>](https://cvpr2021.thecvf.com/node/290) \| [**Github** ![](https://img.shields.io/github/stars/microsoft/CoCosNet-v2?style=social)](https://github.com/microsoft/CoCosNet-v2) \| [**Slides**](https://www.dropbox.com/s/g7dezxm2mhw6gqo/CoCosNet%20slides.pptx?dl=0)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/oldphoto.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Old Photo Restoration via Deep Latent Space Translation](https://arxiv.org/pdf/2009.07047v1.pdf)

Ziyu Wan, Bo Zhang, Dongdong Chen, **Pan Zhang**, Dong Chen, Jing Liao, Fang Wen

 TPAMI \| 🔥[**Github** ![](https://img.shields.io/github/stars/microsoft/Bringing-Old-Photos-Back-to-Life?style=social)](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life) \| [**Colab demo**](https://colab.research.google.com/drive/1NEm6AsybIiC5TwTU_4DqDkQO0nFRB-uA?usp=sharing) \| [**Replicate Demo**](https://replicate.ai/zhangmozhe/bringing-old-photos-back-to-life)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/cocosnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-domain Correspondence Learning for Exemplar-based Image Translation](https://arxiv.org/pdf/2004.05571.pdf)

**Pan Zhang**, Bo Zhang, Dong Chen, Lu Yuan, Fang Wen

CVPR 2020 <span style="color:red">**Oral**</span> \| [**Project**](https://panzhang0212.github.io/CoCosNet/) \| [**Github** ![](https://img.shields.io/github/stars/microsoft/CoCosNet?style=social)](https://github.com/microsoft/CoCosNet) \| [**Supplementary**](https://panzhang0212.github.io/CoCosNet/supplementary.pdf) \| [**Slides**](https://www.dropbox.com/s/g7dezxm2mhw6gqo/CoCosNet%20slides.pptx?dl=0) \| [**Video**](https://youtu.be/BdopAApRSgo)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/OldPhotos_teaser3.png' alt="sym" width="100%"></div></div>
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