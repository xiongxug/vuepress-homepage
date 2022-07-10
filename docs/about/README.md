---
pageClass: about-page
description: "The biography and information about me."
avatar: /profile.jpg
head: "Xu Xiong"
info: "ECE@UIUC"
interests: "Interests: Coding and brewing coffee"
socials:
  - title: github
    link: https://github.com/xiongxug
  - title: linkedin
    link: https://www.linkedin.com/in/xuxiong2/
  - title: instagram
    link: https://www.instagram.com/xiongxu_
  - title: email
    link: ‘mailto:xiongxug@gmail.com'
actions:
  - text: Projects
    link: /projects/
  - text: CV
    link: /resume_Xu_Xiong.pdf
footer: Made with ♥ by Xu. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

Master student at University of Illinois at Urbana-Champaign

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)

  .last-updated
    display none

</style>
