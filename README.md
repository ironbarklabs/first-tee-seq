# GIANT WARNINGS  
This is just a helper tool - it's not perfect. It gets things mostly right, but not always. 

** dont poll clubs into oblivion - thats rude. Grab your data once, and move on. 

# First Tee SEQ

A single self-contained page listing public tee times at golf clubs around
South East Queensland, ranked by driving time from wherever you say you are
starting.

**The page:** https://ironbarklabs.github.io/first-tee-seq/

This repository holds only the built page. It is a generated artefact — the
scraper that produces it is not published here.

## What it does

Reads the public guest booking pages that clubs already publish, collapses the
several products a club sells against one clock time (18 walking, 9 holes, cart
deals) back into a single physical tee time, and lets you filter by day, party
size, holes, cart and price. Drive times, weather and sunset are worked out in
your browser, so moving the start point re-ranks everything without re-reading
anything.

**It books nothing.** Every result links back to the club's own booking sheet
on the right date. Tee sheets move between refreshes; the club's page is always
the truth.

## Refreshing

The page carries a snapshot from when it was last published, and says how old
that is. **Refresh data** re-reads the clubs live from your browser and takes a
few minutes. That reads only the public guest booking paths each club already
serves to the open web, one request per second per club.

The refresh updates the page in front of you; reloading returns you to the
published snapshot.
