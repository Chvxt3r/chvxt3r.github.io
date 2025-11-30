---
title: PNPT - My Thoughts and Experience
date: 2025-02-15 16:00:00 +/-0000
categories: [Training,Certifications,Hacking,Pentesting]
tags: [tcm security,pnpt,certifications,exams,cybersec,training]     # TAG names should always be lowercase
description: In Cicada we attack a Domain Controller starting with abusing SMB null authentication.
image: "https://certifications.tcm-sec.com/wp-content/uploads/2024/08/PNPT.webp"
---

## My Motivations
  As you may have read on my about page, I'm a 25-year systems administrator who was told by multiple employers I was salary capped unless I specialized. Always having had an interest
in security, I decided to specialize in security. I'm expert level at networking and AD, about average at Linux, and probably below average at security up until this point.

## The Training
  The PNPT training material is broken out into 5 courses:
  - OSINT
  - Practical Ethical Hacking
  - Windows Privilege Escalation
  - Linux Privilege Escalation
  - External Pentest Playbook

  I'm going to go at these in the order I would take them in, knowing what I know now about the exam.

  First, I'd go with Practical Ethical Hacking. This course breaks down common vulnerability the TCM crew has found in their penetration testing business and how to exploit them. The material is comprehensive, although does rely on metasploit quite a bit. Doing this over again, I would work on manually exploiting these vulnerabilities, rather than using metasploit. Beyond that, the training is of excellent quality and will have you enumerating and breaking into machines in now time. There are several labs, and while there is no mechanism in the course to verify you have completed these labs, I would highly suggest you do them. As an experienced sysadmin, I can tell you the domain build is very accurate, and I have seen engineer's build actual domains in the same manner. I would encourage you to invest in a home lab, which will allow you to spin this lab up on your own and experiment and get familiar with the various exploits, and perhaps experiment with different, perhaps newer, tools to accomplish the same objectives the course is trying to teach. It's refreshing that the course is very methodology-based vs. tool-based.  I don't think TCM cares what tool you use as long as you arrive at the same result.

  After PEH, I would tack the External Pentesters Playbook. This is a comprehensive course regarding steps from initial contact to final report regarding perforrming a pentest. You'll learn about checklists used, how to prepare a report, what common findings look like, how to interpret Rules of Engagement, etc. It's a comprehensive guide to conducting a pentest in a professional manner and staying professional throughout. During this course you'll touch on subjects already covered in PEH and get a taste of subjects covered in OSINT. 

  Next I'd tackle OSINT. This course was very comprehensive and explores Open-Source intelligent from a pentesting perspective. This course was very informative about the tools and techniques used to gather intelligence on a target, and how to use that intelligence to successfully reach your objective. There are several case studies on reviewing publicly available materials for locating and identifying your targets. You'll learn how to gather users, sniff out hints and clues from images, explore social media, and tons of other valuable information that can be gathered publicly.

  Windows Privilege Escalation would be my next step. This course will expand on techniques covered in PEH and OSINT. It will help you search for passwords, identify kernel exploits, and increase your privileges on a windows computer through means other than a username and password. You'll learn about several techniques for impersonating users, dumping passwords, system enumeration, exploring automated tools, pivoting, and several other techniques used to escalate priviliges.

  Finally I'd do Linux Privilege Escalation. This is pretty much the same as Windows PrivEsc, except geared for Linux. Obviously the methods for linux are going to be different from windows, but many of the principles will be the same. Enumeration, sudo, suid, and scheduled tasks abuse are all covered. 

  Overall, I found all of the courses to be fairly comprehensive in teams of teaching you what you need for real world pentest, and for the exam.

## The Exam
  On to the exam. In all fairness, I had to take the exam twice. I failed the first exam because I drastically reduced my time through my own errors. I couldn't seem to get a command right, and then I accidentally deleted all my notes while trying to back them up. I made the 2nd attempt almost immediately after the first attempt, and was able to pass. I feel like if you spent 4 hours a day for a month going through the courses, practicing on the labs, and studying, you would be able knock this out on the first try.

**Exam Format**
  The exam gives you 7 days to find a way in and completely compromise an active directory domain. You have 5 days with the lab environment and then another 2 days to write your report. II feel like you should be able to do the report as you go along. I used sysreptor to document and create the report as I went along. I find this method makes it very easy to gather the documentation necessary for the report. It also provides a brief break from trying to figure stuff out. You can find my report templates [here]().

## The Debrief

