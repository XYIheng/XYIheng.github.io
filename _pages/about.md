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

Yiheng Xiong (熊一衡) is a postdoctoral research scientist at [Singapore Management University (SMU)](https://www.smu.edu.sg/), working with Prof. [Xiaofei Xie](https://xiaofeixie.bitbucket.io/). He received his Ph.D. degree from [East China Normal University (ECNU)](https://www.ecnu.edu.cn/), under the supervision of Prof. [Ting Su](https://tingsu.github.io/) and Prof. [Geguang Pu](https://scholar.google.com/citations?user=niQAGcQAAAAJ&hl=zh-CN). He was fortunate enough to visit the [Advanced Software Technologies (AST) Lab](https://ast.ethz.ch/) at [ETH Zurich](https://ethz.ch/en.html), advised by Prof. [Zhendong Su](https://people.inf.ethz.ch/suz/). He obtained the B.Eng. degree at [SUSTech](https://www.sustech.edu.cn/) in 2020.

His research interests lie in software engineering, with a focus on mobile app testing and malware detection. His work has received three ACM SIGSOFT Distinguished Paper Awards (ISSTA 2023, ASE 2024, and ISSTA 2026). He is maintaining a paper list on [Android testing, analysis, and security](https://github.com/XYIheng/AndroidTesting).


# 📖 Educations
- *2023.10 - 2024.10*, Visiting Ph.D. Student, **ETH Zurich**, supervised by Prof. [Zhendong Su](https://people.inf.ethz.ch/suz/).
- *2020.09 - 2025.06*, Ph.D. in Software Engineering, **East China Normal University**, supervised by Prof. [Ting Su](https://tingsu.github.io/) and Prof. [Geguang Pu](https://scholar.google.com/citations?user=niQAGcQAAAAJ&hl=zh-CN).
- *2016.09 - 2020.06*, B.Eng. in Computer Science and Technology, **Southern University of Science and Technology (SUSTech)**, supervised by Prof. [Yepang Liu](https://yepangliu.github.io/).

# 🔥 News
- *2026.09*: &nbsp;🏆 ISSTA 2026 paper received ACM SIGSOFT Distinguished Paper Award (**19 of 888 submissions, top 2.1%**).
- *2026.07*: &nbsp;🎉 One paper accepted to ASE 2026.
- *2026.05*: &nbsp;I was invited to serve as a Program Committee member for FSE 2027.
- *2026.04*: &nbsp;🎉 Two papers accepted to ISSTA 2026.
- *2026.02*: &nbsp;🎉 One paper accepted to FSE 2026 (demo track).

<details class="news-more" markdown="1">
<summary>Show earlier news</summary>

- *2025.06*: &nbsp;🎓 Received Ph.D. from East China Normal University.
- *2025.06*: &nbsp;🎉 One paper accepted to FSE 2025 (industry track).
- *2025.04*: &nbsp;🏆 Awarded Outstanding Graduate of Shanghai (上海市优秀毕业生).
- *2024.12*: &nbsp;🏆 ASE 2024 paper received ACM SIGSOFT Distinguished Paper Award.
- *2024.10*: &nbsp;🇨🇭 Completed visiting Ph.D. at ETH Zurich, advised by Prof. Zhendong Su.
- *2024.08*: &nbsp;🎉 One paper accepted to ASE 2024.
- *2023.07*: &nbsp;🏆 ISSTA 2023 paper received ACM SIGSOFT Distinguished Paper Award.
- *2023.05*: &nbsp;🎉 One paper accepted to ISSTA 2023.
- *2021.07*: &nbsp;🎉 One paper accepted to OOPSLA 2021.

</details>

# 📝 Selected Publications

- [ASE 2026] **PropGen: Automated Property Generation for Property-Based Testing of Mobile Apps** <span class="bdg"><span class="l">CCF</span><span class="r">A</span></span>  
  **Yiheng Xiong**, Shiwen Song, Bo Ma, Ting Su, Xiaofei Xie<br>
  ACM/IEEE International Conference on Automated Software Engineering<br>
  [[pdf]](https://xyiheng.github.io//files/PropertyGen_ASE_26_Final_version.pdf) [[repo]](https://xyiheng.github.io)

- [ISSTA 2026] **From Natural Language to Executable Properties for Property-based Testing of Mobile Apps** <span class="bdg"><span class="l">CCF</span><span class="r">A</span></span>  
  **Yiheng Xiong**, Ting Su, Jingling Sun, Jue Wang, Qin Li, Geguang Pu, Zhendong Su<br>
  ACM SIGSOFT International Symposium on Software Testing and Analysis<br>
  [[pdf]](https://dl.acm.org/doi/10.1145/3832108) [[repo]](https://xyiheng.github.io)

- [ISSTA 2026] **Characterizing and Repairing Obsolete Android GUI Tests under UI Evolution** <span class="bdg"><span class="l">CCF</span><span class="r">A</span></span><span class="bdg"><span class="l">ACM SIGSOFT</span><span class="g">Distinguished Paper Award · Top 2.1%</span></span>  
  Shiwen Song, **Yiheng Xiong**<sup>✉</sup>, Wenbo Guo, Manqi Sun, Jiaolong Kong, Xiaofei Xie<br>
  ACM SIGSOFT International Symposium on Software Testing and Analysis<br>
  [[pdf]](https://dl.acm.org/doi/10.1145/3832300) [[repo]](https://xyiheng.github.io)

- [ASE 2024] **General and Practical Property-based Testing for Android Apps** <span class="bdg"><span class="l">CCF</span><span class="r">A</span></span><span class="bdg"><span class="l">ACM SIGSOFT</span><span class="g">Distinguished Paper Award</span></span>  
  **Yiheng Xiong**, Ting Su, Jue Wang, Jingling Sun, Geguang Pu, Zhendong Su<br>
  ACM/IEEE International Conference on Automated Software Engineering<br>
  [[pdf]](https://xyiheng.github.io//files/Property_Based_Testing_for_Android_Apps.pdf) [[repo]](https://github.com/ecnusse/Kea)

- [ISSTA 2023] **An Empirical Study of Functional Bugs in Android Apps** <span class="bdg"><span class="l">CCF</span><span class="r">A</span></span><span class="bdg"><span class="l">ACM SIGSOFT</span><span class="g">Distinguished Paper Award</span></span>  
  **Yiheng Xiong**, Mengqian Xu, Ting Su, Jingling Sun, Jue Wang, He Wen, Geguang Pu, Jifeng He, Zhendong Su<br>
  ACM SIGSOFT International Symposium on Software Testing and Analysis<br>
  [[pdf]](https://xyiheng.github.io//files/ISSTA_2023.pdf) [[repo]](https://github.com/Android-Functional-bugs-study/home)

<a class="btn" href="/publications.html">All Publications</a>

# 🎖 Honors and Awards
- *2026*, ACM SIGSOFT Distinguished Paper Award, ISSTA (**19 of 888 submissions, top 2.1%**)
- *2025*, Outstanding Graduate of Shanghai (上海市优秀毕业生)
- *2024*, National Scholarship (国家奖学金)
- *2024*, Merit Student of East China Normal University (华东师范大学优秀学生)
- *2024*, ACM SIGSOFT Distinguished Paper Award, ASE
- *2023*, ACM SIGSOFT Distinguished Paper Award, ISSTA
- *2023*, Merit Student of East China Normal University (华东师范大学优秀学生)
- *2023*, Joint Ph.D Student Scholarship, CSC (国家留学基金委博士研究生联合培养奖学金)

# 🧑‍🏫 Academic Services
- Program Committee (PC) Member, FSE 2027
- Reviewer, ACM Transactions on Software Engineering and Methodology (TOSEM)
- Reviewer, IEEE Transactions on Software Engineering (TSE)
- Reviewer, Empirical Software Engineering
