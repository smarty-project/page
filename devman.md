[Home](./index.html)

## Device Management

Massively distributed systems are challenging to update while maintaining consistency among the included devices. They pose additional challenges compared to traditional architectures, such as handling systems that are always on, handling a large number of devices, and moving from centralised to edge architectures. It can not be assumed that all devices are available for updating at the same time, and in many cases it is not feasible to shut down the system for updating. This can make it difficult to deploy updates in a consistent and timely manner, which might be crucial when facing security vulnerabilities. Additionally, the updating procedure itself must not open up for new vulnerabilities.

So, at the heart of this part of the project is the requirement to securely distribute and install updated code in remote devices, and to be able to do so in a timely manner that doesn't require the system to be shut down.

As part of our research we have implemented a prototype update mechanism that addresses the issues stated above. We use this mechanism in a demonstrator that we have developed in collaboration with the municipality of Helsingborg.

### Palcom introduction
Our updating mechanism builds on concepts from Palcom, a framework for building IoT systems, and is implemented using the Palcom middleware toolkit. This video gives an introduction to these concepts and basic building blocks of Palcom.

<!-- Palcom Introduction -->
{% include youtubePlayer.html id="Ln4c5Lm_Y60" %}

### Automatic updates
This video further describes the automatic update mechanism implemented in Palcom.

<!-- Automatic Updates -->
{% include youtubePlayer.html id="AU63XRrFu4M" %}


### ComPOS
This video introduces ComPOS, a composition language used in Palcom. ComPOS is used for composing and coordinating services.

<!-- ComPOS Introduction -->
{% include youtubePlayer.html id="0X-kS9hSYxY" %}

### EDOC 2020 Demo video
This demo video was shown at the EDOC 2020 Conference and won the Best Demo award. It showcases our update mechanism using one of the demonstrator scenarios of the project that we have developed together with the municipality of Helsingborg.

<!-- EDOC 2020 Demo video -->
{% include youtubePlayer.html id="TVLZfQT-IRo" %}


### ComPOS - a Domain-Specific Language for Composing Internet-of-Things Systems
This video is the PhD thesis presentation of Alfred Åkesson. It gives a more detailed presentation of ComPOS.

<!-- ComPOS Thesis (30 min) -->
{% include youtubePlayer.html id="tkFkQy3BJ18" %}

### People involved in this part of the project

* [Alfred Åkesson](https://portal.research.lu.se/en/persons/alfred-åkesson)
* [Mattias Nordahl](https://portal.research.lu.se/en/persons/mattias-nordahl)
* [Görel Hedin](https://portal.research.lu.se/en/persons/görel-hedin)
* [Boris Magnusson](https://portal.research.lu.se/en/persons/boris-magnusson)
