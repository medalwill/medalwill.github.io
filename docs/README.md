---
pageClass: home-page
# some data for the components

name: Renshuai Liu
profile: /profile1.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/medalwill
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.cn/incareer/in/ACoAAD9tTDEBP8XrYB7uowP4W7c2wT7SOcnkrZM

# researchgate: https://en.wikipedia.org/wiki/Harry_Potter
bio: Student at Xiamen University
email: medalwill@stu.xmu.edu.cn
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me
<!-- (https://vcg.xmu.edu.cn/) -->
I'm currently a graduate student in the [Visual Computing and Graphics Lab](https://vcg.xmu.edu.cn/) of Xiamen University, supervised by associate professor Xuan Cheng. 
<!--From 2022.6 to 2022.9, I served as a research intern at [Virtual Human Group](https://fuxivirtualhuman.github.io/) of [NetEase Fuxi AI Lab](https://fuxi.163.com/), working with [Zhimeng Zhang](https://scholar.google.com/citations?user=FGRtKVoAAAAJ&hl=zh-CN&oi=ao) and [Yu Ding](https://scholar.google.com/citations?hl=zh-CN&user=T9Vd-rcAAAAJ&view_op=list_works&sortby=pubdate).-->

My research interests lie at Computer Vision and Computer Graphics. I'm particularly interested in the areas of face completion and multi-exposure image fusion.
## News
- [Nov. 2022] Our work on multi-exposure image fusion has been accepted by AAAI2023.

## Some of my paper co-authors
<!-- [Jing Liao](https://liaojing.github.io/html/), Assistant Professor with the Department of Computer Science, City University of Hong Kong <br> -->
Xuan Cheng, Assistant Professor at School of Informatics, Xiamen University <br>
[Ming Zeng](http://mingzeng.xyz/), Associate Professor at School of Informatics, Xiamen University <br>
[Yinglin Zheng](https://yinglinzheng.netlify.app/), Research Intern at Visual Computing Group, Microsoft Research Asia (MSRA) <br>
[Wenjin Deng](https://wenjindeng.netlify.app/), Research Intern at Virtual Human Group of NetEase Fuxi AI Lab <br>

## Publications

Coming Soon!😆

<!--<ProjectCard hideBorder=true image="https://s1.ax1x.com/2022/04/21/LyGJKK.png">-->

<!--  I^2R-Net: Intra- and Inter-Human Relation Network for Multi-Person Pose Estimation-->

<!--  Yiwei Ding*, **Wenjin Deng***, Yinglin Zheng, Pengfei Liu, Jianmin Bao, Meihong Wang, Xuan Cheng, Ming Zeng, Dong Chen-->
  
<!--  2022, The 31st International Joint Conference on Artificial Intelligence (IJCAI2022)-->

<!-- [Paper](https://arxiv.org/pdf/2206.10892.pdf) [Code](https://github.com/leijue222/Intra-and-Inter-Human-Relation-Network-for-MPEE)-->

<!--</ProjectCard>-->


<!--## Projects-->

<!--<ProjectCard hideBorder=true image="/projects/case.png">-->

<!--  A management system for case workflow-->

<!--  Java Backend: **Wenjin Deng**, [Pengfei Liu](https://github.com/BlacksLiu)-->

<!--  H5 frontend: [Yiwei Ding](https://github.com/leijue222), **Wenjin Deng**-->
  
<!--  2021-->

<!--</ProjectCard>-->

<!--<ProjectCard hideBorder=true image="/projects/watermeter.png">-->

<!--  Watermeter Reader Autonomous System for paper *Image-Based Automatic Watermeter Reading under Challenging Environments*-->

<!--  Java Backend: **Wenjin Deng**, Jian Wang-->

<!--  H5 frontend: [Yiwei Ding](https://github.com/leijue222)-->
  
<!--  2020-->

<!--  [Paper Link](https://www.mdpi.com/1424-8220/21/2/434)-->

<!--</ProjectCard>-->

<!--<ProjectCard hideBorder=true image="/projects/iFit.png">-->
<!--  AI fitness coach in web(PC/Mobile) using our Human Pose Estimation Network. Benefit from our design, it infers well pose on user's local device with 25fps.-->

<!--  Human Pose Estimation Algorithm & Website: [Zihao Chen](https://github.com/sppleHao), **Wenjin Deng**-->

<!--  Team: Ximeng Zhou, [Zihao Chen](https://github.com/sppleHao), **Wenjin Deng**, Yilin Huang-->

<!--  2018.08-2019.5-->

<!--  [Media Report](https://www.sohu.com/a/315247559_685340)-->

<!--</ProjectCard>-->

<!--<ProjectCard hideBorder=true image="/projects/ooad.png">-->
<!--  A course system in web(PC/Mobile) using Springboot and VUE.-->

<!--  Java Backend: [Shiqi Wang](https://github.com/17Wang), **Wenjin Deng**-->

<!--  H5 frontend: Tianyu Su, [Zihao Chen](https://github.com/sppleHao)-->

<!--  2018.11-2019.1-->

<!--  [Project Link](https://github.com/OOAD2-3/RBS)-->

<!--</ProjectCard>-->



<!--## Awards & Honors-->

<!--- **Outstanding prize (1st place)** of the 12nd "Intel Cup" national undergraduate software innovation competition, Shanghai, China, 2019.-->


## Education & Experiences
- **School of Informatics, Xiamen University.** <br/>
Sept. 2021 - present

- **School of Informatics, Xiamen University, B.S.** <br/>
Sept. 2017 - 2021

## Thanks
Many thanks to my bros [Yinglin Zheng](https://yinglinzheng.netlify.app/), [Wenjin Deng](https://wenjindeng.netlify.app/) and my mentor Xuan Cheng.
<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
