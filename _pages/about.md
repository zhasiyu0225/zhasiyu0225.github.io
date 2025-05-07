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

0507 I’m Siyu Zha, an HCI researcher in Human-Computer Interaction, passionate about Human-AI collaboration and creative learning design. I’m currently pursuing my Ph.D. in Information Art & Design at Tsinghua University, advised by Prof. [Yingqing Xu](https://thfl.tsinghua.edu.cn/en/yjdw/yjtd/xyq/index.htm), and am a visiting Ph.D. researcher at the University of Toronto, working with Prof. [Jia Xue](https://aij.utoronto.ca/team/dr-jia-xue.html).

With a background in Educational Technology and STEM Education, my research explores how emerging technologies—especially AI—can empower learning experiences, support collaborative creativity, and foster lifelong learning through innovative, interdisciplinary design.

I’ve contributed to a range of projects in the fields of AI in education, STEAM curriculum design, and future learning environments, including the LEGO Foundation’s Playful Learning Online Project, Tsinghua’s Project X, and the Stanford ME310 Future Education Project. Currently, I’m investigating how intelligent agents can scaffold creative problem-solving and support child-centered, AI-augmented learning.

🔍 I’m actively seeking postdoctoral opportunities, research collaborations, or other academic/industry roles related to HCI, AI & Education, or Creativity Support Tools.

📬 If you're working on something exciting in these areas, I’d love to connect! Email: zhasiyu1@gmail.com

# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2025</div><img src='images/proj/mentigo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mentigo: An Intelligent Agent for Mentoring Students in the Creative Problem Solving Process](https://arxiv.org/pdf/2409.14228)

**Siyu Zha**, Yujia Liu*, Chengbo Zheng, Jiaqi Xu, Fuze Yu, Jiangtao Gong*, Yingqing Xu
- To appear in the CHI Conference on Human Factors in Computing Systems (CHI '25)
- Creative Problem-Solving (CPS) promotes creative and critical thinking while enhancing real-world problem-solving skills, making it essential for middle school education. However, providing personalized mentorship in CPS projects at scale is challenging due to resource constraints and diverse student needs. To address this, we developed Mentigo, an AI-driven mentor agent designed to guide middle school students through the CPS process. Using a dataset of real classroom interactions, we encoded CPS task stages, adaptive guidance strategies, and personalized feedback mechanisms
to inform Mentigo‘s dynamic mentoring framework powered by large language models (LLMs). A comparative experiment with 12 students and evaluations from five expert educators demonstrated improved student engagement, creativity, and task performance. Our findings highlight design implications for using LLM-based AI mentors to enhance CPS learning in educational environments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2025</div><img src='images/proj/bricksmart.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BrickSmart: Leveraging Generative AI to Support Children’s Spatial Language Learning in Family Block Play](https://arxiv.org/pdf/2504.11138)

Yujia Liu*, **Siyu Zha***, Yuewen Zhang, Yanjin Wang, Yangming Zhang, Qi Xin, Lunyiu Nie, Chao Zhang, Yingqing Xu
- To appear in the CHI Conference on Human Factors in Computing Systems (CHI'25) (🏆 BEST PAPER HONORABLE MENTION)
- Block-building activities are crucial for developing children’s spatial
reasoning and mathematical skills, yet parents often lack the expertise to guide these activities effectively. BrickSmart, a pioneering system, addresses this gap by providing spatial language guidance through a structured three-step process: Discovery & Design, Build & Learn, and Explore & Expand. This system uniquely supports parents in 1) generating personalized block-building instructions, 2) guiding parents to teach spatial language during building and interactive play, and 3) tracking children’s learning progress, altogether enhancing children’s engagement and cognitive development. In a comparative study involving 12 parent-child pairs of children aged 6-8 years) for both experimental and control groups, BrickSmart demonstrated improvements in supportiveness, efficiency, and innovation, with a significant increase in children’s use of spatial vocabulary during block play, thereby offering an effective framework for fostering spatial language skills in children.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2025</div><img src='images/proj/vrchat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generative AI in Virtual Reality Communities: A Preliminary Analysis of the VRChat Discord Community]([https://arxiv.org/pdf/2403.16159.pdf](https://www.researchgate.net/profile/Jie-Cai-22/publication/389359262_Generative_AI_in_Virtual_Reality_Communities_A_Preliminary_Analysis_of_the_VRChat_Discord_Community/links/67bfe68f207c0c20fa98863f/Generative-AI-in-Virtual-Reality-Communities-A-Preliminary-Analysis-of-the-VRChat-Discord-Community.pdf))

