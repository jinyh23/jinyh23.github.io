---
layout: about
title: about
permalink: /
#subtitle: Undergraduate Student · Information Security · Wuhan University

# profile:
#   align: left
#   image: prof_pic.jpg
#   image_circular: false

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: true
  scrollable: true
  limit: 3
---
<style>
  /* 顶部两栏布局：左卡片 + 右正文 */
  .hero {
    display: flex;
    gap: 12px;
    align-items: flex-start;
    margin-top: 12px;
  }

  .hero-left {
    width: 230px;
    flex: 0 0 230px;
    text-align: center;
  }

  .hero-left img {
    width: 182px;
    height: 182px;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    margin: 0 auto 14px auto;
  }

  .hero-title {
    margin-top: 10px;
    font-size: 16px;
    color: #666;
    line-height: 1.3;
  }

  .hero-title strong {
    font-weight: 600;
    font-size: 16px;
    color: #777;
  }

  .chinese-name {
    font-family: "KaiTi", "楷体", serif;
  }

  .hero-right {
    flex: 1;
    min-width: 0;
  }

  /* 手机端 */
  @media (max-width: 900px) {
    .hero { flex-direction: column; gap: 20px; }
    .hero-left { width: 100%; }
  }

  /* Education and Experience */
  .edu-entry {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 14px;
  }

  .edu-left {
    display: flex;
    align-items: flex-start;
    gap: 12px;
  }

  .edu-logo {
    width: 26px;
    height: 26px;
    object-fit: contain;
    flex-shrink: 0;
  }

  .edu-text {
    display: flex;
    flex-direction: column;
  }

  .edu-school {
    font-size: 1.05rem;
    font-weight: 600;
  }

  .edu-school a {
    text-decoration: none;
  }

  .edu-detail {
    font-size: 0.95rem;
    line-height: 1.4;
  }

  .edu-time {
    font-size: 0.9rem;
    color: #555;
    white-space: nowrap;
    margin-left: 16px;
  }

  /* Mobile */
  @media (max-width: 900px) {
    .edu-entry {
      flex-direction: column;
    }
    .edu-time {
      margin-left: 38px;
      margin-top: 4px;
    }
  }

  /* --- Large publication thumbnail (desktop, NeurIPS-style) --- */
  /* --- Fix layout after enlarging thumbnail: two-column grid --- */
  @media (min-width: 900px) {
    /* the publication entry row */
    .selected-papers .row,
    .publications .row,
    .bib-entry .row {
      display: grid;
      grid-template-columns: 300px 1fr; /* 左侧给足空间（略大于280） */
      column-gap: 22px;
      align-items: start;
    }

    /* prevent old bootstrap columns from constraining width */
    .selected-papers .row > [class*="col-"],
    .publications .row > [class*="col-"],
    .bib-entry .row > [class*="col-"] {
      max-width: none !important;
      flex: none !important;
    }

    /* keep the image inside the left column */
    .selected-papers img,
    .publications img,
    .bib-entry img {
      width: 280px;
      max-width: 280px;
      height: auto;
      display: block;
    }
  }
</style>

<div class="hero">
  <div class="hero-left">
    <img src="/assets/img/prof_pic.jpg" alt="avatar">
    <div class="hero-title">
      Master's Student<br>
      Computer Vision<br>
      <strong>Carnegie Mellon University</strong>
    </div>
  </div>

  <div class="hero-right">
    <p>
      I am currently a first-year master's student in the
      <strong>Master of Science in Computer Vision (MSCV)</strong> program at
      <a href="https://www.cmu.edu/">Carnegie Mellon University</a>.
    </p>

    <p>
      Before joining CMU, I received my B.E. degree in
      <strong>Information Security</strong> from the
      <a href="https://cse.whu.edu.cn/">School of Cyber Science and Engineering (SCSE)</a> at
      <a href="https://en.whu.edu.cn/">Wuhan University</a>,
      where I conducted research under the supervision of
      <a href="https://wangrun.github.io/">Prof. Run Wang</a>.
    </p>

    <p> 
      <strong><em><u>Research Interests:</u></em></strong>
      My research interests lie in 
      Computer Vision, Multimodal Learning, and Trustworthy AI, 
      with a particular interest in robust and safe vision systems. 
    </p>
  </div>
</div>



<!-- Write your biography here. Tell the world about yourself.  
Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too.
The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also
disable any of these elements by editing `profile` property of the YAML header
of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will
render your publications page automatically.

Link to your social media connections, too. This theme is set up to use
[Font Awesome icons](https://fontawesome.com/) and
[Academicons](https://jpswalsh.github.io/academicons/), like the ones below.
Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
<!-- I am currently an undergraduate student majoring in Information Security at the [School of Cyber Science and Engineering (SCSE)](https://cse.whu.edu.cn/) in [Wuhan University](https://en.whu.edu.cn/), where I am advised by [Prof. Run Wang](https://wangrun.github.io/).

My research interests lie in AI security, adversarial robustness, and trustworthy machine learning, with a focus on investigating the vulnerabilities and risks of multimodal systems and deep learning models in real-world applications. I aim to integrate AI security research with practical application needs and promote the deployment of AI safety technologies in domains such as robotics, healthcare, and judicial decision-making. 

I am actively seeking research internships and preparing for graduate school applications. -->