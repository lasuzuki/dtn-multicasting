# Multicasting over the Interplanetary Internet :rocket:
This project has been developed by Dr Lara Suzuki :woman_technologist: [![Twitter](https://img.shields.io/twitter/url/https/twitter.com/larasuzuki.svg?style=social&label=Follow%20%40larasuzuki)](https://twitter.com/larasuzuki) and supervised by Vint Cerf :technologist: [![Twitter](https://img.shields.io/twitter/url/https/twitter.com/vgcerf.svg?style=social&label=Follow%20%40vgcerf)](https://twitter.com/vgcerf), both at Google Inc.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/lasuzuki/StrapDown.js/graphs/commit-activity)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
![Profile views](https://gpvc.arturio.dev/lasuzuki)
[![GitHub contributors](https://img.shields.io/github/contributors/Naereen/StrapDown.js.svg)](https://GitHub.com/lasuzuki/StrapDown.js/graphs/contributors/)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![saythanks](https://img.shields.io/badge/say-thanks-ff69b4.svg)](https://saythanks.io/to/lasuzuki)

[![ForTheBadge built-with-science](http://ForTheBadge.com/images/badges/built-with-science.svg)](https://GitHub.com/lasuzuki/)

# Multicasting

Multicasting over the Interplanetary Internet uses version 7 of the Bundle Protocol. In a multicasting scenario, we send messages to a multicasting end point and the messages are propagated across the nodes of the network, removing the need to send data to individual nodes one at a time.

Use multicasting when the messages you are sending should be delivered to all the known nodes of the network.

# Basic Concepts of the Bundle Protocol Version 7

This section gives an overview of bundle protocols, referring to [RFC 4838](Cerf, V.G., Burleigh, S.C., Durst, R.C., Fall, K., Hooke, A.J., Scott, K.L., Torgerson, L., Weiss, H.S.: Delay-Tolerant Networking Architecture. Tech. Rep. RFC
4838, IETF (2007))
and the current version of the [Bundle Protocol (BP)](Burleigh, S., Fall, K., Birrane, E.J.: Bundle Protocol Version 7 (draft version 13).
Tech. rep., IETF (2019)).