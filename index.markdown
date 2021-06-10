---
layout: thumbnail
media:
- uri: /assets/scottish_tux.svg
  alt: Scottish Tux
title: Welcome
lead: This is the official site for the **Scottish Linux User Group** in Glasgow.

---

{% assign meeting = site.categories.meetings.first %}
The next meeting, **[{{ meeting.title }}]({{ meeting.url }})**, is on {{ meeting.date | date: "%A, %-d %B" }}.

Meetings are held at 19:00, with the talk beginning at 19:30, every last Thursday of the month at the [Electron Club][].  Check out our past meetings, what’s on this month, and what might be coming up on our [meetings](/meetings) page.

Our IRC channel, [#scotlug][], is usually busy and helpful.  There is a [mailing list][] for general announcements.

In addition to Glasgow, [Falkirk][] and [Edinburgh][] both have active Linux User Groups.  The [UK Linux User Groups organisation][] has a list of other [user groups across Scotland][].

[Electron Club]: http://www.electronclub.org/doku.php?id=welcome#where_to_find_us
[#scotlug]: https://web.libera.chat/#scotlug
[mailing list]: http://mailman.lug.org.uk/mailman/listinfo/scottish
[Falkirk]: https://plus.google.com/115476628113417487323
[Edinburgh]: http://www.edlug.org.uk/
[UK Linux User Groups organisation]: https://lug.org.uk/
[user groups across Scotland]: https://lug.org.uk/lugs/Scotland
[Registration and more information is available here]: https://2015.spaceappschallenge.org/location/glasgow/
