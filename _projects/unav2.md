---
title: "UNav2"
excerpt: ""
author: "Alessio Morale"
classes: wide
number: 2022
link: https://blog.alessiomorale.com/unav2/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/assets/images/projects/unav2/unav2_v0.jpg"
  teaser: "/assets/images/projects/unav2/unav2_v0.jpg"
---


[uNav2](https://blog.alessiomorale.com/unav2) was born as a STM32 based redesign of [uNav](https://rnext.it/project/unav/) (based on PIC32).
It is a motor controller board that integrates with ROS. it is currently used to "move" [Slammer](https://alessiomorale.com/wordpress/tag/slammer/).

This board includes a STM32F405 and two DRV8871 drivers. It supports motor current feedback using two INA186 and global battery current/voltage monitor using an INA219. Additionally there is an LM75 temperature monitor ic, a fan output and switching supply for 5V to power the board and the motor encoders.

![](/assets/images/projects/unav2/unav2_v0.jpg)

## References

[HW repository](https://github.com/AlessioMorale/unav2_hardware/tree/master/integrated_board), there are a few issues (i'm adding them to the GitHub project to keep track of all changes needed)

[Interactive BOM](https://htmlpreview.github.io/?https://raw.githubusercontent.com/AlessioMorale/unav2_hardware/master/integrated_board/bom/ibom.html) (built with the awesome [InteractiveHtmlBom plugin](https://github.com/openscopeproject/InteractiveHtmlBom))

![](https://raw.githubusercontent.com/AlessioMorale/unav2_hardware/master/integrated_board/rendering_top.png)
