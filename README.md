# HMS hospital directory

A static list the HMS Staff mobile app reads at start-up to find a hospital's API by its hospital code. It holds names and addresses only, no
secrets. Served by GitHub Pages at `https://yashitgarg.github.io/hms-directory/hospitals.json`. The sandbox entry is rewritten by the QA runner
on the developer Mac whenever the tunnel hostname changes (`deploy/qa/run-qa.sh` in hms-web).
