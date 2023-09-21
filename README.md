# FinanceDB
This will slowly turn into a (unoptimized) CLI finance tracker. This will primarily be done with python and shell scripts.

The idea is to take financial statements whether banking, investment, paystubs, etc. as input, parse them, normalize the parsed data, import to a database, then use a handful of commands to do some basic tracking.

As a side effect, this project will also serve as practice using GitHub properly with the official CLI client.

TODO
+ Prepare list of needed components to install
  + python3
  + pdf parser (pdftotext)
  + database component (undecided)
+ Setup file structure in repo
+ Write scripts
  + Statement fetcher (if allowed by institution, otherwise fetch manually)
  + Pdf parser
  + normalizer.py (Takes parsed statement as input, normalizes output. May need to write multiple based on statement organization)
  + DB import
  + ...
+ Setup a handful of commands to use in CLI
+ Create webpage primarily for testing. Intention of project to be used with CLI.
