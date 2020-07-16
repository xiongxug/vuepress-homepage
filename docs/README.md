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
    link: https://www.linkedin.com
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: https://www.instagram.com

cv: https://drive.google.com/file/d/1LgIl1cL2oO2jVD1FU7kHvXifr2VjIW5T/view?usp=sharing
bio: Student at Wuhan University
email: xiongxug@gmail.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I’m a student at Wuhan University


## News

- [Sept 2017] Admitted to Wuhan University


## Education & Experiences

- **Wuhan University, Wuhan, China** <br/>September 2017 - present

  Bachelor in Computer Science and Technology


## Projects


[→ Full list](/projects/)

<ProjectCard image="/projects/1.jpg" hideBorder=true>

  **WALL-E-Garbage-classification-robot**

Built a WALL-E-Garbage-classification-robot on Arduino and RaspberryPi.

Using the object detection algorithm Mask RCNN to perform object detection on the video stream acquired by the Raspberry Pi. The identified objects are then classified by the InceptionV3. Used Bottle (Python Web Framework) and Bootstrap build a Web Panel which involved Camera Streaming, Autopilot and Manual control. Communicate computer and RaspberryPi with MQTT (message Queue Telemetry Transport)

[[Link](https://isteps.comp.nus.edu.sg/event/sws-y2-19/module/Cluster3/project/9)]

</ProjectCard>


## Awards & Honors

### Contests

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
