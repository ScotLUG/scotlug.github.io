---
layout: thumbnail
media:
- uri: /assets/scottish_tux.svg
  alt: Scottish Tux
title: Welcome
lead: This is the official site for the **Scottish Linux User Group** in Glasgow.

---
    {% assign meeting = site.categories.meetings.first %}
<!-- /* comment out until august 2026 */ -->
To celebrate [Software Freedom Day][https://digitalfreedoms.org/en/sfd] ScotLUG will be running an **[{{ meeting.title }}]({{ meeting.url }})**, is on {{ meeting.date | date: "%A, %-d %B" }}.

The [{{ meeting.title }}]({{ meeting.url }}) will be taking place at the [The Gamer Club][https://www.thegamerclub.co.uk/] at [153 Bath Lane, Glasgow, G2 4RH][https://www.thegamerclub.co.uk/gettinghere] between 12:00 and 16:30.
<!-- /* Electron club meeting details */
Meetings are usually held at 19:00, with the talk beginning at 19:15, every last Thursday of the month at the [Electron Club][].  Check out our past meetings, what's on this month, and what might be coming up on our [meetings](/meetings) page.
-->

Our IRC channel, [#scotlug][] on libera.chat (or [Matrix][]), is usually helpful.  There is a [mailing list][] for general announcements.

In addition to Glasgow, [Falkirk][] and [Edinburgh][] both have active Linux User Groups.  The [UK Linux User Groups organisation][] has a list of other [user groups across Scotland][].

[Electron Club]: http://www.electronclub.org/doku.php?id=welcome#where_to_find_us
[#scotlug]: https://web.libera.chat/#scotlug
[Matrix]: https://matrix.to/#/#scotlug:glasgow.social
[mailing list]: http://mailman.lug.org.uk/mailman/listinfo/scottish
[Falkirk]: https://plus.google.com/115476628113417487323
[Edinburgh]: http://www.edlug.org.uk/
[UK Linux User Groups organisation]: https://lug.org.uk/
[user groups across Scotland]: https://lug.org.uk/lugs/Scotland
[Registration and more information is available here]: https://2015.spaceappschallenge.org/location/glasgow/
