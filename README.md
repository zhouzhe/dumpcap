dumpcap
=======

Provides an interface to [Wireshark](https://www.wireshark.org)'s `dumpcap` tool for the go programming language (golang).

You can use `dumpcap` to
* find out about available network interfaces and their supported capabilities. See [here](https://github.com/lukaslueg/dumpcap/blob/master/examples/devices/devices.go) for an example.
* Receive live statistics about traffic seen on each interface. See  [here](https://github.com/lukaslueg/dumpcap/blob/master/examples/statistics/statistics.go) for example.
* Capture traffic and save it to disk for further processing. See [here](https://github.com/lukaslueg/dumpcap/blob/master/examples/capture/capture.go) for an example.

On most BSD/Linux distributions `dumpcap` comes suid'd so one can capture traffic using this isolated single-purpose process and does not need root credibilities to dissect captured traffic.

You may be interested in [gopacket](https://code.google.com/p/gopacket/) to dissect network data from within go.


[![GoDoc](https://godoc.org/github.com/lukaslueg/dumpcap?status.svg)](https://godoc.org/github.com/lukaslueg/dumpcap) [![Build Status](https://travis-ci.org/lukaslueg/dumpcap.svg?branch=master)](https://travis-ci.org/lukaslueg/dumpcap)
