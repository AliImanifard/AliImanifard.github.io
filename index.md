---
layout: single
author_profile: true
permalink: /
classes: wide smaller-font
---

<!-- Swiper CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.css" />

<!-- Swiper Slider Bar -->
<div class="swiper mySwiper" style="margin-bottom: 2rem;">
  <div class="swiper-wrapper">
    <div class="swiper-slide"><img src="/assets/images/vlcsnap-2025-06-26-00h42m47s7412.png" alt="Media 1"></div>
    <div class="swiper-slide"><img src="/assets/images/F16ALEOUA6EQXFQJ1.png" alt="Media 2"></div>
    <div class="swiper-slide"><img src="/assets/images/20240505_150338.jpg" alt="Media 3"></div>
    <div class="swiper-slide"><img src="/assets/images/photo_6028452423955235366_y.jpg" alt="Media 4"></div>
  </div>
  <div class="swiper-pagination"></div>
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
</div>

<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.js"></script>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const swiper = new Swiper('.mySwiper', {
      loop: true,
      pagination: {
        el: '.swiper-pagination',
        clickable: true,
      },
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
      autoplay: {
        delay: 4000,
      },
    });
  });
</script>

{% capture custom_content %}
## About Me
<div style="text-align: justify; font-size: 20px;">
Ranked <strong>1<sup>st</sup> out of 100+ students</strong> in my M.Sc. cohort for two consecutive years and in myfinal 18 months of B.Sc. study, achieving a <strong>GPA of 20.00/20.00 (full marks in every course),</strong> with top performance throughout. Authored 16+ publications focusing on Human Centered AI and Educational Technology, including an <strong>IEEE Best Paper Award</strong> and an <strong>IEEE Selected Paper Award;</strong> placed 1<sup>st</sup> out of 150 submissions at IEEE SGC 2024. Served three years as Research and Teaching Assistant dedicated to developing pedagogical tools and adaptive learning frameworks. Committed to advancing scholarly research in AI-driven education and student well-being at the Ph.D.level.
</div>

{: .small}

---
## Technical Skills

### Programming Languages
- Python, R, Java, C, C++, SQL, Julia, MATLAB

### LLM & AI Development Environments

- **LLM Agent Frameworks**
  - CrewAI, LangChain, Llama Index, OpenAI Agents SDK

- **Embeddable Local AI Engines**
  - llama.cpp, Ollama, PrivateGPT, GPT4All, Msty, LM Studio, Jan

- **LLM-Specific Tools and Techniques**
  - Transformers (Hugging Face)
  - Prompt Engineering
  - Few-Shot Prompting, Chain-of-Thought Prompting, Retrieval Augmented Generation (RAG), Generate Knowledge Prompting, Program-Aided Language Models (PALs), Tree of Thoughts (ToT), ReAct, Reflexion, etc.

- **NLP Libraries**
  - spaCy, NLTK

- **General AI Development Frameworks**
  - TensorFlow, Keras, PyTorch, scikit-learn

- **Visualization Tools**
  - Matplotlib, Seaborn, Plotly, ggplot2

- **Data Processing Tools**
  - Pandas, NumPy, dplyr

### Engineering Software Skills
- **IDEs**: Anaconda, RStudio, PyCharm, Visual Studio Code, IntelliJ IDEA  
- **Interactive Application Development Tools**: Gradio, Streamlit  
- **Data Science and Analytics Platforms**: RapidMiner

### Academic Writing Tools
- LaTeX, Overleaf, EndNote, Mendeley, Zotero

###  English Test Scores – TOEFL (iBT): 5.0/6.0 (=100/120) (overall score)
- Test Date: July 1<sup>st</sup> 2026
- Reading: 5.5 /6.0


{: .small}
{% endcapture %}

{{ custom_content | markdownify }}
 ---
