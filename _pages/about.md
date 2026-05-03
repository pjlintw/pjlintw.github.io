---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Ph.D. student in Computer Science at [Virginia Tech](https://cs.vt.edu/), advised by [Tu Vu](https://tuvllms.github.io/). My research interests focus on transferring alignment-induced behaviors (SFT, RL) across models. My overarching goal is to build modular, reusable systems in which the systems continually learn and evolve over time.

- **Efficient model development:** Developing methods for faster, cheaper, and more reusable alignment updates, enabling continual adaptation across model versions and model families.

- **Continually evolving agents**: Building LLM agents that evolve skills and effectively extract useful signals from raw trajectories for long-horizon tasks.

- **Parameter-efficient transfer learning:** Developing methods to create modular task and document knowledge for scalable transfer.

- **Data-centric methods:** Data selection and sampling strategies for stronger performance under limited compute or data.

- **Model harnessing:** Designing systems that effectively orchestrate LLM agents with tools, memory, and feedback to improve system reasoning.

Before starting my Ph.D., I completed my Master's at Saarland University where I worked on efficient transfer learning and low-resource NLP with [Dietrich Klakow](https://www.lsv.uni-saarland.de/people/dietrich-klakow/) and [Vera Demberg](https://www.uni-saarland.de/lehrstuhl/demberg/members/verademberg.html). I was selected as a Google CSRMP Fellow in 2023, and most recently interned at Amazon AGI on distributed model distillation in 2025.

<a id="-CV"></a><span style="color:darkgreen">Seeking a <strong>Research Internship</strong> (Summer 2026). Interests: LLM post-training, agents, RL, deep reasoning, and efficiency. My [CV](https://drive.google.com/file/d/1ReOHvWH1V8qXpr4mm04_dbxAcUg8eUx4/view?usp=sharing) is here.</span>


# 🔥 News

- *2026.04*: One preprint on [Master Key Hypothesis](https://arxiv.org/abs/2604.06377) (eliciting the CoT behavior in latent space).
- *2025.08*: One paper accepted as an oral presentation at EMNLP 2025.
- *2024.10*: One paper accepted to EMNLP 2024 Industry Track.
- *2024.09*: Paper *Target-Aware Language Modeling via Granular Data Sampling* accepted to EMNLP 2024.
- *2024.08*: Started my Ph.D. at Virginia Tech.
- *2024.07*: Paper *Exploring the Effectiveness and Consistency of Task Selection in Intermediate-Task Transfer Learning* accepted to ACL 2024 SRW.
- *2024.02*: Successfully defended my Master’s thesis *Exploring Task Selection for Intermediate-Task Transfer Learning*.
- *2024.02*: Paper *Modeling Orthographic Variation Improves NLP Performance for Nigerian Pidgin* accepted to LREC-COLING 2024.

<br /> 

# 📝 <a id="-Publications">Selected Publications</a>


Please see [Google Scholar](https://scholar.google.com/citations?user=KYeOpSoAAAAJ&hl=en&authuser=1) for an up-to-date publication list.

\* indicates equal contributions


<style>
    :root {
        --img-width: 200px;
    }
    img {
        width: var(--img-width);
    }
</style>

<div style="display: flex; align-items: center;">
    <img src="images/imgs/emd-img-1.jpg" alt="Efficient Model Development through Fine-tuning Transfer — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://arxiv.org/abs/2503.20110" style="color:teal;"><strong>Efficient Model Development through Fine-tuning Transfer</strong></a> <br />
        <strong><ins>Pin-Jie Lin</ins></strong>, Rishab Balasubramanian, Fengyuan Liu, Nikhil Kandpal, Tu Vu <br />
        EMNLP 2025 (Oral, top 10%) <br />
        <a href="https://arxiv.org/abs/2503.20110" style="color:gray; text-decoration:none;">[Paper]</a> <a href="https://github.com/pjlintw/finetuning-transfer" style="color:gray; text-decoration:none;">[Code]</a><br />
        <span style="color:purple">Transferring alignment-induced capabilities (SFT, RL) across LLMs without re-training LLMs from scratch.</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/sampling-img-5.jpg" alt="Target-Aware Language Modeling via Granular Data Sampling — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://arxiv.org/abs/2409.14705" style="color:teal;"><strong>Target-Aware Language Modeling via Granular Data Sampling</strong></a> <br />
        Ernie Chang, <strong><ins>Pin-Jie Lin</ins></strong>, Yang Li, Changsheng Zhao, Daeil Kim, Rastislav Rabatin, Zechun Liu, Yangyang Shi, Vikas Chandra <br />
        EMNLP 2024 <br />
        <a href="https://arxiv.org/abs/2409.14705" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">Data-efficient pretraining: ~1% of RefinedWeb to match full pretraining performance.</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/task-emb-img-1.jpg" alt="Task Selection in Intermediate-Task Transfer Learning — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2024.acl-srw.24/" style="color:teal;"><strong>Exploring the Effectiveness and Consistency of Task Selection in Intermediate-Task Transfer Learning</strong></a> <br />
        <strong><ins>Pin-Jie Lin</ins></strong>, Miaoran Zhang, Marius Mosbach, Dietrich Klakow <br />
        Student Research Workshop at ACL 2024 <br />
        <a href="https://aclanthology.org/2024.acl-srw.24/" style="color:gray; text-decoration:none;">[Paper]</a> <a href="https://github.com/uds-lsv/intermediate-task-selection/" style="color:gray; text-decoration:none;">[Code]</a><br />
        <span style="color:purple">Robust modular task selection via point-wise similarity for transfer learning.</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/ov-img-4.jpg" alt="Orthographic variation for Nigerian Pidgin NLP — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2024.lrec-main.1006/" style="color:teal;"><strong>Modeling Orthographic Variation Improves NLP Performance for Nigerian Pidgin</strong></a> <br />
        <strong><ins>Pin-Jie Lin</ins></strong>, Merel Scholman, Muhammed Saeed, Vera Demberg <br />
        LREC-COLING 2024 <br />
        <a href="https://aclanthology.org/2024.lrec-main.1006/" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">Generating synthetic data from a phonological-theoretic, parameter-free framework.</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/in-context-img-1.jpg" alt="In-Context Prompt Editing for conditional audio generation — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://ieeexplore.ieee.org/document/10446431" style="color:teal;"><strong>In-Context Prompt Editing For Conditional Audio Generation</strong></a> <br />
        Ernie Chang*, <strong><ins>Pin-Jie Lin*</ins></strong>, Yang Li, Sidd Srinivasan, Gael Le Lan, David Kant, Yangyang Shi, Forrest Iandola, Vikas Chandra <br />
        ICASSP 2024 <br />
        <a href="https://ieeexplore.ieee.org/document/10446431" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">In-context control for conditional generation (GenAI); featured in HuggingFace Daily Paper.</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/cat-img-3.jpg" alt="Cross-lingual adaptive training for low-resource Nigerian Pidgin — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://www.isca-archive.org/interspeech_2023/lin23e_interspeech.html" style="color:teal;"><strong>Low-Resource Cross-Lingual Adaptive Training for Nigerian Pidgin</strong></a> <br />
        <strong><ins>Pin-Jie Lin*</ins></strong>, Muhammed Saeed*, Ernie Chang*, Merel Scholman <br />
        Interspeech 2023 <br />
        <a href="https://www.isca-archive.org/interspeech_2023/lin23e_interspeech.html" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">Improving low-resource performance through mixed-language adaptation.</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/sample-size-img-1.jpg" alt="Sample size determination for NLU data efficiency — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2023.findings-acl.419/" style="color:teal;"><strong>Revisiting Sample Size Determination in Natural Language Understanding</strong></a> <br />
        Ernie Chang*, Muhammad Hassan Rashid*, <strong><ins>Pin-Jie Lin*</ins></strong>, Changsheng Zhao, Vera Demberg, Yangyang Shi, Vikas Chandra <br />
        ACL 2023 Findings <br />
        <a href="https://aclanthology.org/2023.findings-acl.419/" style="color:gray; text-decoration:none;">[Paper]</a> <a href="https://github.com/pjlintw/sample-size" style="color:gray; text-decoration:none;">[Code]</a>
        <br />
        <span style="color:purple">Sample-size estimation for data-efficient NLU and more reliable scaling decisions.</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/sum-img-1.jpg" alt="Two-stage movie script summarization — figure" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2022.creativesumm-1.9/" style="color:teal;"><strong>Two-Stage Movie Script Summarization: An Efficient Method For Low-Resource Long Document Summarization</strong></a> <br />
        Dongqi Pu*, Xudong Hong*, <strong><ins>Pin-Jie Lin*</ins></strong>, Ernie Chang, Vera Demberg <br />
        COLING 2022 <br />
        <a href="https://aclanthology.org/2022.creativesumm-1.9/" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">Achieving top performance in movie script summarization.</span>
    </div>
</div>
<br />


<!-- <div style="display: flex; align-items: center;">
    <img src="images/imgs/sampling-img-5.jpg" alt="Description" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://arxiv.org/abs/2409.14705" style="color:teal;"><strong>Target-Aware Language Modeling via Granular Data Sampling</strong></a> <br />
        Ernie Chang, <strong><ins>Pin-Jie Lin</ins></strong>, Yang Li, Changsheng Zhao, Daeil Kim, Rastislav Rabtin, Zechun Liu, Yangyang Shi, Vikas Chandra <br />
        EMNLP 2024 <br />
        <a href="https://arxiv.org/abs/2409.14705" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">Using ~1% of RefinedWeb data, models match full pretraining performance</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/task-emb-img-1.jpg" alt="Description" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2024.acl-srw.24/" style="color:teal;"><strong>Exploring the Effectiveness and Consistency of Task Selection in Intermediate-Task Transfer Learning</strong></a> <br />
        <strong><ins>Pin-Jie Lin</ins></strong>, Miaoran Zhang, Marius Mosbach, Dietrich Klakow <br />
        Student Research Workshop at ACL 2024 <br />
        <a href="https://aclanthology.org/2024.acl-srw.24/" style="color:gray; text-decoration:none;">[Paper]</a> <a href="https://github.com/uds-lsv/intermediate-task-selection/" style="color:gray; text-decoration:none;">[Code]</a><br />
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/ov-img-4.jpg" alt="Description" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2024.lrec-main.1006/" style="color:teal;"><strong>Modeling Orthographic Variation Improves NLP Performance for Nigerian Pidgin</strong></a> <br />
        <strong><ins>Pin-Jie Lin</ins></strong>, Merel Scholman, Muhammed Saeed, Vera Demberg <br />
        LREC-COLING 2024 <br />
        <a href="https://aclanthology.org/2024.lrec-main.1006/" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">Our synthetic data are generated from a phonological-theoretic, parameter-free framework</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/in-context-img-1.jpg" alt="Description" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://ieeexplore.ieee.org/document/10446431" style="color:teal;"><strong>In-Context Prompt Editing For Conditional Audio Generation</strong></a> <br />
        Ernie Chang*, <strong><ins>Pin-Jie Lin</ins>*</strong>, Yang Li, Sidd Srinivasan, Gael Le Lan, David Kant, Yangyang Shi, Forrest Iandola, Vikas Chandra <br />
        ICASSP 2024 <br />
        <a href="https://ieeexplore.ieee.org/document/10446431" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">HuggingFace Daily Paper and twelve picks by Jordi Pons</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/cat-img-3.jpg" alt="Description" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://www.isca-archive.org/interspeech_2023/lin23e_interspeech.html" style="color:teal;"><strong>Low-Resource Cross-Lingual Adaptive Training for Nigerian Pidgin</strong></a> <br />
        <strong><ins>Pin-Jie Lin</ins>*</strong>, Muhammed Saeed*, Ernie Chang*, Merel Scholman <br />
        Interspeech 2023 <br />
        <a href="https://www.isca-archive.org/interspeech_2023/lin23e_interspeech.html" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">We address one of the most underrepresented low-resource languages in the world. Our benchmark is publicly available</span>
    </div>
</div>
<br />


<div style="display: flex; align-items: center;">
    <img src="images/imgs/sample-size-img-1.jpg" alt="Description" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2023.findings-acl.419/" style="color:teal;"><strong>Revisiting Sample Size Determination in Natural Language Understanding</strong></a> <br />
        Ernie Chang*, Muhammad Hassan Rashid*, <strong><ins>Pin-Jie Lin</ins>*</strong>, Changsheng Zhao, Vera Demberg, Yangyang Shi and Vikas Chandra <br />
        ACL 2023 Findings <br />
        <a href="https://aclanthology.org/2023.findings-acl.419/" style="color:gray; text-decoration:none;">[Paper]</a> <a href="https://github.com/pjlintw/sample-size" style="color:gray; text-decoration:none;">[Code]</a>
        <br />
        <span style="color:purple">Our approach forecasts model performance with 0.9% error, using only 10% of the data</span>
    </div>
</div>
<br />

<div style="display: flex; align-items: center;">
    <img src="images/imgs/sum-img-1.jpg" alt="Description" style="width: {{ site.img_width }}; height: auto; margin-right: 20px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);">
    <div>
        <a href="https://aclanthology.org/2022.creativesumm-1.9/" style="color:teal;"><strong>Two-Stage Movie Script Summarization: An Efficient Method For Low-Resource Long Document Summarization</strong></a> <br />
        Dongqi Pu*, Xudong Hong*, <strong><ins>Pin-Jie Lin</ins>*</strong>, Ernie Chang, Vera Demberg <br />
        COLING 2022 <br />
        <a href="https://aclanthology.org/2022.creativesumm-1.9/" style="color:gray; text-decoration:none;">[Paper]</a> <br />
        <span style="color:purple">The top-performing movie script summarizer</span>
    </div>
</div>

**Event Extraction: Convolutional Neural Networks for Extracting Medieval
Chinese Monk’s Travels**  <br />
**<ins>Pin-Jie Lin</ins>**, Bing-Lin Tsai <br />
International Conference of Digital Archives and Digital Humanities 2019 <br />

**Name Recognition of Medieval Chinese
Monk Names** <br />
Severina Balabanova, **<ins>Pin-Jie Lin</ins>**, Ya-Lin Chen, Wan-Chun Chiu <br />
International Conference of Digital Archives and Digital Humanities 2018 <br />
 -->