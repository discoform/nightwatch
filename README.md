# nightwatch
A responsive layout for a simple blog project


In theory; this basic layout can be used with any type of blogging solution. As-is it achieves perfect lighthouse scores and excellent web vitals scores. 

![Screen Shot 2021-08-31 at 6 50 22 PM](https://user-images.githubusercontent.com/23062181/131598696-87ed1025-5426-49d9-bb84-d869a123f9bf.png)

Best use would probably be a static site generator and an open source CMS solution for a simple, fast, and free solution.

Note that this layout is using [Lite YouTube Embed](https://github.com/paulirish/lite-youtube-embed) to ensure best performance with YouTube video embeds. 

The markup for YouTube embeds should follow this structure:

```
<lite-youtube videoid="YouTube video ID goes here" playlabel="Description of the video goes here"></lite-youtube>
<figcaption>Description of the video goes here</figcaption>
```

Here's what that looks like in the example `index.html`

```
<lite-youtube videoid="88OoZ4mdD0A" playlabel="Lorenzo Senni interview/lecture with Red Bull Music Academy"></lite-youtube>
<figcaption>Lorenzo Senni interview/lecture with Red Bull Music Academy</figcaption>
```
