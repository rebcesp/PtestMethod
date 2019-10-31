.. Ptest Method documentation master file, created by
   sphinx-quickstart on Fri Jul 13 13:04:20 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Rebcesp documentation!
========================================

This Repo will be my knowledge database about Pentesting skills. It has been inspired by https://bitvijays.github.io And some of the content will be the same as a starting point.

Always keep in mind when you have a problem just launch a search over internet about it, 99 % of the time the comunity already sollved this issue.

#####################
The Essentials Series
#####################

The Essentials Series covers the essential concepts/ skills for somebody who wants to enter the field of CyberSecurity.

- :doc:`CyberSecurity in an Enterprise <LFF-ESS-P0A-CyberSecurityEnterprise>` : IT Technical challenges faced by a company during their transformation from a start-up of two people growing to Micro, Small, Medium-sized, larger size company and their solutions.
- :doc:`Linux Basics <LFF-ESS-P0B-LinuxEssentials>` : Essential linux commands and concepts required in the Infosec field.

.. toctree::
   :maxdepth: 2
   :caption: The Essentials

   LFF-ESS-P0A-CyberSecurityEnterprise
   LFF-ESS-P0B-LinuxEssentials


#############################
Infrastructure Pentest Series
#############################

The Infrastructure Pentest Series cover all the phases of Infrastructure Pentest as described by
`The Penetration Testing Execution Standard <http://www.pentest-standard.org/>`_.

- :doc:`Intelligence Gathering <LFF-IPS-P1-IntelligenceGathering>` : Technical steps to perform during the information gathering phase of an organization and figuring out the attack-surface area.
- :doc:`Vulnerability Analysis <LFF-IPS-P2-VulnerabilityAnalysis>` : Exploring different services running on different ports of a machine by utilizing metasploit-fu, nmap or other tools.
- :doc:`Exploitation <LFF-IPS-P3-Exploitation>`                    : Enumeration methods that can be used after compromising a domain user credentials and Remote code execution methods after compromising administrative credentials.
- :doc:`Post Exploitation <LFF-IPS-P4-PostExploitation>`           : Different methods to gather credentials after getting an administrative remote shell. Also, performing post-exploitation to leave high-impact to C-Level executives is also covered in this section.
- :doc:`Reporting <LFF-IPS-P5-Reporting>`                          : Open-source ways to automate report writing after a successfull Pentest.
- :doc:`Configuration Review <LFF-IPS-P6-ConfigurationReview>`     : Methods to perform configuration review for the switches, routers, firewall and endpoint devices.


.. toctree::
   :maxdepth: 2
   :caption: Pentest Stages

   LFF-IPS-P1-IntelligenceGathering
   LFF-IPS-P2-VulnerabilityAnalysis
   LFF-IPS-P3-Exploitation
   LFF-IPS-P4-PostExploitation
   LFF-IPS-P5-Reporting
   LFF-IPS-P6-ConfigurationReview
   LFFWirelessPentesting


#############################
Hardening Series
#############################

  The Hardening Series cover all the procedures needed to be more secure.

- :doc:`Securing Debian <LFFSecuringDebiang>` : Technical steps to harden Debian systems.


.. toctree::
   :maxdepth: 2
   :caption: Hardening

   LFFSecuringDebian


#############################
Metasploit Documentation
#############################

Here you will find the documentation of some tools.

- :doc:`Metasploit Fundamentals <MetasploitFundamentals>` : How to use Metasploit. Forked from metasploit unlished.



.. toctree::
   :maxdepth: 2
   :caption: Metasploit Fundamentals

   MetasploitFundamentals


#############################
Other Tools
#############################


.. toctree::
   :maxdepth: 2
   :caption: Other Tools

   pupy
   cme

#####################
Obligatory Disclaimer
#####################

This blog is purely intended for educational purposes. We do not want anyone to use this information (or any information on this blog) to hack into computers where they do not have permission for or do other illegal things. Therefore we don't want to be held responsible for the acts of other people who took parts of this document and used it for illegal purposes. If you don’t agree, we kindly ask you to leave this website.



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
