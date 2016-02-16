---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  title: Test Setup
  image_fullwidth: banner.jpg

widget1:
  title: "Our Physics"
  url: '/physics'
  image: pic01.jpg
  text: 'A neutrino(denoted by the Greek letter ν) is a lepton, an elementary particle with half-integer spin, that interacts only via the weak subatomic force and gravity. The mass of the neutrino is tiny compared to other subatomic particles. Neutrinos are the only identified candidate for dark matter, specifically hot dark matter.'

widget2:
  title: "PandaX project"
  url: 'pandax'
  image: pic02.jpg
  text: 'The PandaX project aims to build ton-scale xenon detectors to search for neutrinoless dobule beta decay and to directly detect the elusive dark matter WIMP. The third phase, PandaX-III, focuses on double beta decay and will use a high pressure xenon-136 (90% enriched) gas time projection chamber to image the possible rare decay.'

widget3:
  title: "CUORE Project"
  url: 'cuore'
  image: pic03.jpg
  text: 'The CUORE collaboration has taken up this challenge by studying the 0νββ decay candidate 130Te. In recent years we have built and analyzed data from the prototype bolometric detectors Cuoricino and CUORE-0. The next stage, planned to start operations in 2016, is the largest bolometric detector ever built: CUORE.'

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
callforaction:
  url: http://kehan.me
  text: Join us ››
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
