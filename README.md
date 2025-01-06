# Interval Training&hellip;

## &hellip; is annoying

Adding interval training greatly helped my performance when I added it
to my schedule.  Thank you, former UNM Women's Cross Country coach[^1]
for mentioning intervals with thirty second rests, because that seemed
insanely too little of a rest, but that's something I've kept constant
throughout the years.

### Software

In order to compare my intervals from "week to week"[^2], I used to use the
"Movescount" web app to bring up a graph of my pace and then manually
isolate the intervals and then ask Movescount for the average pace for
each interval I selected. This was time consuming, but it gave me data
and I like data.

Eventually, I chose to write
[software](https://github.com/ctm/nom_fun) that automatically
extracted my intervals for me. I used (crappy!) heuristics that seemed
to work well enough to allow me to compare my efforts.  It's a bit
embarrassing because the source is publicly available and it's _really
bad_, but way better (IMO) than nothing.

### Files

Initially I put everything into a single file, `monday_intervals`,
whose filename I later added the `.txt` suffix to, so that it would be
opened as a plain-text document by apps that check suffixes.  In
general, I tried to make this an append-only file so I could make
semi-permanent links to individual days' stats and comments. I
embedded these links in my Strava comments (but now Strava strips URLs
from comments) and in my [BMDM training
logs](https://github.com/ctm/Bataan-Memorial-Death-March/tree/master?tab=readme-ov-file#pack-and-exception-days).

At the beginning of 2025, I chose to start splitting them by year to
make them easier to read on phones. I have a feeling I'll be doing a
lot more with my phone this year.

&nbsp;
&nbsp;
&nbsp;
<hr/>

[^1]: I'll have to look up his name, track him down and eventually thank him in
email or in person; I didn't do it while he was still in New Mexico)

[^2]: Yeah, right. I skip Monday intervals far too frequently to call my
comparisons week to week, but that's my renewed aim (at the time I'm writing
this), so I'll humor myself.
