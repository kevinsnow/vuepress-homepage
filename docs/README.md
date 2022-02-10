---
pageClass: home-page
# some data for the components

name: Kevin XIA
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/kevinsnow
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/zhaobinxia/
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: 

bio: Senior DevOps
email: kevin (at) neversummer (dot) net
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

TBA


## News

- [Feb 2022] Started my public cloud and DevOps journey as Senior DevOps
- [Dec 2016] Joined Boeing as Systems Analyst


## Education & Experiences

- **National University of Singapore** <br/>
2017 - 2018

TBA


## Projects


[→ Full list](/projects/)

<ProjectCard hideBorder=true>

  TBA


</ProjectCard>

<ProjectCard hideBorder=true>

  **Title**
  
  TBA

  [[Link](https://www.google.com)]

</ProjectCard>


## Awards & Honors

- TBA


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
