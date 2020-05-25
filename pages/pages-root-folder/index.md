---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: index-logo.jpg

# widget1:
#   title: "Blog"
#   url: '/blog/'
#   image: widget-1-302x182.jpg
#   text: 'Blog about my accomplishments, fresh news, thoughts, developments, and activities. Go to a quick overview of all my posts.'
# widget-ideas.jpeg

widget2:
  title: "About Me"
  url: '/about-me/'
  text: 'Short section about my experiences, skills and interests.'
  image: widget-myself.png

widget3:
  title: "Self-Education"
  url: '/ideas/'
  image: widget-1-302x182.jpg
  text: 'Courses, Projects and Ideas I want to accomplish.'
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
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features 
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https:/#www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
