<p>
  <center>
    <img src="https://user-images.githubusercontent.com/1423657/39084356-c723a81e-4574-11e8-963c-d11717789fa3.png" width=200/>
  </center>
</p>

#### HOMER: 100% Open-Source VoIP Capture, Troubleshooting & Monitoring


![H5](https://img.shields.io/badge/HOMER-7-red.svg)
![HEP](https://img.shields.io/badge/proto-hep_eep-blue.svg)
![HEP](https://img.shields.io/badge/proto-sip-brightgreen.svg)
![HEP](https://img.shields.io/badge/proto-rtcp-brightgreen.svg)
![HEP](https://img.shields.io/badge/proto-rtcp_xr-brightgreen.svg)
![HEP](https://img.shields.io/badge/proto-rtp_stats-brightgreen.svg)
![HEP](https://img.shields.io/badge/text-QoS-green.svg)
![HEP](https://img.shields.io/badge/text-syslog-green.svg)
![HEP](https://img.shields.io/badge/text-CDRs-green.svg)



**HOMER** is a robust, carrier-grade, scalable Packet and Event capture system and VoiP/RTC Monitoring Application based on the [HEP/EEP](http://github.com/sipcapture/hep) protocol and ready to process & store insane amounts of signaling, rtc events, logs and statistics with instant search, end-to-end analysis and drill-down capabilities.

**HOMER** is already used by large enterprises, voice network operators, voip service providers and traffic carriers worldwide, has been implemented as a service in 3rd party voice platforms and is suitable for production. 

<br/>

--------
### HEP STACK
#### HEP Servers

| Name          | Role   | Features | Link |
|---------------|--------|----------|------|
| HEPop         | server | core     | http://github.com/sipcapture/hepop |
| HEPlify-server| server | core     | http://github.com/sipcapture/heplify-server |

#### HEP Agents
| Name          | Role   | Features | Link |
|---------------|--------|----------|------|
| HEPlify       | agent  | external | http://github.com/sipcapture/heplify |
| CaptAgent     | agent  | external | http://github.com/sipcapture/captagent |

#### Native HEP Agents
HOMER and its HEP protocol are natively supported at the core of all leading VoiP/RTC projects:

| Name          | Role   | Features | Link |
|---------------|--------|----------|------|
| OpenSIPS      | agent  | SIP/TLS, LOGS, MI, REST, HEP-Relay | http://github.com/opensips |
| Kamailio      | agent  | SIP/TLS, LOGS | http://github.com/kamailio |
| FreeSwitch    | agent  | SIP/TLS, ESL(rtcp,logs) | http://github.com/freeswitch |
| Asterisk      | agent  | SIP/TLS, RTCP | https://github.com/digium |
| sipgrep       | agent  | SIP  | https://github.com/sipcapture/sipgrep |
| sngrep        | agent  | SIP, HEP-Relay | https://github.com/irontec/sngrep |

#### Middleware HEP Agents
HEP messages can be generated from just about any logfile, event, streaming protocol.

| Name          | Role   | Features | Link |
|---------------|--------|----------|------|
| paStash       | agent  | Logs, AMI/ESL, Janus, Mediasoup, Queues, Any | http://github.com/sipcapture/pastash |
| hepipe.js     | agent  | ESL, Janus, Logs | http://github.com/sipcapture/hepipe.js |

#### HEP Generators
HEP messages can be forged synthetically for CI and load-testing purposes:

| Name          | Role   | Features | Link |
|---------------|--------|----------|------|
| hepgen.js     | agent  | Generate HEP from scenarios | http://github.com/sipcapture/hepgen.js |
| hammerHEP     | agent  | Generate HEP bulk load-tests | http://github.com/negbie/hammerHEP |


### Support
For professional support, remote installations, customizations or commercial requests please contact: support@sipcapture.org

For community support, updates, user discussion and experience exchange please join our users   [Mailing-List](https://groups.google.com/forum/#!forum/homer-discuss)

For commercial licensing and support, please contact the QXIP Team at [http://qxip.net]

<img src="http://i.imgur.com/9AN08au.gif" width=100% height=50 >



### Developers
Contributors and Contributions to our project are always welcome! If you intend to participate and help us improve HOMER by sending patches, we kindly ask you to sign a standard [CLA (Contributor License Agreement)](http://cla.qxip.net) which enables us to distribute your code alongside the project without restrictions present or future. It doesn’t require you to assign to us any copyright you have, the ownership of which remains in full with you. Developers can coordinate with the existing team via the [homer-dev](http://groups.google.com/group/homer-dev) mailing list. If you'd like to join our internal team and volounteer to help with the project's many needs, feel free to contact us anytime!


### License & Copyright

![H5](https://img.shields.io/badge/license-GNU_AGPL_v3-blue.svg)

Homer components are released under the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

*(C) 2008-2018 [QXIP BV](http://qxip.net)*

----------

#### Made by Humans
This Open-Source project is made possible by actual Humans without corporate sponsors, angels or patreons.<br>
If you use this software in production, please consider supporting its development with contributions or [donations](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=donation%40sipcapture%2eorg&lc=US&item_name=SIPCAPTURE&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=donation%40sipcapture%2eorg&lc=US&item_name=SIPCAPTURE&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest) 
