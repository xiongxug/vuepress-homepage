---
pageClass: home-page
# some data for the components

name: Xu (Sean) Xiong
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/xiongxug
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/xuxiong2/
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: https://www.instagram.com/xiongxu_

cv: /resume_Xu_Xiong.pdf
email: xiongxug@gmail.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Master student at University of Illinois at Urbana-Champaign, majored in Electrical and Computer Engineering.

## News

- [Aug. 2021] Admitted to University of Illinois at Urbana-Champaign
- [Sept 2017] Admitted to Wuhan University

## Education & Experiences

- **University of Illinois at Urbana-Champaign, IL, US** <br/> Expected Dec. 2022

  Master of Engineering in Electrical & Computer Engineering

- **Wuhan University, Wuhan, China** <br/> Sept. 2017 - Jun. 2021

  Bachelor in Computer Science and Technology

- **University of California, Berkeley, US** <br/> Jan. 2020 - Mar. 2020

  Visiting Student in EECS

- **National University of Singapore** <br/> Jul. 2019 - Aug. 2019

  Visiting Student, School of Computing

## Projects

[→ Full list](/projects/)

<ProjectCard image="/projects/1.jpg" hideBorder=true>

**WALL-E-Garbage-classification-robot**

Built a WALL-E-Garbage-classification-robot on Arduino and RaspberryPi.

- Built a WALL-E-object-classification-robot on Arduino and Raspberry Pi that detects and classifies objects and automatically navigates

- Engineered an intelligent mobile platform and designed a web panel in Bottle (Python web framework) and Bootstrap that includes camera streaming, autopilot, and manual control

- Established communication between the computer and Raspberry Pi with MQTT

[[Link](https://isteps.comp.nus.edu.sg/event/sws-y2-19/module/Cluster3/project/9)]

</ProjectCard>

## Awards & Honors

- Scholarship & Outstanding Student Award(Sept. 2019/2020) at Wuhan University
- First place in **‘Zero Cup’ Web Design Competition**

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
