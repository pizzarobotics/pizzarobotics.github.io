---
layout: splash
excerpt: "In Pizza we crust"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/background.jpg
intro: 
  - excerpt: 'We are Italian Makers. We make Robots. In Pizza we crust'
feature_row:
  - image_path: /assets/images/about.jpg
    alt: "about"
    title: "About"
    excerpt: "about us"
    url: "/about/"
    btn_label: "about"
    btn_class: "btn--primary"
  - image_path: /assets/images/members.jpg
    alt: "members"
    title: "Members"
    excerpt: "Members"
    url: "/member/"
    btn_label: "members"
    btn_class: "btn--success"
  - image_path: /assets/images/events.jpg
    alt: "events"
    title: "events"
    excerpt: "events"
    url: "/event/"
    btn_label: "events"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/robots.jpg
    alt: "robots"
    title: "Robots"
    excerpt: "Robots"
    url: "/robot/"
    btn_label: "robots"
    btn_class: "btn--warning"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="center" %}