# How to perform a Ping Test
A Ping Test will determine if an IP address or hostname is online and the latency between your computer and the remote address. It's important that you have a low ping time from any game server you have, as a high ping can result in lag caused by increase latency, or delayed gameplay.

You first need to understand how to open a console window.

Once your console is open, you will need to send the following command:

```
ping <IP-ADDRESS>
```

Make sure you replace <IP-ADDRESS> with the IP address of the IP or hostname you are trying to test. For example if you wanted to test if google.com is online, you would perform the following:

```
ping google.com
```

When your ping is completed, you will see an output similar to this:

```
Pinging google.com [173.194.115.66] with 32 bytes of data:
Reply from 173.194.115.66: bytes=32 time=16ms TTL=55
Reply from 173.194.115.66: bytes=32 time=17ms TTL=55
Reply from 173.194.115.66: bytes=32 time=16ms TTL=55
Reply from 173.194.115.66: bytes=32 time=13ms TTL=55

Ping statistics for 173.194.115.66:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 13ms, Maximum = 17ms, Average = 15ms
```

Be sure to notice the time reported by these ping tests. In this example the longest time it took to ping google.com was 17ms. The smaller the number, the better, and for game servers, you want this number to be around 90ms or lower, depending on your location, for optimal gameplay.