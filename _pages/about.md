---
permalink: /
title: "Welcome to Siddharth's website"
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<button id="theme-toggle">Toggle Dark Mode</button>

I am currently a PhD candidate in the AeroAstro Department at MIT. My research interest lies in multi-agent robotics especially in partially observable settings with limited communication bandwidth. I am also interested in the interpretability of learning-based methods for autonomous navigation. I have combined tools like multi-agent reinforcement learning (MARL), graph neural networks, foundational models, and language models for my research.

My PhD thesis is on learning-based methods for multi-agent robotics focussing on:

- Scaling MARL in partially observable systems
- Long-horizon planning for multi-agent robotics
- Creating human-interpretable communication protocols for MARL methods

**I am currently on the job market for 2025**.

You can find my publications [here](https://nsidn98.github.io/publications/).

In addition to my research, I like playing musical instruments like guitar, bass, piano, drums, recorder. You can find some of my guitar videos on [instagram](https://www.instagram.com/nsidn98_/).
I am also into [sketching](https://drive.google.com/drive/folders/1NsuQx0Xl9pQ5V_EsmRd8-qbaLd2zO-Gk), [astrophotography](https://docs.google.com/presentation/d/1IXEQaMT4YNwtfmGf4ktiFaTfVXWCZLqqv2AeThw02LI/edit?usp=sharing), playing tennis, badminton, cricket and swimming.

## Contact Me

---

I am glad to discuss research ideas related to robotics, reinforcement learning and anything related to engineering and science! If you have any exciting ideas, please drop me an email.

<script>
  document.addEventListener('DOMContentLoaded', (event) => {
    const toggleButton = document.getElementById('theme-toggle');
    const currentTheme = localStorage.getItem('theme') || 'light';

    if (currentTheme === 'dark') {
      document.body.classList.add('dark-mode');
    }

    toggleButton.addEventListener('click', () => {
      document.body.classList.toggle('dark-mode');
      const theme = document.body.classList.contains('dark-mode') ? 'dark' : 'light';
      localStorage.setItem('theme', theme);
    });
  });
</script>
<!---
<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=0e1633&w=150&t=tt&d=vuy8oJHmtOg7LUHtjdY1k-B5CjSIsQ-mzVNm9KPAL0M&co=0b4975&cmo=3acc3a&cmn=ff5353&ct=cdd4d9"></script>
-->
