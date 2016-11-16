# Table of Content
- [Linux](#linux)
- [Network](#network)
- [Database](#database)
- [IAAS](#iaas)
- [Programming](#programming)
- [Version Control](#version-control)
- [System Design](#system-design)
- [System Performance](#system-performance)
- [Troubleshooting](#troubleshooting)
- [CI/CD](#ci/cd)
- [Containers](#containers)
- [Configuration Management](#configuration-management)
- [Virtualization technologies](#virtualization-technologies)

## Linux
- [Understanding the Linux kernel](http://shop.oreilly.com/product/9780596005658.do)
  - Introduction
  - Memory Addressing
  - Processes
  - Interrupts and Exceptions
  - Process Scheduling
  - Memory Management
  - Process Address Space
  - System Calls
  - Signals
  - The Virtual Filesystem (VFS)
  - I/O Architecture
  - Block Device Drivers
  - The Page Cache
  - Accessing Files
  - Page Frame Reclaiming
  - Process Communication
  - Program Execution
  - System Startup
- [Advanced Linux Programming](http://advancedlinuxprogramming.com/alp-folder/)
  - [Chapter 02 - Writing Good GNU/Linux Software](http://advancedlinuxprogramming.com/alp-folder/alp-ch02-writing-good-gnu-linux-software.pdf)
  - [Chapter 03 - Processes](http://advancedlinuxprogramming.com/alp-folder/alp-ch03-processes.pdf)
  - [Chapter 04 - Threads](http://advancedlinuxprogramming.com/alp-folder/alp-ch04-threads.pdf)
  - [Chapter 05 - Interprocess Communication](http://advancedlinuxprogramming.com/alp-folder/alp-ch05-ipc.pdf)
  - [Chapter 06 - Mastering Linux](http://advancedlinuxprogramming.com/alp-folder/alp-ch06-mastering-linux.pdf)
  - [Chapter 07 - The /proc File System](http://advancedlinuxprogramming.com/alp-folder/alp-ch07-proc-filesystem.pdf)
  - [Chapter 10 - Security](http://advancedlinuxprogramming.com/alp-folder/alp-ch10-security.pdf)
- [Memory Layout of C Program](http://cs-fundamentals.com/c-programming/memory-layout-of-c-program-code-data-segments.php)
- [Out of Memory](http://www.linuxdevcenter.com/pub/a/linux/2006/11/30/linux-out-of-memory.html)
- Filesystems
  - [Ext4](https://en.wikipedia.org/wiki/Ext4)
  - [XFS](https://en.wikipedia.org/wiki/XFS)
  - [Btrfs](https://en.wikipedia.org/wiki/Btrfs)
  - [ZFS](https://en.wikipedia.org/wiki/ZFS)
- Storage technologies
  - [SATA](https://en.wikipedia.org/wiki/Serial_ATA)
  - [SCSI](https://en.wikipedia.org/wiki/SCSI)
  - [Fiber Channel](https://en.wikipedia.org/wiki/Fibre_Channel)
  - [InfiniBand](https://en.wikipedia.org/wiki/InfiniBand)
- [RAID](http://www.storagecraft.com/blog/raid-performance/)
- [I/O Scheduler](http://www.admon.org/system-tuning/a-comparison-of-io-schedulers/)
- [CPU Scheduler](https://doc.opensuse.org/documentation/html/openSUSE_121/opensuse-tuning/cha.tuning.taskscheduler.html)
- Security
  - [SELinux](https://en.wikipedia.org/wiki/Security-Enhanced_Linux)
  - [grsecurity](https://en.wikipedia.org/wiki/Grsecurity) 

## Network
- Network layers 1 - 3
  - [ARP](https://en.wikipedia.org/wiki/Address_Resolution_Protocol)
  - [Ethernet](https://en.wikipedia.org/wiki/Ethernet)
  - [IPv4](https://en.wikipedia.org/wiki/IPv4)
  - [IPv6](https://en.wikipedia.org/wiki/IPv6)
  - [ICMP](https://en.wikipedia.org/wiki/https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol) and [Path MTU Discovery](https://en.wikipedia.org/wiki/Path_MTU_Discovery)
  - [Multicast](https://en.wikipedia.org/wiki/IP_multicast) and [IGMP](https://en.wikipedia.org/wiki/Internet_Group_Management_Protocol)
  - [IPsec](https://en.wikipedia.org/wiki/IPsec)
  - [MPLS](https://www.nanog.org/meetings/nanog49/presentations/Sunday/mpls-nanog49.pdf)
- [Routing protocols](https://en.wikipedia.org/wiki/Routing_protocol) and [AS](https://en.wikipedia.org/wiki/Autonomous_system_(Internet))
  - [OSPF](https://en.wikipedia.org/wiki/Open_Shortest_Path_First)
  - [RIP](https://en.wikipedia.org/wiki/Routing_Information_Protocol)
  - [EIGRP](https://en.wikipedia.org/wiki/Enhanced_Interior_Gateway_Routing_Protocol)
  - [BGP](https://en.wikipedia.org/wiki/Border_Gateway_Protocol)
- Network layer 4
  - [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
  - [UDP](https://en.wikipedia.org/wiki/User_Datagram_Protocol)
- Network layer 7
  - [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol), [HTTPS](https://en.wikipedia.org/wiki/HTTPS), [HSTS](https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security) and [HTTP/2](https://en.wikipedia.org/wiki/HTTP/2)
  - [Same-origin policy](https://en.wikipedia.org/wiki/Same-origin_policy) and [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing)
  - [SSL/TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security), [SNI](https://en.wikipedia.org/wiki/Server_Name_Indication) [Public key certificate](https://en.wikipedia.org/wiki/Public_key_certificate), [Certificate authority
](https://en.wikipedia.org/wiki/Certificate_authority), [Extended Validation Certificate](https://en.wikipedia.org/wiki/Extended_Validation_Certificate) and [Subject Alternative Name
](https://en.wikipedia.org/wiki/Subject_Alternative_Name)
  - [SSH](https://en.wikipedia.org/wiki/Secure_Shell)
  - [DNS](https://en.wikipedia.org/wiki/Domain_Name_System) and [DNSSEC](https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions)
  - [DHCP](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol)
  - [NTP](https://en.wikipedia.org/wiki/Network_Time_Protocol)
  - [SNMP](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol)
  - Email
    - [SMTP(S)](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol) and [Submission](https://en.wikipedia.org/wiki/Message_submission_agent)
    - [SASL](https://en.wikipedia.org/wiki/Simple_Authentication_and_Security_Layer) and [GSSAPI](https://docs.oracle.com/cd/E19683-01/816-1331/6m7oo9sn3/index.html)
    - [SPF](https://en.wikipedia.org/wiki/Sender_Policy_Framework)
    - [DKIM](https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail)
    - [DMARC](https://en.wikipedia.org/wiki/DMARC)
  - [LDAP](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol)
- [Load Balancing](https://en.wikipedia.org/wiki/Load_balancing_(computing))
  - [Apache mod_proxy_balancer](https://httpd.apache.org/docs/2.4/mod/mod_proxy_balancer.html)
  - [HAProxy](http://www.haproxy.org/#desc) 
- [Network caching](http://docwiki.cisco.com/wiki/Network_Caching_Technologies)
  - [Varnish](https://en.wikipedia.org/wiki/Varnish_(software)) 
- [CDN](https://en.wikipedia.org/wiki/Content_delivery_network)

## Database
- SQL
  - [Intro to SQL: Querying and managing data](https://www.khanacademy.org/computing/computer-programming/sql)
  - [PostgreSQL Exercises](https://pgexercises.com/)

## IAAS
- AWS
  - [Official documentation](https://aws.amazon.com/documentation/)
  - [The Open Guide to Amazon Web Services](https://github.com/open-guides/og-aws)

## Programming
- Bash
  - [Advanced Bash-Scripting Guide](http://tldp.org/LDP/abs/html/)
  - [Google Shell Style Guide](https://google.github.io/styleguide/shell.xml)
  - [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
- Python
  - [Official documentation](https://docs.python.org/3.6/#)
  - [Learning Python, 5th edition](http://learning-python.com/books/about-lp5e.html)
  - [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
  - [Common Gotchas](http://docs.python-guide.org/en/latest/writing/gotchas/)
  - [Testing](http://docs.python-guide.org/en/latest/writing/tests/)
- Go
  - [Official documentation](https://golang.org/doc/) 
  - [The Go Programming Language](http://www.gopl.io/)
- [Data structures and complexity](http://bigocheatsheet.com/) 
- [hackerrank.com](https://www.hackerrank.com)
  - [Python](https://www.hackerrank.com/domains/python/py-introduction)
  - [Bash](https://www.hackerrank.com/domains/shell/bash)
  - [Data structures](https://www.hackerrank.com/domains/data-structures/arrays)
  - [Algorithms](https://www.hackerrank.com/domains/algorithms/warmup)

## Version Control
- Git
  - [Atlassian tutorials](https://www.atlassian.com/git/tutorials/)
  - [Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows/) 

## System Design
- [System Design Interview](https://github.com/checkcheckzz/system-design-interview)
- [High Scalability](http://highscalability.com/)

## System Performance
- [Systems Performance: Enterprise and the Cloud](http://www.brendangregg.com/sysperfbook.html)
  - Introduction
  - Methodology
  - Operating Systems
  - Observability Tools
  - Applications
  - CPUs
  - Memory
  - File Systems
  - Disks
  - Network
  - Cloud Computing
  - Benchmarking
  - Case Study
  - Appendices

## Troubleshooting
- [Linux System Administrator/DevOps Interview Questions](https://github.com/chassing/linux-sysadmin-interview-questions)
- [Linux Performance Analysis in 60,000 Milliseconds](http://techblog.netflix.com/2015/11/linux-performance-analysis-in-60s.html)
- ["What happens when you type google.com into your browser's address box and press enter?"](https://github.com/alex/what-happens-when)

## CI/CD
- [Continuous Integration](http://www.martinfowler.com/articles/continuousIntegration.html)
- Test frameworks
  - [Inspec](http://inspec.io/)
  - [KitchenCI](http://kitchen.ci/)

## Containers
- [cgroups](https://www.kernel.org/doc/Documentation/cgroup-v2.txt) and [namespaces](http://man7.org/linux/man-pages/man7/namespaces.7.html)
- [Docker](https://docs.docker.com/)
- [rkt](https://coreos.com/rkt/)
- Framerworks
  - [Kubernetes](http://kubernetes.io/docs/)
  - [Mesosphere](https://mesosphere.com/product/)
- [Docker init problems](https://engineeringblog.yelp.com/2016/01/dumb-init-an-init-for-docker.html)

## Configuration Management
- [Configuration management](https://en.wikipedia.org/wiki/Configuration_management)
- Pick one from
  - [Ansible](http://docs.ansible.com/)
  - [SaltStack](https://docs.saltstack.com/en/latest/)
  - [Chef](https://docs.chef.io/)
  - [Puppet](https://docs.puppet.com/)

## Virtualization technologies
- [Hypervisor](https://en.wikipedia.org/wiki/Hypervisor)
  - [KVM](https://en.wikipedia.org/wiki/Kernel-based_Virtual_Machine)
  - [Xen](https://en.wikipedia.org/wiki/Xen)

## RAW content to be sorted
• Memory management
  • Paging
  • Page faults
    • Determine the location of the data on disk
    • Obtain an empty page frame in RAM to use as a container for the data. → if not, eviction through LRU
    • Load the requested data into the available page frame.
    • Update the page table to refer to the new page frame.
    • Return control to the program, transparently retrying the instruction that caused the page fault.
* Security
