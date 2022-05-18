---
# try also 'default' to start simple
theme: unicorn
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false

website: 'smorcuend.github.io'
handle: '_serxius_'

layout: intro
introImage: 'assets/intro_q.jpg'
preload: false
---

# Sergio Morcuende

<div
  v-motion
  :initial="{
    opacity: 0,
    y: 100,
  }"
  :enter="{
    opacity: 1,
    y: 0,
    transition: {
      delay: 1000
    }
  }"
>
  <SocialBar />
</div>

---
layout: center
mode: ligth
preload: false

website: 'smorcuend.github.io'
handle: '_serxius_'
---
# Roadmap
<div
  v-motion
  :initial="{
    opacity: 0,
    x: 100,
  }"
  :enter="{
    opacity: 1,
    x: 0,
    transition: {
      delay: 1000
    }
  }"
>
<MyNextTimeline />
</div>

---
layout: intro
introImage: 'assets/bloomod.jpg'
website: 'smorcuend.github.io'
handle: '_serxius_'
---
# Projects
* e-Reader software
* Educational Robotics Software > [bitbloq](https://bitbloq.cc)
* Digital In-Image  advertising software
* Data analyst & visualization
* Legaltech software
* Clean Tech > [bloomod](https://bloomod.com)

---
layout: cover-logos
logos: [
  'https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Angular_full_color_logo.svg/2048px-Angular_full_color_logo.svg.png',
  'https://nuxtjs.org/design-kit/colored-logo.png',
  'https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Arduino_Logo.svg/1280px-Arduino_Logo.svg.png',
  'https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/React.svg/1200px-React.svg.png',
  'https://cdn-icons-png.flaticon.com/512/919/919825.png',
  'https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/640px-Python-logo-notext.svg.png',
  'https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/1822px-ISO_C%2B%2B_Logo.svg.png',
  'https://profile.es/wp-content/media/image.png',
  'https://logos-world.net/wp-content/uploads/2021/08/Amazon-Web-Services-AWS-Logo.png',
  'https://opencv.org/wp-content/uploads/2020/07/OpenCV_logo_no_text_.png',
  'https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Gnulinux.svg/1200px-Gnulinux.svg.png',
  'https://res.cloudinary.com/startup-grind/image/upload/c_fill,dpr_2,f_auto,g_center,q_auto:good/v1/gcs/platform-data-mongodb/events/mon.png'
]
website: 'smorcuend.github.io'
handle: '_serxius_'
---
# Tech tools
* e-Reader software
* Educational Robotics Software > [bitbloq](bitbloq.cc)
* Digital In-Image  advertising software
* Data analyst & visualization
* Legaltech software

---
layout: center
mode: ligth

website: 'smorcuend.github.io'
handle: '_serxius_'
---
# Github
[![logo github](https://github.githubassets.com/images/modules/logos_page/Octocat.png)](https://profile-summary-for-github.com/user/smorcuend)

<!-- https://octoprofile.vercel.app/user?id=smorcuend -->
