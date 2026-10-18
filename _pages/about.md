---
layout: about
title: Home
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <div class="social">
      <div class="contact-icons" style="font-size: 1.75rem; display: flex; flex-wrap: nowrap; justify-content: center; gap: 1rem">
        <a href="mailto:weiminhu@usc.edu" title="Email"><i class="fa-solid fa-envelope"></i></a>
        <a href="https://scholar.google.com/citations?user=P9yew5AAAAAJ&hl=en" title="Google Scholar" rel="external nofollow noopener" target="_blank"><i class="ai ai-google-scholar"></i></a>
        <a href="https://www.linkedin.com/in/weimin-huang-594ab5187" title="LinkedIn" rel="external nofollow noopener" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
      </div>
    </div>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # social icons are shown under the profile picture instead (see more_info above)

announcements:
  enabled: false # the News section is rendered in the page body below so its heading can be capitalized
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

Welcome to my website! I am a fourth-year Ph.D. candidate in Computer Science at the University of Southern California, advised by Prof. Bistra Dilkina. I am affiliated with the USC Center for Artificial Intelligence in Society ([CAIS](https://cais.usc.edu/)) and the Artificial Intelligence Institute for Advances in Optimization ([AI4OPT](https://www.ai4opt.org/)). During my studies, I spent time at Microsoft Research and the Pacific Northwest National Laboratory as a Ph.D. intern. Before joining USC, I received my bachelor's and master's degrees from the University of Toronto.

My research interests lie in machine learning, mathematical optimization, and data-driven decision-making. I develop scalable, efficient algorithms that exploit the structure of the problem and patterns in historical solution data, with applications to large-scale, real-world decision-making.

## Availability

- I am looking for internship positions for Summer 2027.

<h2><a href="{{ '/news/' | relative_url }}" style="color: inherit">News</a></h2>

{% include news.liquid limit=true %}
