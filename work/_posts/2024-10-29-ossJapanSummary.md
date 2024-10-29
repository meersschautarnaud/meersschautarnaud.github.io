---
layout: post
title:  "Open Source Summit and AI Dev Japan"
subtitle: "A summary of 2 interesting days"
author: Arnaud
categories: conference japan linux-foundation
background: '/img/posts/work/ossJapanSummary/background.jpg'
---

# Open Source Summit and AI Dev Japan

The past two days, I attended the Open Source Summit in Japan. Here’s a bit about what the event covers and my experience there.

This event focuses on the open-source projects within the Linux Foundation, including AI projects and innovative solutions. Its primary focus is on open-source developers, sharing new projects, and the future of existing initiatives. Events like these give developers from various companies a chance to connect and exchange ideas, it’s also a way for companies to showcase their work using available open-source code.

## What is the Linux Foundation?

The Linux Foundation is a nonprofit organisation dedicated to supporting development on Linux and fostering open-source projects. Its initiatives include projects like the Linux Kernel, OpenJS, RISC-V, the Confidential Computing Consortium, and the Cloud Native Computing Foundation (CNCF), among others. The projects are not only about open software, but open hardware, standards, and data as well.

The Cloud Native Computing Foundation or CNCF is part of the Linux Foundation as mentioned and is focused on building and maintaining cloud native solutions. They have a huge list of projects and members and are hosting events all over the world like KubeCon.

The Open Source summit in Japan is a lot smaller than KubeCon which I attended last year in Amsterdam, but I’ve experienced the same vibe and community feeling. People gather from all over the world to share ideas and projects they are working on to help improve things while sharing the code is wonderful to see.

Some of the topics during the summit:
- Automotive Grade Linux - AGL (Really interesting topic and curious what the evolution will be)
- The benefits of open-source software
- The open-source mentality within companies and Japan in general
- Open-source AI tools and models
- Updates in the Linux Kernel
- Security concerns with open-source projects

## Sessions spotlight

The first session I want to put in the spotlight it’s the one that’s brought by Jeff Shaw. Titled "Running Containers on a Resource Constrained Embedded Device" it addressed the challenges of running applications on limited hardware. Nowadays, during development, I feel like we take the computing power and resources that are available for granted. Meaning that we are focused on the development part and not on the amount of CPU and memory the application will use or how big the docker image and container will be.

During the session, Jeff demonstrated how they managed to get a container with an application running on a device with a single-core processor and 256MB of storage and memory. Besides needing a small image, they also faced the challenge of installing a container runtime on the device. To address this, they used [Linux Containers (LXC)](https://linuxcontainers.org/lxc/introduction/). LXC allows mounting host directories, making the container behave much like the host. This approach ensures that the base software on the device remains read-only, maintaining system security, while user processes can still run within the container. I hope this makes sense!

Another session that stood out to me was Tal Folkman’s presentation "The Dark Side of AI: The Hidden Risks in Open-Source AI Models". She not only covered the potential for malicious code within open-source AI models but also discussed risks related to malicious code embedded in packages and dependencies. Tal shared numerous examples and provided tips on preventing the use of compromised packages. The key takeaway was the importance of thoroughly checking any package before integrating them into your development environment, though this can be challenging at times. I’ll definitely be following the [Checkmarx page on Medium](https://zero.checkmarx.com/latest) to stay updated on these topics.

A lot of the talks will normally end up on the [Youtube channel](https://www.youtube.com/@LinuxfoundationOrg/videos) of the Linux Foundation. So if you are interested in one of these topics, be sure to check that out!

## Conclusion

Overall, I liked the event and I’m happy that I was able to attend, thanks to Codit. I’ve met new people and got a glimpse of the open-source community within the Linux Foundation and its importance.

You may be wondering: Did you travel to Japan just to attend this session? The answer is… yes! Just kidding—I traveled to Japan for my holiday and was excited to see the Linux Foundation hosting an event, so I couldn’t resist attending. You can read more about my travels in Japan [here](/travel/index.html).§

<img class="img-fluid" src="/img/posts/work/ossJapanSummary/image1.jpg">
<img class="img-fluid" src="/img/posts/work/ossJapanSummary/image2.jpg">
<img class="img-fluid" src="/img/posts/work/ossJapanSummary/image3.jpg">