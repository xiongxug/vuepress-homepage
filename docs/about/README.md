---
pageClass: about-page
description: 'The biography and information about me.'
avatar: /profile.jpg
head: 'Xu (Sean) Xiong'
info: 'Student at Wuhan University'
interests: 'Interests: Coding'
socials:
- title: github
  link: https://github.com/xiongxug
- title: linkedin
  link: https://www.linkedin.com
- title: instagram
  link: https://www.instagram.com
- title: email
  link: ‘mailto:xiongxug@gmail.com'
actions:
- text: Projects
  link: /projects/
- text: Blog
  link: https://github.com/mtobeiyf
- text: CV
  link: /article/
footer: Made with ♥ by Sean. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

I’m a student at Wuhan University.

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)

  .last-updated
    display none

</style>