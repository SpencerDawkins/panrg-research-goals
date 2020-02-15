---
title: "Path Aware Networking: Research Goals"
abbrev: What Not To Do
docname: draft-dawkins-panrg-research-goals-latest
date: 
category: info
submissiontype: IRTF

ipr: trust200902
area: IRTF
workgroup: PANRG
keyword: Networking
keyword: Aware
keyword: Path
keyword: PAN

stand_alone: yes
pi: 
  toc: yes
  sortrefs: yes
  symrefs: yes
  compact: yes
  comments: yes

author:
  -
    ins: S. Dawkins
    name: Spencer Dawkins
    organization: Tencent America 
    email: spencerdawkins.ietf@gmail.com
    role: editor

informative:

  RFC0792:
  
  RFC0793:
  
  RFC1016:

  RFC1190:
  
  RFC1633:
  
  RFC1809:
  
  RFC1819:
  
  RFC1887:

  RFC2001:
  
  RFC2205: 
  
  RFC2210:
  
  RFC2211:
  
  RFC2212:
  
  RFC2215:
  
  RFC2475:

  RFC3168:

  RFC3697:
  
  RFC4094: 

  RFC4443:
  
  RFC4782:
  
  RFC5082:

  RFC5218:
  
  RFC5533:
  
  RFC5575:

  RFC5681:
  
  RFC5971:
 
  RFC5973:
 
  RFC5974:
 
  RFC5981:
  
  RFC5974:
  
  RFC6294:
  
  RFC6398:

  RFC6437:
  
  RFC6438:
  
  RFC6633:
  
  RFC6928:

  RFC7305:
  
  RFC7418:
  
  RFC8085:
  
  RFC8170:

  Colossal-Cave:
    target: https://en.wikipedia.org/wiki/Colossal_Cave_Adventure
    title: "Wikipedia Page for Colossal Cave Adventure"
    date: Retrieved January 2019

  draft-arkko-arch-internet-threat-model:
    title: "Changes in the Internet Threat Model" 
    target: https://datatracker.ietf.org/doc/draft-arkko-arch-internet-threat-model/
    author: 
      ins: J. Arkko 
      name: Jari Arkko

  draft-farrell-etm:
    title: "We're gonna need a bigger threat model" 
    target: https://datatracker.ietf.org/doc/draft-farrell-etm/
    author: 
      ins: S. Farrell 
      name: Stephen Farrell 

  IEN-119: 
    title: "ST - A Proposed Internet Stream Protocol" 
    target: https://www.rfc-editor.org/ien/ien119.txt
    author: 
      ins: J. Forgie 
      name: James W. Forgie
    date: September 1979

  GREASE: 
    title: "Long-term Viability of Protocol Extension Mechanisms" 
    target: https://tools.ietf.org/html/draft-iab-use-it-or-lose-it-00
    author: 
      ins: M. Thomson 
      name: Martin Thomson
    date: July 2019
    
  ITAT:
    target: https://www.iab.org/activities/workshops/itat/
    title: "IAB Workshop on Internet Technology Adoption and Transition (ITAT)"
    date: December 2013

  MP-TCP:
    target: https://datatracker.ietf.org/wg/mptcp/about/
    title: "Multipath TCP Working Group Home Page"

  model-t:
    target: https://www.iab.org/mailman/listinfo/model-t
    title: "Model-t -- Discussions of changes in Internet deployment patterns and their impact on the Internet threat model"

  NANOG-35:
    target: https://www.nanog.org/meetings/nanog35/agenda
    title: "North American Network Operators Group NANOG-35 Agenda"
    date: October 2005

  NSIS-CHARTER-2001:
    target: https://datatracker.ietf.org/doc/charter-ietf-nsis/
    title: "Next Steps In Signaling Working Group Charter"
    date: March 2011

  PANRG-99:
    target: https://datatracker.ietf.org/meeting/99/sessions/panrg
    title: "Path Aware Networking Research Group - IETF-99"
    date: July 2017

  PANRG-103-Min:
    target: https://datatracker.ietf.org/doc/minutes-103-panrg/
    title: "Path Aware Networking Research Group - IETF-103 Minutes"
    date: November 2018 

  PANRG-105-Min:
    target: https://datatracker.ietf.org/doc/minutes-105-panrg/
    title: "Path Aware Networking Research Group - IETF-105 Minutes"
    date: July 2019

  PANRG-106-Min:
    target: https://datatracker.ietf.org/doc/minutes-106-panrg/
    title: "Path Aware Networking Research Group - IETF-106 Minutes"
    date: November 2019

  PATH-Decade:
    target: https://datatracker.ietf.org/doc/slides-99-panrg-a-decade-of-path-awareness/
    title: "A Decade of Path Awareness"
    author:
      name: Olivier Bonaventure
      ins: O. Bonaventure
    date: July 2017

  PANRG:
    target: https://irtf.org/panrg
    title: "Path Aware Networking Research Group (Home Page)"

  PathProp: 
    title: "A Vocabulary of Path Properties" 
    target: https://tools.ietf.org/html/draft-enghardt-panrg-path-properties-03
    author: 
      - 
        name: Theresa Enghardt
        ins: T. Enghardt
      - 
        name: Cyrill Kraehenbuehl
        ins: C. Kraehenbuehl   
    date: November 2019

  QS-SAT:
    target: https://dl.acm.org/citation.cfm?id=3160304.3160305
    title: "Using Quick-Start to enhance TCP-friendly rate control performance in bidirectional satellite networks"
    author: 
      - 
        name: Raffaello Secchi
        ins: R. Secchi
      - 
        name: Arjuna Sathiaseelan
        ins: A. Sathiaseelan        
      - 
        name: Francesco Potortì
        ins: F. Potortì     
      - 
        name: Alberto Gotta
        ins: A. Gotta   
      - 
        name: Gorry Fairhurst
        ins: G. Fairhurst
    date: 2009
        
  QUIC-WG:
    target: https://datatracker.ietf.org/wg/quic/about/
    title: "QUIC Working Group Home Page"
  
  SAAG-105-Min:
    target: https://datatracker.ietf.org/meeting/105/materials/minutes-105-saag-00
    title: "Security Area Open Meeting - IETF-105 Minutes"
    date: July 2019

  SAF07: 
    author: 
      - 
        name: Pasi Sarolahti
        ins: P. Sarolahti
      - 
        name: Mark Allman
        ins: M. Allman
      - 
        name: Sally Floyd
        ins: S. Floyd
    title: "Determining an appropriate sending rate over an underutilized network path"
    seriesinfo:
      "Computer Networking": "Volume 51, Number 7"
    date: May 2007

  Sch11:
    author: 
      name: M. Scharf
      ins: M.Scharf
    title: "Fast Startup Internet Congestion Control for Broadband Interactive Applications"
    seriesinfo: 
      "Ph.D.": "Thesis, University of Stuttgart"
    date: April 2011
 
  Shim6-35:
    author:
      - 
        name: David Meyer
        ins: D. Meyer
      - 
        name: Geoff Huston
        ins: G. Huston
      -
        name: Jason Schiller
        ins: J. Schiller
      -
        name: Vijay Gill
        ins: V. Gill
    title: "IAB IPv6 Multihoming Panel at NANOG 35"
    seriesinfo:
      "NANOG": "North American Network Operator Group"
    date: October 2005
    target: https://www.youtube.com/watch?v=ji6Y_rYHAQs

  TAPS-WG:
    target: https://datatracker.ietf.org/wg/taps/about/
    title: "Transport Services Working Group Home Page"
 
  TRIGTRAN-55:
    target: https://www.ietf.org/proceedings/55/239.htm 
    title: "Triggers for Transport BOF at IETF 55"
    date: July 2003
 
  TRIGTRAN-56:
    target: https://www.ietf.org/proceedings/56/251.htm 
    title: "Triggers for Transport BOF at IETF 56"
    date: November 2003
 
