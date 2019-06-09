---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image: logo_full-plus-text-hor.png
  background-color: "#316197"
widget1:
  title: "Getting started"
  url: 'http://domain.de/must-be-absolut-url-like-this-one/'
  image: 'https://d35c7d8c.web.cern.ch/sites/d35c7d8c.web.cern.ch/files/styles/home_button/public/imageblock/PH-ROOT-icons-4.png'
  text: ''
widget2:
  title: "Reference guide"
  url: 'http://domain.de/must-be-absolut-url-like-this-one/'
  image: 'https://d35c7d8c.web.cern.ch/sites/d35c7d8c.web.cern.ch/files/styles/home_button/public/imageblock/PH-ROOT-icons-3.png'
  text: ''
widget3:
  title: "Forum"
  url: 'http://domain.de/must-be-absolut-url-like-this-one/'
  image: 'https://d35c7d8c.web.cern.ch/sites/d35c7d8c.web.cern.ch/files/styles/home_button/public/imageblock/PH-ROOT-icons-5.png'
  text: ''
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
