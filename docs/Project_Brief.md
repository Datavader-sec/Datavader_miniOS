# Project Brief - Datavader minOS
**Author:** Michael J C Royle Prock-Ferrand
**Environment:** Parrot OS
**Repository:** [Datavader_miniOS](https://github.com/Datavader-sec/Datavader_miniOS)
**Start Date:** 2025-11-07

Objective:
"This project explores how core operating-system concepts like process managment, memory handling, file permissions, and user authentication work together. By simulating these systems in Python I hope to deepen my understanding of how attacks exploit OS mechanisms and how defenses are built."

Constraints:
Implemented entirely in Python 3 on my Parrot OS Laptop
No direct hardware interaction, kernel modules or real device drivers
Focus on conceptusl accuracy, clarity and documentation
All features must include at least one documented abuse case and mitigation 

Success Criteria:
Demonstrate working simulations of process scheduling, memory allocation, VFS Permissions, and user authentication
Include a threat-model document and at least one logged "attack - detection - mitigation" scenario
Maintain 100% commit-to-push sync with GitHub and a weekly learning-jounal entry
Produce a README that allows anyone to clone and run the demo without assistance

Core Pillars:
Sheduler & Process Model - Simulate CPU time-sharing and fairness policies
Memory Managment - model paging, fragmentation, and allocation
Virtual File System & Permissions - enforce user/group access
Authentication & Shell - Implement users, hashing, and an interactive CLI.
Audit Logging & Security Monitoring - detect and report misuse
Concurrency & IPC Simulation - cooperative multitasking and message queues

Learning Outcomes:
Strengthen low-level systems reasoning using a high-level language
Practice threat modeling, least privilege, and audit-driven security 
Improve Git discipline, documentaion habits, and self directed learning

Cybersecurity Relevance:
"By simulating OS internals I hope to better understand vulnerabilities such as race conditions, privilege escalation, and memory misuse. These insights directly translate to security analysis, blue-team forensics, and ethical-hacking context."

Milestone Overview:
Week 0 - Lab setup and planning
Week 1 - Process Scheduling Simulation
Week 2 - Memory Model
week 3 - VFS & Permissions
Week 4 - Auth + Shell + Audit
Week 5 - Concurrency & IPC
Week 6 - Hardening and Demo Day
