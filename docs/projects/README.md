---
pageClass: projects-page
---

# Work

<ProjectCard image="/projects/kuaishou.png" hideBorder=true>

**Kuaishou Technology, SDE Intern, Search Engine Group(C++)**

- Built prefix tree(Trie) service, the search engine request the new service through gRpc/ProtoBuf to obtain the suggestion results of entries, improved service restart time from 20 minutes to several minutes

- The new prefix tree service cluster could take 200k QPS (100 nodes) with 99.99% availability.

- Built Docker service, combined with Hadoop, to optimize the update time of search suggestion entries;

- Add features to search results, provide search functionality to new services from other department

- Built Grafana server monitoring dashboard for search engine service

</ProjectCard>

## Projects

<ProjectCard image="/projects/1.jpg" hideBorder=true>

**WALL-E-Garbage-classification-robot**

Built a WALL-E-Garbage-classification-robot on Arduino and RaspberryPi.

- Built a WALL-E-object-classification-robot on Arduino and Raspberry Pi that detects and classifies objects and automatically navigates

- Engineered an intelligent mobile platform and designed a web panel in Bottle (Python web framework) and Bootstrap that includes camera streaming, autopilot, and manual control

- Established communication between the computer and Raspberry Pi with MQTT

[[Link](https://isteps.comp.nus.edu.sg/event/sws-y2-19/module/Cluster3/project/9)]

</ProjectCard>

<ProjectCard image="/projects/distribution.png" hideBorder=true>

**Distributed Transactions System**

- Implemented timestamp based concurrency control, transactions that read and write to distributed objects while ensuring full ACID properties. A separate coordinator server for coordinating the transactions.

- Used RMI (remote method invocation) and the Pyro framework to allow our clients to access methods and object a remote node has.

</ProjectCard>

<ProjectCard image="/projects/pacman.png" hideBorder=true>

**The Pac-Man project**

- Applied depth-first search, breadth-first search, and A\* search on Pac-Man to find the shortest path

- Implemented model-based and model-free reinforcement learning to help Pac-Man run away from ghosts

</ProjectCard>

<ProjectCard image="/projects/reminisce.png" hideBorder=true>

**Reminiscence: A Website of Memory**

- Built a website that allows users to log in and post about their daily lives using Django & Bootstrap

- Won First Prize in the Wuhan University Web Design Competition

</ProjectCard>

<style lang="stylus">

.projects-page
  background-color #fafbfc

</style>
