---
layout: post
title: "Jemeter - Plugins 2018-10-23"
---

1. Jemeter Plugins download - JMeterPlugins-Extras(Standard) and copy .jar package to JMETER_HOME/lib/ext
2. Server Agent
  a. turn on Telnet from Control Panel -> Programs -> Turn Windows features on or off -> Telnet Client
  b. type command "telnet ip 4444" in cmd(4444 is the default port of Server Agent) to test if connection succeed
3. Reference https://www.cnblogs.com/zhaoxd07/p/5197669.html to config 

Note: if Jmeter pop up "Uncaught exception" after adding Listener "jp@gc - PerfMon Metrics Collector", then check if Filename of 
listener result be specified.
