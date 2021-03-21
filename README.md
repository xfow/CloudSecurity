# Cloud Security
A repository containing materials used to contain information and methodologies for Cloud based penetration testing engagements.

# Introduction

With enterprises moving to Cloud based technology on an increasing basis, the requirements to test the security of configurations is becoming increasingly prevelant. Organisations are moving to cloud services as they offer a number of benefits, including decreasing the amount of expenditure on physical servers, adding redundancy in the event of catastrophic failures and to lower the technical abilities required to maintain services.

Insecure cloud configurations may be an inticing attack vector for malicious actors. Open SW buckets for example may contain sensitive information that can be used for social engineering attacks, or credentials for key pieces of infrastructure. The three most common cloud platforms today are as follows:

* Microsoft Azure
* Amazon Web Services
* Google Cloud

As such, these platforms are the basis of this training document. Each section will contain useful tools, CTF examples, known exploits and any tools specifically used for that platform. CIS Compliance benchmarks will also be contained as they may provide useful insight into best practises.

# ScoutSuite

Scoutsuite is an automated vulnerability assessment scanner written in Python and used to audit a number of cloud technologies. The project has been created by NCC and licensing is per their rules. Such automation is always useful to give a brief oversight of areas that may be vulnerable. It should be treated like Nessus, great to get an overview but make sure you are checking the output is correct, and it also may not catch everything you are looking for. The link to the git repository is below.

https://github.com/nccgroup/ScoutSuite

Scoutsuite outputs a HTML file to classify all vulnerabilities found that can be browsed at your leisure. This training document will not cover usage as there is adequate documentation on the repository.

# CIS Compliance Benchmarks

The Center of Internet Security (CIS) provide benchmarks for pretty much any operating system or technology commonly used. They are the standard most cyber security organsiations perform build reviews too, and although often overly restrictive, provide an excellent insight into the mindset required to secure a technology. All of their benchmarks are available for free on their website, listed below:

https://www.cisecurity.org/cis-benchmarks/

Although automated tools may be used to perform these benchmarks, it is always highly recommended to read the document itself, in order to try to understand rationales behind the standards they set. If you are new to a technology, they are a great starting place to refer to.

# Outro

This document is a live document, meaning that contributions will be made as and when I am available to make such changes. It is an individual project and although I am open to input, there are currently no plans to add addition contributors to the repository. If you have suggested alterations I am more than happy to hear such ideas and credit you as appropriate.
