---
name: "Project Librimesh Piranha, new release."
desc: "This project consists of the development of a new release from Piranha for the new version of Libremesh based on OpenWRT 22."
collaborating_projects:
- Coolab
- LibreMesh
developers_involved:
- San
- Hiure
- Tania
- Luandro
difficulty: medium
status: open
initiatives:
- GSoC 2024
issues:
- https://github.com/libremesh/lime-packages/issues/942 
- https://github.com/libremesh/lime-packages/issues/936
- https://github.com/libremesh/lime-packages/issues/886
- https://github.com/libremesh/lime-packages/issues/327
- https://github.com/libremesh/lime-packages/issues/261
- https://github.com/libremesh/lime-packages/issues/76

size: 175 hours # choose between 90 hours, 175 hours and 350 hours
markdown: libremeshpiranianewrelease
mentors:
- name: public name of mentor 1
  contact:
    github: hiurequeiroz # provide at least one contact option
    email: hiure@riseup.net
    other_chat_options:
    - link to matrix or similar
requirements:
- "Analyzing and coding"
- "Lua"
- "javascript"
tags:
- Libremesh
- Pirania
---

The publication of the  [New Pirania API](https://github.com/libremesh/lime-packages/pull/893), the open captive portal application for Libremesh, unleashed the potential for several new applications based on the platform.
Many communities already make use of it, but many more could adopt it as a very important tool for the collection of funds, for the payment of the provider and sometimes even for people who work.
Anyone can manage the sistem through the [Pirania UI](https://github.com/libremesh/lime-app/pull/329).
Each router has access to the Captive Portal system,  making it a distributed solution, very useful for communities with different approaches to collectivity. Pirania has diferent options of governance, meaning that each community can understand the best use that it can make with the system and still propose new use cases.
In order to make it more complete it is important to raise the different ideas that have already been [raised by the community](https://github.com/libremesh/lime-packages/issues/76).
Pirania is unfortunately not included, in the latest versions of lime-packages (libremesh repository tool),  mainly because the basis of pirania's operation is the iptbles rules contained in ./usr/bin/captive-portal. As iptables ends up creating a very large file, the new version of libremesh decided to migrate from iptables to nftables. 
This and other changes need to be made to fit pirania into a new release.


#### Milestones

##### GSOC COMMUNITY BONDING

* Understanding open issues about pirania.
* Survey of all the ideas from the community that have not yet been contemplated about pirania.
* Understand with the community of the Libremesh in which point is the LimeApp, to planning the integration of the piranha with the new LimeApp.
* Understand the integration of the piranha with the Shared-State and to review the points that are open in this sense.

##### GSOC MIDTERM

* Create a clear and feasible plan of actions to be carried out within the indicated timeframe.
* Develop a user prototype within the new verion Libremesh.
* Test this solution with the community test of the Librimesh
* Documentation.

##### GSOC FINAL

* Review everything and present it to the Libremesh community, opening the platform for more contributions.
* Documentation

