---
title: "Report from the IAB workshop on Management Techniques in Encrypted Networks (M-TEN)"
abbrev: "M-TEN workshop report"
category: info

docname: draft-iab-m-ten-workshop-latest
submissiontype: IAB
number:
date:
consensus: true
v: 3
# area: AREA
# workgroup: WG Working Group
keyword:
 - encryption
 - network management
venue:
#  group: WG
#  type: Working Group
#  mail: WG@example.com
#  arch: https://example.com/WG
  github: "intarchboard/m-ten-workshop-public"
  latest: "https://intarchboard.github.io/m-ten-workshop-public/draft-iab-m-ten-workshop.html"

author:
 -
    fullname: Your Name Here
    organization: Your Organization Here
    email: "cmorgan@amsl.com"
 -
    fullname: Mallory Knodel
    organization: Center for Democracy & Technology
    email: "mknodel@cdt.org"

normative:

informative:


--- abstract

The “Management Techniques in Encrypted Networks (M-TEN)” workshop was convened by the Internet Architecture Board (IAB) from 17 October 2022 to 19 October 2022 as a three-day online meeting. The workshop was organized in three parts to discuss ways to improve network management techniques in support of even broader adoption of encryption on the Internet. This report summarizes the workshop's discussion and identifies topics that warrant future work and consideration.

Note that this document is a report on the proceedings of the workshop. The views and positions documented in this report are those of the workshop participants and do not necessarily reflect IAB views and positions.

--- middle

# Introduction

User privacy and security are constantly being improved by increasingly strong and more widely deployed encryption. This workshop aims to discuss ways to improve network management techniques in support of even broader adoption of encryption on the Internet.

Network management techniques need to evolve to work effectively and reliably in the presence of ubiquitous traffic encryption and support techniques that enhance user privacy. In an all-encrypted network, it is not viable to rely on unencrypted metadata for network monitoring and security functions, troubleshooting devices, and passive traffic measurements. New approaches are needed to track network behaviors, e.g., by directly cooperating with endpoints and applications, increasing use of in-band telemetry, increasing use of active measurement approaches, and privacy-preserving inference techniques.

The aim of this IAB online workshop from October 17-19, 2022, has been to provide a platform to explore the interaction between network management and traffic encryption and initiate new work on collaborative approaches that promote security and user privacy while supporting operational requirements. As such the workshop addressed the following questions:

* What are actionable network management requirements?
* Who is willing to work on collaborative solutions?
* What are the starting points for collaborative solutions?

# Workshop Scope and Discussion

The workshop was organized across three, all-group discussion slots, one per day. The following topic areas were identified and the programme committee organized paper submissions into three main themes for each of the three discussion slots. During each discussion, those papers were presented sequentially with open discussion held at the end of each day.

## “Where we are” - Requirements and Passive Observations

The first day of the workshop agenda focused on the existing state of the relationship between network management and encrypted traffic from various angles. Presentations ranged from discussing classifiers using machine-learning to recognize traffic, to advanced techniques for evading traffic analysis, to user privacy considerations.

## “Where we want to go” - Collaboration Principles

The second day of the workshop agenda focused on the emerging techniques for analysing, managing or monitoring encrypted traffic. Presentations ranged from discussing advanced classification and identification, including machine-learning techniques, for the purposes of manging network flows, monitoring or monetising usage.

## “How we get there” - Collaboration Use cases


--- back

# Position Papers {#positionpapers}

Interested participants were openly invited to submit position papers on the workshop topics, including Internet-Drafts, relevant academic papers, or short abstracts explaining their interest. The papers below constitute the inputs that were considered relevant for workshop attendees and that focused the discussions themselves. The program committee grouped the papers by theme as such.

## Motivations and principles

Richard Barnes. “What’s In It For Me? Revisiting the reasons people collaborate.”

Iain R. Learmonth, Gurshabad Grover, Mallory Knodel. “Guidelines for Performing Safe Measurement on the Internet.” (Additional rationale)

Qin Wu, Jun Wu, Qiufang Ma. “Network Management of Encrypted Traffic: Detect it don’t decrypt it.”

## Classification and identification of encrypted traffic

Luca Deri. “nDPI Research Proposal.”

Wes Hardaker. “Network Flow Management by Probability.”

Xi Jiang, Shinan Liu, Saloua Naama, Francesco Bronzino, Paul Schmitt, Nick Feamster. “Towards Designing Robust and Efficient Classifiers for Encrypted Traffic in the Modern Internet.”

Yupeng Lei, Jun Wu, Xudong Sun, Liang Zhang, Qin Wu. “Encrypted Traffic Classification Through Deep Learning.”

## Ideas for collaboration and coordination between devices and networks

Michael Collins. “Improving Network Monitoring Through Contracts.”

Paul Grubbs, Arasu Arun, Ye Zhang, Joseph Bonneau, Michael Walfish. “Zero-Knowledge Middleboxes.”

Mirja Kühlewind, Magnus Westerlund, Zaheduzzaman Sarker, Marcus Ihlar. “Relying on Relays: The future of secure communication.”

Tommy Pauly, Richard Barnes. “Red Rover: A collaborative approach to content filtering.”

Michael Welzl. “The Sidecar: ‘Opting in’ to PEP Functions.“

## Other background material

Pedro Casas. “Monitoring User-Perceived Quality in an Encrypted Internet – AI to the Rescue.”

Nalini Elkins, Mike Ackermann, Mohit P. Tahiliani, Dhruv Dhody, Prof. Tommaso Pecorella. “Performance Monitoring in Encrypted Networks: PDMv2.”

# Workshop participants {#participants}

The workshop participants were Cindy Morgan, Colin Perkins, Cullen Jennings, Deborah Brungard, Dhruv Dhody, Eric Vyncke, Georg Carle, Ivan Nardi, Jari Arkko, Jason Livingood, Jiankang Yao, Karen O'Donoghue, Keith Winstein, Lars Eggert, Laurent Vanbever, Luca Deri, Mallory Knodel, Marcus Ihlar, Matteo, Michael Ackermann, Michael Collins, Michael Richardson, Michael Welzl, Mike Ackermann, Mirja Kühlewind, Mohit P. Tahiliani, Nalini Elkins, Patrick Tarpey, paul grubbs, Pedro Casas, Qin Wu, Qiufang, Richard Barnes, Rob Wilton, Russ White, Saloua Naama, Shinan Liu, Srinivas C, Toerless Eckert, Tommy Pauly, Wes Hardaker, Xi Chase Jiang, Zaheduzzaman Sarker, Zhenbin Li.

# Program Committee

The workshop program committee members were Wes Hardaker (IAB, USC/ISI), Mallory Knodel (IAB, Center for Democracy and Technology), Mirja Kühlewind (IAB, Ericsson), Tommy Pauly (IAB, Apple), Russ White (IAB, Juniper), Qin Wu (IAB, Huawei).

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