--- abstract

At the first meeting of the Path Aware Networking Research Group, the research group agreed to catalog and analyze past efforts to develop and deploy  Path Aware techniques, most of which were unsuccessful or at most partially successful, in order to extract insights and lessons for path-aware networking researchers.

This document contains that catalog and analysis.

--- middle
# Introduction

At the first meeting of the Path Aware Networking Research Group {{PANRG}}, at IETF 99 {{PANRG-99}}, Oliver Bonaventure led a discussion of "A Decade of Path Awareness" {{PATH-Decade}}, on attempts, which were mostly unsuccessful for a variety of reasons, to exploit Path Aware techniques and achieve a variety of goals over the past decade. At the end of that discussion, two things were abundantly clear. 

- The Internet community has accumulated considerable experience with many Path Aware techniques over a long period of time, and

- Although some path aware techniques have been deployed (for example, Differentiated Services, or DiffServ {{RFC2475}}), most of these techniques haven't seen widespread adoption and deplyment. Even "successful" techniques like DiffServ can face obstacles that prevents wider usage. The reasons for non-adoption and limited adoption and deployment are many, and are worthy of study.

The meta-lessons from that experience were

- Path aware networking has been more Research than Engineering, so establishing an IRTF Research Group for Path Aware Networking is the right thing to do {{RFC7418}}.

- Analyzing a catalog of past experience to learn the reasons for non-adoption would be a great first step for the Research Group.

Allison Mankin, as IRTF Chair, officially chartered the Path Aware Networking Research Group in July, 2018. 

This document contains the analysis performed by that research group ({{LessonsLearned}}), based on that catalog ({{Contributions}}). 

# Security Considerations

This document describes Path Aware techniques that were not adopted and widely deployed on the Internet, so it doesn't affect the security of the Internet. 

If this document meets its goals, we may develop new techniques for Path Aware Networking that would affect the security of the Internet, but security considerations for those techniques will be described in the corresponding RFCs that specify them.

# IANA Considerations

This document makes no requests of IANA.

# Acknowledgments

Your name could go here ...

--- back

