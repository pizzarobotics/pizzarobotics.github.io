---
layout: splash
excerpt: "In Pizza we crust"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/background.jpg
  actions:
  - label: ":camera_flash: Instagram"
    url: "https://instagram.com/pizzarobotics"
  - label: ":robot: Discord"
    url: "https://discord.gg/wnumEzwYYd"
intro: 
  - excerpt: 'We are Italian Makers. We make Robots. In Pizza we crust'
feature_row:
  - image_path: /assets/images/team_mfr2021.jpg
    alt: "about"
    title: ":pizza: About"
    excerpt: "Collective of professionals and high-level enthusiasts roboticist. Read more about our team and join in this community."
    url: "/about/"
    btn_label: "read more"
    btn_class: "btn--primary"
  - image_path: /assets/images/events.jpg
    alt: "Events"
    title: ":date: Events"
    excerpt: "Conference, events, PizzaRobotics make your robots and show in all events around the world. "
    url: "/event/"
    btn_label: "events"
    btn_class: "btn--info"
  - image_path: /assets/images/robots.jpg
    alt: "Projects"
    title: ":notebook: Projects"
    excerpt: "We are not making Pizza, but cool projects! Explore all our projects made from our community."
    url: "/projects/"
    btn_label: "explore"
    btn_class: "btn--success"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include discord.html %}