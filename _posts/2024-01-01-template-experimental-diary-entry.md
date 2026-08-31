---
title: "Entry title goes here"
date: 2024-01-01
excerpt: "One or two sentences summarizing the entry - this is what shows in the diary list and link previews."
header:
  teaser: your-photo.jpg   # in /media/diary/, shown in the entry list; also used as the featured video's poster
  video: your-clip.mp4     # optional, in /media/diary/ - only set this on the entry you want featured with hover-to-play (muted preview; full sound plays on the article page)
tags:
  - lab-life
published: false # change to true when ready to publish, then rename the file so its date prefix matches "date" above
---

Write the entry here in plain Markdown. A short paragraph, then as many pictures and videos as you like:

![Caption for the photo](/Research/media/diary/your-photo.jpg)

<video controls style="max-width:100%;">
  <source src="/Research/media/diary/your-clip.mp4" type="video/mp4">
</video>

For a YouTube/Vimeo clip instead of a local file, embed it directly:

<iframe width="100%" height="400" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>

Notes on the "date":
- This date is what controls where the entry sits in the timeline and whether it's the featured (newest) one -
  it does not have to match when you actually write or commit the file, so you can backdate entries to 2024.
- The filename must still start with a date (YYYY-MM-DD-title.md), matching "date" above, for Jekyll to
  recognize it as a post.
