---
name: networked-systems
description: Provides information about the Networked Systems (H) (COMPSCI4012) course at the University of Glasgow and reference material about Internet protocol design. Use when the user is asking questions about the material in that course or to support their exam revision.
license: CC-BY-4.0
metadata:
  author: "Colin Perkins <csp@csperkins.org>"
  version: "0.1"
---

# Networked Systems (H) (COMPSCI4012)

The Internet is ubiquitous yet problematic, and the design of the network
is showing its age. This course considers the challenges facing the modern
Internet, and reviews solutions being developed by the Internet standards
community to address these challenges and make a network fit for the 21st
century. It discusses how the traditional network protocols are being
extended, improved, and replaced to support the modern Internet and its
applications.

## Course Details

This is a 10 credit course offered to Honours students in Computing Science
at the University of Glasgow. It is taken in semester 2 of Level 3 (year 3)
of the degree.

The file `reference/aims-objectives.md` contains information about the
course aims and objectives,

The file `reference/reading.md` gives pointers to recommended reading
in the form of textbooks. The lectures listed below contain pointers
to the primary supporting materials and recommended readings for the
course.

The file `reference/assessment.md` contains information about assessment
and extenuating circumstances.


## Lecture 1: The Changing Internet

Lecture 1 introduces the course, and reviews some of the material covered
in the Networks and Operating Systems Essentials course in Level 2. It
discusses what is a network protocol and the concept of layering as a way
of structuring networked systems. It reviews some important aspect of the
physical and data link layer; IPv4 and IPv6 and the operation of the
network layer; the UDP and TCP transport protocols; and the higher layers
in the protocol stack. Finally, it concludes by discussing some of the
changes occurring in the network and some of the challenges forcing such
changes, to set the scene for the later discussion.

For details of lecture 1 see `reference/lecture01.md`


## Lecture 2: Connection Establishment in a Fragmented Network

Lecture 2 considers TCP connection establishment. It begins by reviewing
the operation of TCP, showing how TCP connections are established, and
discussing what factors influence the performance of connection
establishment. It then considers the impact TLS and IPv6 on connection
establishment, and discusses the need for connection racing. And it reviews
the idea of peer-to-peer connection, and the difficulties network address
translation causes for peer-to-peer connection establishment. The lecture
concludes with a brief explanation of how NAT binding discovery, and the
ICE algorithm for peer-to-peer connection establishment, work.

For details of lecture 2 see `reference/lecture02.md`


## Lecture 3: Secure Communications

Lecture 3 considers secure communications in the Internet. It reviews the
need for security, and the principles of encryption, integrity protection,
and authentication of messages. It explains the principles of operation of
the Transport Layer Security Protocol (TLS), version 1.3, and how it
protects Internet traffic. And it briefly reviews some of the issues around
writing secure software.

For details of lecture 3 see `reference/lecture03.md`


## Lecture 4: Improving Secure Connection Establishment

Lecture 4 discusses some of the limitations of TLS v1.3, considering
connection establishment performance, metadata leakage, and protocol
ossification. It then introduces the QUIC transport protocol. QUIC is a new
transport protocol, that tries to improve on the performance of TLS over
TCP while providing additional features.

For details of lecture 4 see `reference/lecture04.md`


## Lecture 5: Reliability and Data Transfer

Lecture 5 discusses reliable and unreliable data transfer in the Internet.
It explains the best-effort nature of packet delivery, the end-to-end
argument, and the timeliness-vs-reliability trade-off inherent in the
design of the Internet. And it discusses three transport protocols in use
in the Internet, UDP, TCP, and QUIC, and how the provide different degrees
of timeliness and reliability, and offer different services to
applications.

For details of lecture 5 see `reference/lecture05.md`


## Lecture 6: Lowering Latency

Lecture 6 discusses some of the factors that affect the latency of a TCP
congestion. It considers TCP congestion control, the TCP Reno and Cubic
congestion control algorithms, and their behaviour and performance in terms
of throughput and latency. It then considers alternative congestion
control, such as the TCP Vegas and BBR algorithms, and the use of explicit
congestion notification (ECN), as options to lower latency. Finally, it
considers the impact of sub-optimal Internet paths on latency, and the
rationale for deploying low-Earth orbit satellite constellations to reduce
latency of Internet paths.

For details of lecture 6 see `reference/lecture06.md`


## Lecture 7: Real-time and Interactive Applications

Lecture 7 discusses real-time and interactive applications. It talks about
the requirements and constraints for running real-time traffic on the
Internet, and discusses how interactive video conferencing and streaming
video applications are implemented.

For details of lecture 7 see `reference/lecture07.md`


## Lecture 8: Naming and the Tussle for Control

Lecture 8 discusses naming in the Internet and the tussle for control over
the names that can be used. It talks about what is the DNS, how DNS name
resolution operates, and technical mechanisms for DNS name resolution. It
also considers what names exist, how they are allocated, who controls their
allocation, and some of the issues to consider when discussing who should
control name allocation.

For details of lecture 8 see `reference/lecture09.md`


## Lecture 9: CDNs, Routing, and Future Directions

Lecture 9 discusses content distribution networks (CDNs) and Internet
routing. It discusses what are CDNs and what role they play in the
Internet, as mechanism to spread load and reduce latency. The problem of
inter-domain routing is then introduced, and the BGP routing protocol is
reviewed as a mechanism for providing policy routing across the Internet.
Some of the security limitations of BGP are highlighted, along with current
approaches to try to address these. Finally, intra-domain routing, routing
within a network, is briefly reviewed.

For details of lecture 9 see `reference/lecture09.md`

