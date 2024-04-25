iptables-view
=============

Perl script to view iptables rules.

perlmonks-iptables-real-time-monitor
=====================================

Source:  [perlmonks](https://www.perlmonks.org/?node_id=513732)

"In trying to solve a problem setting up iptables on my Linux gateway box, I wrote a Perl script to display netfilter activity in real-time. Every second, it grabs output from the iptables list utility, including counters (which are then zeroed). It displays this data with extraneous lines removed, highlighting the lines with non-zero packet counts in color. It's designed to run in an xterm window and uses ANSI escape sequences to control the text. To be effective, the xterm window needs to be at least as high as the output, else scrolling will ruin the visual effect. Also, the code may be iptables version-dependent, as it matches certain keywords for the formatting. Once started, it can be stopped with a ctl-C, which will restore some of the display settings. Herewith is the code:"

other tools
===========

[iptstate](https://github.com/jaymzh/iptstate/?tab=readme-ov-file)

WHAT IS IP TABLES STATE?

IP Tables State (iptstate) was originally written to implement the "state top" feature of IP Filter (see "The Idea" below) in IP Tables. "State top" displays the states held by your stateful firewall in a top-like manner.

Since IP Tables doesn't have a built in way to easily display this information even once, an option was added to just have it display the state table once.

Features include:

- Top-like realtime state table information
- Sorting by any field
- Reversible sorting
- Single display of state table
- Customizable refresh rate
- Display filtering
- Color-coding
- Open Source (specifically I'm using the zlib license)