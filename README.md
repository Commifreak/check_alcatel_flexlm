# check_alcatel_flexlm
Nagios plugin which searches for licensing problem using incvisu with FlexLM server

# How does it work
This is a php-based tool which connects to the OXE and searches for incidents regarding FlexLM licensing. I use it for our OXE only, so there is no guarantee that it is working for you also (but I think it should - its a simple check).

Tested on:

```
R12.1-m2.300-19
```

**Only working, when the telnet prompt is ```xa001001``` - improvements are welcome ;)**

**The telnet class is modified to work properly!** Original one is from Dalibor Andzakovic.
