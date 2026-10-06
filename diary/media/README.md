Put Experimental Diary photos and videos here, e.g. `2024-04-15-vacuum-chamber.jpg` or `2024-04-15-plasma-plume.mp4`.

Keep videos short and muted (a few MB, a few seconds) — GitHub repos aren't built for hosting large video files.
For anything longer, upload it to YouTube/Vimeo instead and embed it directly in the post body rather than as
the hover-to-play featured clip (only a locally hosted .mp4 supports the hover play/pause effect).

Reference a file from a post's front matter as just the filename:

```yaml
header:
  teaser: 2024-04-15-vacuum-chamber.jpg   # shown in the entry list
  video: 2024-04-15-plasma-plume.mp4      # optional, only set on the entry you want featured with hover-to-play
```

**Poster images (the still shown before a video plays):** give the image the exact same filename as its
video, just with an image extension - e.g. `Experimental_Room.mp4` and `Experimental_Room.jpg` side by
side. Both the featured hover-video on the diary page and any video embedded in a post body (via
`{% include diary-video.html file="Experimental_Room" %}` - see the template post) automatically pick it
up as the poster, no front matter needed. Setting `header.teaser` explicitly still overrides this for the
featured hero video.

The hover preview on the diary list plays muted; a video's own audio only plays once someone clicks
through to the full article page.
