Put Experimental Diary photos and videos here, e.g. `2024-04-15-vacuum-chamber.jpg` or `2024-04-15-plasma-plume.mp4`.

Keep videos short and muted (a few MB, a few seconds) — GitHub repos aren't built for hosting large video files.
For anything longer, upload it to YouTube/Vimeo instead and embed it directly in the post body rather than as
the hover-to-play featured clip (only a locally hosted .mp4 supports the hover play/pause effect).

Reference a file from a post's front matter as just the filename:

```yaml
header:
  teaser: 2024-04-15-vacuum-chamber.jpg   # shown in the entry list; also used as the featured video's poster
  video: 2024-04-15-plasma-plume.mp4      # optional, only set on the entry you want featured with hover-to-play
```

The hover preview on the diary list plays muted; a video's own audio only plays once someone clicks
through to the full article page.
