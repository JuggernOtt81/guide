---
title: Make Typography Responsive
---
## Make Typography Responsive

the instructions make it look like one is supposed to use "vmin: 10vmin" format, but that is not the case.
we are still just setting the width here, so keep the same old format, there is nothing new about that.
the new thing here is the units we can use.

THIS WAY:
<style>
  h2
  {
      width: 10vw;
  }

  p
  {
      width: 10vmin;
  }
</style>

NOT THIS WAY:
<style>
  h2
  {
      vw: 10vw;
  }

  p
  {
      vmin: 10vmin;
  }
</style>

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
