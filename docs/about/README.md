---
pageClass: about-page
description: 'The biography and information about me.'
avatar: /profile.jpg
head: 'Kevin, Zhaobin XIA'
info: 'Senior Engineer @ Tencent'
interests: 'Interests: Hiking, Marvel movies and series.'
socials:
- title: github
  link: https://github.com/kevinsnow
- title: linkedin
  link: https://www.linkedin.com/in/zhaobinxia/
- title: instagram
  link: 
- title: email
  link: 'mailto:kevin[at]neversummer.com'
actions:
- text: Projects
  link: /projects/
- text: Blog
  link: https://github.com/kevinsnow
- text: CV
  link: /article/
footer: Made with ♥ by Fing. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

Test

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>
