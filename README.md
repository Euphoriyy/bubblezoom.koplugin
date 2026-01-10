# Bubble Zoom KOReader Plugin

This plugin enables users to magnify the selected (tapped or long-pressed) speech bubble in a comics/manga page. You can access the plugin's settings from the top Typesetting (second from the left) menu.

<img src="img/bubblezoom_demo_low.gif" width="450">

*Plugin preview*


# Installation

Download the latest plugin from the [relases](https://github.com/anezih/bubblezoom.koplugin/releases). Copy the `bubblezoom.koplugin` folder to your KOReader installation's `plugins` directory.


# Disclosure

I've written and streamlined the image processing worklow (luma calculations, integral images, sauvola thresholding, flood fill and morphological closing) in C# as a PoC. Yet, I've used ChatGPT codex to create the final lua plugin as KOReader documentation's drawing and input interception parts are not easy to get into.

# References
- J. Sauvola and M. Pietikainen, “Adaptive document image binarization,” Pattern Recognition 33(2), pp. 225-236, 2000. DOI:10.1016/S0031-3203(99)00055-2

- Comic shown in the preview video: https://www.teamfortress.com/tf05_old_wounds/