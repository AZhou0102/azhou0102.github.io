In just 4 hours, CERN's CMS detector generates enough raw data to fill all of Amazon's cloud storage. There's no way we can analyze all that data!

CERN scientists have to be selective about what data to keep and what data to toss. A lot of this work is done on servers, through algorithms which selectively parse data for interesting processes. However, the first filter for CMS data is actually on detectors, implemented in low-latency hardware (like FPGAs and ASICs) to instantaneously identify relevant particles. By no means is this an easy task.

At Cornell, I worked under Professor Jennet Dickinson to develop fast ML algorithms that reduce CMS data rates. The goal was to fine-tune lightweight models that could run on FPGAs under strict resource constraints while still being smart enough to pick up on interesting physics.
