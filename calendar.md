---
layout: post
title: Calendar
description: Online calendar of seminars and events
image: assets/images/jupiter.jpg
image-show: false
nav-menu: true
show-tile: true
order: 6

---

<script>
function CopyToClipboard(id)
{
var r = document.createRange();
r.selectNode(document.getElementById(id));
window.getSelection().removeAllRanges();
window.getSelection().addRange(r);
document.execCommand('copy');
window.getSelection().removeAllRanges();
}
</script>

<iframe width="900" height="800" src="https://cloud.planetary-research.org/index.php/apps/calendar/embed/sXeNC5x8WqESKwZo"></iframe>

<p></p>
*You can subscribe to this calendar by using this url in your calendar application:*

<span id="calendar">
```https://cloud.planetary-research.org/remote.php/dav/public-calendars/sXeNC5x8WqESKwZo?export```</span>
<a href="#" onclick="CopyToClipboard('calendar');return false;" class="button small">Copy</a>
