# MHN Honeypot

## Honeypot(s) deployed

* Dionaea with HTTP

## Issues encountered

* Commands take a *long* time to run and don't provide much feedback
  to know if they're actually doing anything or just frozen
* Google Cloud Compute doesn't work with the Google accounts managed
  by the university IT department, so I had to use a personal account
* Assignment required Ubuntu 14.04 (almost four years old) instead of
  a newer release
* A lot of the software uses Python 2.x, which is EOL in 21 months

## Summary of data collected

After maybe an hour or two of being active, the honeypot recorded 433
attacks. Most of the attacks came from my IP address (nmap scans), but
there were quite a few from other countries, including (but not limited to):
* Russia
* China
* India
* Japan
* The Netherlands
* Canada
* United Kingdom

## Unresolved questions

While I was able to record a decent number of attacks, I don't
actually know if they were real attacks or something more innocent,
like a crawler/indexer for a search engine. I'm sure there is a way to
determine they're legitimate traffic or attempts to break into the
system, but that's a bit beyond the scope of this assignment. It would
be interesting to see though.