He Zhang, **Siyu Zha**, Jie Cai*, Donghee Yvette Wohn, John M. Carroll
- To appear in the CHI Conference on Human Factors in Computing Systems (CHI'25)
- As immersive social platforms like VRChat increasingly adopt generative AI (GenAI) technologies, it becomes critical to understand how community members perceive, negotiate, and utilize these tools. In this preliminary study, we conducted a qualitative analysis of VRChat-related Discord discussions, employing a deductive coding framework to identify key themes related to AI-assisted content creation, intellectual property disputes, and evolving community norms. Our findings offer preliminary insights into the complex interplay between the community's enthusiasm for AI-driven creativity and deep-rooted ethical and legal concerns. Users weigh issues of fair use, data ethics, intellectual property, and the role of community governance in establishing trust. By highlighting the tensions and trade-offs as users embrace new creative opportunities while seeking transparency, fair attribution, and equitable policies, this research offers valuable insights for designers, platform administrators, and policymakers aiming to foster responsible, inclusive, and ethically sound AI integration in future immersive virtual environments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJHCI 2025</div><img src='images/proj/online.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[COLP: Scaffolding Children’s Online Long-term Collaborative Learning](https://arxiv.org/pdf/2502.03226)

**Siyu Zha**, Yuanrong Tang, Jiangtao Gong*, Yingqing Xu
- Accepted by the International Journal of Human-Computer Interaction (IJHCI).
- Nowadays, online collaborative learning and working are important for everyone, including children. However, children still face a lot of difficulties communicating and working together while online, which keeps them from engaging in long-term project-based teamwork. We aim to investigate online long-term collaborative learning opportunities to address this gap. We designed the Children’s Online Long-term Program (COLP), a 16-week online project-based learning program, as an educational intervention grounded in multiple learning theories for primary school students. This program was implemented with 67 upper primary school students (Grades 3–6, ages 8–13) from over five provinces in China. We found that this program could engage more than one-third of children in teamwork after a long-term study. Furthermore, we interview children and their parents to help us understand the communication channel, benefits, and challenges of this program. Interestingly, we discovered that parents play multiple roles in their children’s collaborative learning, particularly modeling and guiding the children’s collaborative skills. Given the lack of programs designed for children’s long-term online collaboration, this study may inspire intervention design in computer-supported collaborative learning communities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In submission to IJHCS 2024</div><img src='images/proj/LLM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Designing Child-Centric AI Learning Environments: Insights from LLM-Enhanced Creative Project-Based Learning](https://arxiv.org/pdf/2403.16159.pdf)

**Siyu Zha**, Yuehan Qiao, Qingyu Hu, Zhongsheng Li, Jiangtao Gong*, Yingqing Xu
- In submission to the International Journal of Human-Computer Studies (IJHCS).
- This paper explores the potential of LLMs in PBL settings, with a special focus on fostering creativity. We began with an exploratory study involving 12 middle school students and identified five design considerations for LLM applications in PBL. Building on this, we developed an LLM-empowered, 48-hour PBL program and conducted an instructional experiment with 31 middle school students. Our results indicated that LLMs can enhance every stage of PBL. We also discovered ambivalent perspectives among students and mentors toward LLM usage. Furthermore, we explored the challenges and design implications of integrating LLMs into PBL and reflected on the program. By bridging AI advancements into educational practice, our work aims to inspire further discourse and investigation into harnessing AI’s potential in child-centric educational settings. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IASDR 2023</div><img src='images/proj/IASDR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Collaborative catalysts: a framework for creative interdisciplinary design workshop](https://dl.designresearchsociety.org/cgi/viewcontent.cgi?article=1237&context=iasdr)

**Siyu Zha**, Di Zhao*, Meng Li, Wei Gong, Qingyu Hu, Zhongsheng Li
- To appear in the International Association of Societies of Design Research (IASDR‘23).
- This study first reviews existing frameworks and the educational factors that affect creativity and productivity; then, it constructs a framework for organizing interdisciplinary workshops to leverage collective creativity through the theme of multi-modal book design for children. Qualitative empirical data were collected and analyzed in accordance with the framework. Finally, we present principles and elements for consideration when conducting an interdisciplinary approach to design experience that fosters creative collaboration by combining inductive and deductive approaches.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UIST 2021</div><img src='images/proj/Holoboard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[HoloBoard: a Large-format Immersive Teaching Board based on pseudo HoloGraphics]([https://dl.acm.org/doi/abs/10.1145/3472749.3474761])

Jiangtao Gong, Teng Han, Siling Guo, Jiannan Li, **Siyu Zha**, Liuxin Zhang, Feng Tian,  Qianying Wang, Yong Rui
- To appear in the ACM Symposium on User Interface Software and Technology (UIST’21).
- HoloBoard, an interactive large-format pseudo-holographic display system for lecture-based classes. With its unique properties of immersive visual display and transparent screen, we designed and implemented a rich set of novel interaction techniques like immersive presentation, role-play, and lecturing behind the scenes that are potentially valuable for lecturing in class.
  
</div>
</div>

# 🗂️ Projects 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/proj/toys.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Innovative Learning Toy Design**
- Managed the project to explore the role of toys in children's creative learning. Completed report on "Theoretical and Practical Design of Innovative Learning Toys for Children”.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/proj/COLP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Emergency COVID-19 Project of LEGO Foundation**
- Designed a Scratch-based online STEAM curriculum for children. Conducted education research and finished the research report "Playful Learning Online”.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/proj/Project X.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**ME310 Project in Stanford University**
- Participated in a 9-month design thinking project in collaboration with D.School. Explored how AI can assist in children's collaborative learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/proj/Teamo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Project X of Lab for Lifelong Learning**
- Responsible for the design and implementation of the developed Scratch and LEGO robotics curriculum Completed and presented two peer-reviewed papers at international conferences.
</div>
</div>

# 📖 Educations & Work Experience
- *2022.09 - Now*, Tsinghua University, Ph.D. in Information Art and Design.
- *2023.09 - 2024.12*, University of Toronto, Ph.D. Exchange in the Faculty of Information.
- *2019.09 - 2022.08*, Tsinghua University, Research Specialist in Lab for Lifelong Learning.
- *2017.09 - 2019.07*, Beijing Normal University, M.A. in Science and Technology Education.

# 📚 Publications & Patents
- **Zha, S**., Liu, Y., Zheng, C., Xu, J., Yu, F., Gong, J., & Xu, Y. (2025). Mentigo: An intelligent agent for mentoring students in the creative problem-solving process. CHI Conference on Human Factors in Computing Systems (CHI'25), April 26–May 1, 2025, Yokohama, Japan. ACM. https://doi.org/10.1145/3706598.3713952
- Liu, Y.*, **Zha, S.***, Zhang, Y., Wang, Y., Zhang, Y., Xin, Q., Nie, L., Zhang, C., & Xu, Y. (2025). BrickSmart: Leveraging generative AI to support children's spatial language learning in family block play. Proceedings of the ACM Conference on Human Factors in Computing Systems (CHI'25). ACM. https://doi.org/10.1145/3706598.3714212  (🏆 BEST PAPER HONORABLE MENTION)
- Zhang, H., **Zha, S.**, Cai, J., Wohn, D. Y., & Carroll, J. M. (2025). Generative AI in virtual reality communities: A preliminary analysis of the VRChat Discord community. Extended Abstracts of the CHI Conference on Human Factors in Computing Systems (CHI EA'25), April 26–May 1, 2025, Yokohama, Japan. ACM. https://doi.org/10.1145/3706599.3720120
- **Zha, S.**, Tang, Y., Gong, J., & Xu, Y. (2025). COLP: Scaffolding Children's Online Long-term Collaborative Learning. International Journal of Human-Computer Interaction 29.4 201-204.
- **Zha, S.**, Qiao, Y., Hu, Q., Li, Z., Gong, J., & Xu, Y. (2024). Designing Child-Centric AI Learning Environments: Insights from LLM-Enhanced Creative Project-Based Learning. arXiv preprint arXiv:2403.16159.
- **Zha, S.**, Zhao, D., Li, M., Gong, W., Hu, Q., and Li, Z.(2023) An interdisciplinary design framework for creative collaboration, in De Sainz Molestina, D., Galluzzo, L., Rizzo, F., Spallazzo, D. (eds.), IASDR 2023: Life-Changing Design, 9-13 October, Milan, Italy. https://doi.org/10.21606/iasdr.2023.550
- **Zha, S.**, Zhang, Y., Zhao, D.(2023). Future talents development through the conceptual lens of lifelong learning. Science & Technology Review(08),104-112. doi:CNKI:SUN: KJDB.0.2023-08-011 (Chinese Version) 
- Li, M., **Zha, S.**, Gong, W., and Jia, Y.(2023) A Survey of Human-Computer Interaction Technology in Intelligent Home for Children's Learning. Journal of Computer-Aided Design & Computer Graphics(02),248-261 (Chinese Version) 
- **Zha, S.** (2021). Emotional Design for Remote Learning Based on Instructional Interaction Theory. Industrial & Engineering Design. [2096-6946(2021)02-0000-10] DOI:10.19798 / j.cnki.2096-6946.2021.02.000 (Chinese Version)
- **Zha, S.**, & Chen, G. (2021). How Does The Degree Of Guidance Support Students’ Computational Thinking In Educational Robotics?. The 6th International STEM in Education Conference, the University of British Columbia, Vancouver, Canada.
- Gong, J., Ji, X., **Zha, S.**, Han, T., Ding, Q., Li, J., Zhang, L., & Wang, Q. (2021). HoloBoard: An Immersive Teaching Board System. Extended Abstracts of the 2021 CHI Conference on Human Factors in Computing Systems, 1–4.https://doi.org/10.1145/3411763.3451532
- Gong, J., **Zha, S.**, Dong, Z., Liu, M., Ding, Q., Zhang, Y., Zhang, L., & Wang, Q. (2020). Community and thematic visual analysis of educational product innovation research in the context of human-computer interaction. Proceedings of the 16th Conference on Harmonious Human-Computer Environment, Chongqing, China. One of the Candidates for Best Paper Award (Chinese Version)
- **Zha,S.**,Peng, R.,&Zhang, F.(2018).The Effects on Young Students’ Computational Thinking in CS Unplugged Activities. Presented at the London international conference on education, Cambridge, UK.
- **Zha,S.**,Chen, G., & Liu, Y. (2018). The Effects of a visual game programming environment on programming education for elementary school students. Presented at the 5th International STEM in Education Conference, Brisbane, Queensland, Australia.
