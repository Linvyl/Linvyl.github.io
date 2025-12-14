---
permalink: /
author_profile: true
---

**About me**:
Hi! I’m Linh, an AI researcher interested in computer vision, multimodal learning, and vision-language models. My research focuses on multimodal understanding, including text-rich images, documents, and tasks that require joint visual and textual reasoning, with Visual Question Answering (VQA) as one of my main research topics. I received my B.Sc. in Information and Communication Technology from the University of Science and Technology of Hanoi (USTH). My research experience includes work at the Institute of Information Technology (IOIT), Vietnam Academy of Science and Technology, where I worked on deep learning-based face authentication, and at AI VIETNAM (AIVN), where I expanded my research to natural language processing, VQA, and multimodal reasoning, while also supporting research and teaching activities.

My research has resulted in publications at international venues, including ICCV Workshops (VisionDocs 2025) and the AAAI Workshop on Document Understanding and Intelligence (2025). I am currently interested in building robust and practical multimodal AI systems, especially for document understanding and real-world vision-language applications.


## Education

**B.Sc. in Information and Communication Technology (ICT)**  
University of Science and Technology of Hanoi (USTH), Vietnam  
*2020 – 2023*


## Research Experience

**AI Research Member**  
AI VIETNAM (AIVN)  
*2024 – Present*  

- Conducted research on vision–language models and visual question answering.
- Contributed to international workshop publications at AAAI and ICCV.
- Participated in reading groups, research discussions, and collaborative experiments.

**AI Research Intern**  
Department of Pattern Recognition and Knowledge Engineering (PRaKE)  
Institute of Information Technology (IOIT), VAST  
*Apr 2023 – Oct 2023*  

- Worked on a deep learning–based facial authentication system for secure login.
- Designed and implemented an end-to-end pipeline including data preprocessing, face detection and alignment, and Siamese-network-based embedding learning.
- Gained experience in debugging vision pipelines and handling noisy, imbalanced data.

## Teaching Experience

**Support Teaching Assistant (STA)**  
AI VIETNAM (AIVN) - (AIO2024 - 2025 Programme)  
*2024 – Present*  

- Assisted in lesson preparation, technical documentation, and demonstration code development.
- Contributed to instructional materials for foundational and advanced machine learning topics, including linear regression, decision trees, gradient boosting, LightGBM, variational autoencoders, and diffusion models.
- Collaborated closely with instructors to improve clarity and structure of teaching materials.

During my role as a Support Teaching Assistant at AI VIETNAM (AIVN), I contributed to the development of structured teaching materials and hands-on demonstrations for the AIO2024–2025 programme. Selected materials include:

### Step-by-step, math-oriented tutorials
- [Introduction to Gaussian Distribution and Central Limit Theorem](https://www.facebook.com/share/p/17W8DiLEKE/)
- [Vectorized Linear Regression](https://www.facebook.com/share/p/1C7s1bWpT1/)
- [Decision Tree Classification](https://www.facebook.com/share/p/19j1ALpPdU/)
- [Decision Tree Regression](https://www.facebook.com/share/p/1Hf87MEtRW/)
- [Vision Transformer (introductory tutorial)](https://aivietnam.edu.vn/blog/vision-transformer#d%E1%BA%ABn-nh%E1%BA%ADp)
- [Gradient Boosting](https://www.facebook.com/share/p/17fgCYArun/)
- [LightGBM](https://www.facebook.com/share/p/1JZxkAZape/)

### Model- and project-oriented articles
- [Knowledge Distillation with CNNs](https://aivietnam.edu.vn/blog/chuyen-giao-tri-thuc-pytorch#gi%E1%BB%9Bi-thi%E1%BB%87u)
- [Instrumental Music Generation with Variational Autoencoders](https://www.facebook.com/share/p/1FZyvZ537f/)
- [Emoji Image Generation using Diffusion Models](https://www.facebook.com/share/p/17i5UXqL99/)
- [Poem Generation with a Fine-tuned GPT-2 Model](https://www.facebook.com/share/p/17Cozz1rCz/)

### Interactive demos (Hugging Face Spaces)
- [Poem Generation Demo](https://huggingface.co/spaces/VLAI-AIVN/AIO2024M08_Poem_Generation)
- [Decision Tree Demo](https://huggingface.co/spaces/VLAI-AIVN/AIO2025M03_DEMO_DECISION_TREE/tree/main)
- [Gradient Boosting Demo](https://huggingface.co/spaces/VLAI-AIVN/AIO2025M03_DEMO_GRADIENT_BOOSTING)


## Publications
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = true %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}


## Skills

- **Machine Learning & Deep Learning:** Vision–Language Models, CNNs, Transformers, Diffusion Models
- **Computer Vision:** Face recognition, document understanding, text-rich image analysis
- **Programming:** Python, PyTorch, R (Basic), LATEX 
- **Research Skills:** Experimental design, ablation studies, paper writing, reproducibility


## Service and Academic Activities

- Research member at AI VIETNAM (AIVN)
- Contributor to open-source research codebases associated with published work
