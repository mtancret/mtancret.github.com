---
layout: default
title: Aveksha
---

<img src="images/aveksha.png" alt="The Aveksha logo." align="left" width="280" title="Aveksha Logo" class="img"/>
<img src="images/tdb.png" alt="Photograph of the Telos Debug Board (TDB), connected to a Telos Rev B mote." align="left" title="TDB" class="img"/>
<br/>

Aveksha is a hardware-software approach for non-intrusively tracing and profiling
sensor network nodes. It is particularly useful for in-field monitoring and debugging
of sensor network applications. The key is to exploit the capabilities of the JTAG
interface present on the sensor nodes application processor, to rapidly poll the
processors state and create a trace of events. The trace is augmented with
energy reading that can be correlated to the events. The hardware prototype we have
created is the Telos Debug Board (TDB). This board is capable of interfacing with the
JTAG port on a Telos (Rev B) mote. It can poll a watchpoint buffer or PC register of
the target processor, while at the same time taking energy readings of the mote.

Code
----
The [source](https://github.com/mtancret/aveksha) is freely
available on GitHub. It is licensed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

Publications
------------

**Best Paper Award:** Matthew Tancreti, Mohammad Hossain, Saurabh Bagchi,
and Vijay Raghunathan. **Aveksha: A Hardware-Software Approach for
Non-intrusive Tracing and Profiling of Wireless Embedded Systems**.
In 9th ACM Conference on Embedded Networked Sensor Systems (SenSys),
14 pages, Seattle, Washington, November 1-4, 2011.
(Acceptance rate: 24/123 = 19.5%)  
DOI>\[ [10.1145/2070942.2070972](http://dx.doi.org/10.1145/2070942.2070972) \]  
Author''s version: \[ [PDF](documents/aveksha-sensys2011-author.pdf) \]  
Presentation slides: \[ [PDF](documents/presentation-aveksha-sensys2011.pdf) \]  

Matthew Tancreti, Mohammad Hossain, Saurabh Bagchi, and Vijay Raghunathan.  
**Demo Abstract: Aveksha - A Hardware-Software Approach for Non-intrusive
Tracing and Profiling of Wireless Embedded Systems**.
In 9th ACM Conference on Embedded Networked Sensor Systems (SenSys),
2 pages, Seattle, Washington, November 1-4, 2011.  
Demo abstract: \[ [PDF](documents/demo-aveksha-sensys2011.pdf) \]  
Poster: \[ [PDF](documents/poster-aveksha-sensys2011.pdf) \]  

