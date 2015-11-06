# How to perform a Traceroute
Traceroute is a network diagnostic tool which displays the connection "hops" your computer must make to connect to the target host. Similar to the Ping Test, this will help you identify any problems when connecting to a server.

You first need to understand how to open a console window.

Once your console is open you need to send the following command:

### Windows:

```
tracert <IP-ADDRESS>
```

### Mac & Linux:

```
traceroute <IP-ADDRESS>
```

Make sure you replace <IP-ADDRESS> with the IP address of the IP or hostname you are trying to test. For example, if you wanted to perform a traceroute to google.com, would input the following:

```
tracert google.com
```

When your traceroute is completed, you will see and output similar to the following:

```
Tracing route to google.com [74.125.227.195]
over a maximum of 30 hops:

  1    <1 ms    <1 ms    <1 ms  192.168.1.1
  2     8 ms    11 ms    10 ms  10.10.128.1
  3     7 ms    11 ms     8 ms  COX-68-12-10-52-static.coxinet.net [68.12.10.52]

  4    12 ms    12 ms    11 ms  COX-68-12-8-84-static.coxinet.net [68.12.8.84]
  5    25 ms    28 ms    19 ms  mtc3dsrj01-ae4.0.rd.ok.cox.net [68.12.14.0]
  6    22 ms    24 ms    29 ms  dalsbprj02-ae2.0.rd.dl.cox.net [68.1.2.121]
  7    13 ms    16 ms    18 ms  72.14.212.237
  8    29 ms    21 ms    15 ms  72.14.233.85
  9    14 ms    26 ms    15 ms  64.233.174.139
 10    15 ms    13 ms    15 ms  dfw06s33-in-f3.1e100.net [74.125.227.195]

Trace complete.
```

Be sure to notice the time reported between hops. If any particular HOP (other than core routers not responding to ICMP ping requests) has a timeout (marked with a *), or vastly increased latency times, there may be a network problem that you can contact us to investigate. Depending on where the problem resides, we may be able to help resolve the issue, however there are times where issues upstream such as with tier 1 providers such as Level 3 are simply out of our control.