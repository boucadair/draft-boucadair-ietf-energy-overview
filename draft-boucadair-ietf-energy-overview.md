---
title: "TODO - Your title"
abbrev: "TODO - Abbreviation"
category: info

docname: draft-boucadair-ietf-energy-overview-latest
submissiontype: IETF  # also: "independent", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: AREA
workgroup: WG Working Group
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: WG
  type: Working Group
  mail: WG@example.com
  arch: https://example.com/WG
  github: USER/REPO
  latest: https://example.com/LATEST

author:
 -
    fullname: Your Name Here
    organization: Your Organization Here
    email: your.email@example.com

normative:

informative:


--- abstract

TODO Abstract


--- middle

# Introduction

# EMAN

* {{?RFC7603}}
* {{?RFC7577}}
* {{?RFC7460}}
* {{?RFC7461}}
* {{?RFC7326}}
* {{?RFC6988}}
* {{?RFC6933}}

# NMRG

{{?I-D.irtf-nmrg-green-ps}}:
: Reducing humankind's environmental footprint and making technology
   more sustainable are among the biggest challenges of our age.
   Networks play an important part in this challenge.  On one hand, they
   enable applications that help to reduce this footprint.  On the other
   hand, they contribute to this footprint themselves in no
   insignificant way.  Methods to make networking technology itself
   "greener" and to manage and operate networks in ways that reduces
   their environmental footprint without impacting their utility
   therefore need to be explored.  This document outlines a
   corresponding set of opportunities, along with associated research
   challenges, for networking technology in general and management
   technology in particular to become "greener", i.e., more sustainable,
   with reduced greenhouse gas emissions and less negative impact on the
   environment. 


# OPSAWG

{{?I-D.opsawg-poweff}}:
: The Power and Energy Efficiency Telemetry Specification seeks to
   address this inconsistency by providing a single reference for these
   important activities, aiming to create value through insights.



# MISC

{{?RFC8352}}:
: This document describes the challenges for energy-efficient protocol
   operation on constrained devices and the current practices used to
   overcome those challenges.  It summarizes the main link-layer
   techniques used for energy-efficient networking, and it highlights
   the impact of such techniques on the upper-layer protocols so that
   they can together achieve an energy-efficient behavior.  The document
   also provides an overview of energy-efficient mechanisms available at
   each layer of the IETF protocol suite specified for constrained-node
   networks.

{{?I-D.cx-green-metrics}}:
: This document explains the need for network instrumentation that allows to assess the power consumption, energy efficiency, and carbon footprint associated with a network, its equipment, and the services that are provided over it. It also suggests a set of related metrics that, when provided visibility into, can help to optimize a network's energy efficiency and "greenness".

{{?I-D.li-ivy-power}}:
: Network sustainability is a key issue facing the industry.  Networks
   consume significant amounts of power at a time when the cost of power
   is rising and sensitivity about sustainability is very high.  As an
   industry, we need to find ways to optimize the power efficiency of
   our networks both at a micro and macro level.  We have observed that
   traffic levels fluctuate and when traffic ebbs there is much more
   capacity than is needed.  Powering off portions of network elements
   could save a significant amount of power, but to scale and be
   practical, this must be automated. This document proposes a YANG model.

 {{?I-D.pignataro-eimpact-icmp}}:
 : This document defines a data structure that can be appended to
   selected ICMP messages.  The ICMP extension defined herein can be
   used to gain visibility on environmental impact information on the
   Internet by providing per-hop (i.e., per topological network node)
   power metrics and other current or future sustainability metrics.
   This will contribute to achieving an objective mentioned in the IAB
   E-Impact workshop.
: The techniques presented are useful not only in a transactional
   setting (e.g., a user-issued traceroute or a ping request), but also
   in a scheduled automated setting where they may be run periodically
   in a mesh across an administrative domain to map out environmental-
   impact metrics.

{{?I-D.gudumasu-avtcore-decoder-energy-reduction}}:
: This document describes an RTCP feedback message format for the second type of green metadata defined by the ISO/IEC International Standard 23001-11, known as Energy Efficient Media Consumption (Green metadata), developed by the ISO/IEC JTC 1/SC 29/WG 3 MPEG System. The RTCP feedback messages specified in this specification is compatible and complimentary with the other draft on green metadata and enables receivers to provide feedback to the senders for decoder power reduction and thus allows feedback-based energy efficient mechanisms to be implemented. The feedback message has broad applicability in real-time video communication services.

{{?I-D.ramos-schc-zero-energy-devices}}:
: This document describes the use of SCHC for very constraint devices.
   The use of SCHC will bring connectivity to devices with restrained
   use of battery and long delays.

 {{?I-D.petra-path-energy-api}}:
 : This document describes an API to query a network regarding its
   Energy Traffic Ratio for a given path.

{{?I-D.cprjgf-bmwg-powerbench}}:
: This document defines a mechanism to measure, report, and
   compare power usage of different networking devices and under
   different network configurations and conditions.

{{?I-D.cparsk-eimpact-sustainability-considerations}}:
: This document defines a set of sustainability-related terms to be
   used while describing and evaluating environmental impacts of
   Internet technologies.  It also describes several of the design
   tradeoffs for trying to optimize for sustainability along with the
   other common networking metrics such as performance and availability.

# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
