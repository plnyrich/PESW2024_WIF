# Network Traffic Analysis Using Weak Indicators
This thesis studies methods for network traffic classification, threat detection, and network security monitoring. Firstly, an extensive overview of network traffic classification and threat detection methods is performed. Then, a new software library called Weak Indication Framework (WIF) is introduced to ease the development of new threat detector systems. It was designed based on the studied methods. Detectors built on top of the Weak Indication Framework are highly explainable and efficient enough for operation on high-speed networks with 400Gbps backbone lines. Furthermore, several detectors were developed on top of the new Weak Indication Framework to demonstrate its usability and ease of use. The detectors were selected with the help of the thesis supervisor: detector of Tor communication, detector of cryptomining (and cryptomalware), detector of covert communication tunnels (used by malware for Command and Control communication and data exfiltration), and finally, detector of IoT malware (such as Mirai). All developed detectors were successfully deployed to the national network CESNET3 with more than half a million users, operated by Czech National Research and Education Network (NREN) operator CESNET.

[Link to the thesis on the CTU DSpace website](https://dspace.cvut.cz/handle/10467/114678)

## Attachments Structure
```
attachements.zip
│   README.md
└───docs/
└───rpms/
└───sources/
```

## License
Copyright 2024 CESNET z.s.p.o.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
