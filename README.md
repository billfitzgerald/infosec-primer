# Information Security Primer

The Information Security Primer for Evaluating Educational Software is a toolkit for people looking to learn more about evaluating information security practices of educational software. While the primary audience of this document is people interested in running information security tests, our secondary audience includes people who will not be running tests, but who want to learn more about what "information security" means.

As the title states, this document is a primer, not a comprehensive guide. We intend for this document to grow and evolve over time. We also want to give people the tools to learn information security testing safely.

This guide was developed as part of the [Common Sense District Privacy Evaluation Initiative](https://www.graphite.org/privacy). If you work at a school district and would like to join the consortium of districts working in the United States to help streamline the process of evaluating privacy policies for EdTech apps, you can [learn more and sign up here](https://www.graphite.org/privacy/about/districts).

## Contents

* A. [Introduction](introduction.md)
* B. [Responsible Disclosure](responsible.md)
* C. [Setting up the Testing Toolkit](getting_started.md)
  * C1 [The Toolkit - A Summary](getting_started.md#h.toolkit-summary)
  * C2 [Installing and Using Firebug to Observe HTTP and HTTPS Traffic](getting_started.md#h.toolkit-firebug)
  * C3 [Installing and Using Advanced Cookie Manager](getting_started.md#h.toolkit-adv-cookie-manager)
  * C4 [Installing and Using ZAP Proxy to Observe HTTP and HTTPS Traffic](getting_started.md#h.toolkit-zap-proxy)
    * C4.1 [Installation and Initial Setup](getting_started.md#h.toolkit-zap-proxy-install)
    * C4.2 [Basic setup, browser and proxy on same computer](getting_started.md#h.toolkit-zap-proxy-same-box)
    * C4.3 [Mobile device (or browser) on different computer than the proxy](getting_started.md#h.toolkit-zap-proxy-different-box)
    * C4.4 [Installing proxy SSL certificate to browser and mobile devices](getting_started.md#h.toolkit-zap-proxy-ssl-cert)
    * C4.5 [Observing websockets traffic using ZAP Proxy](getting_started.md#h.toolkit-zap-proxy-websockets)
* D. [Preparing Your Browser](browser_prep.md)
  * D1 Set Firefox Home Page
  * D2 Clear recent history 
  * D3 about:permissions
* E. [Testing Scenarios](testing_scenarios.md)
  * E1 Sensitive information in URLs
  * E2. Encryption and Transport Layer Security
  * E3 TLS for email sent by an application to users
  * E4 Caching and history storage of pages with sensitive information
  * E5 Authentication token and cookie handling
  * E6 Password handling
  * E7 Username enumeration
  * E8 Observation of websockets traffic
  * E9 Information leakage
  * E10 API authentication checks
  * E11 Mobile application testing
* F. [Glossary](glossary.md)

## Author Credits

Tony Portfeld and Jim Siegl are the primary authors of this text.

Bill Fitzgerald, Girard Kelly, and Jeff Graham provided editing support and testing.

Jenny Pritchett copy edited the initial version.

## Contact Information

Please contact Bill Fitzgerald (bfitzgerald@commonsense.org) with any questions or comments on this handbook.

We will also respond - as time permits - to issues in the issue queue.

## Get Involved

We will be modifying this document over time to keep the tests current, and to add additional tests. If you would like to contribute, please open an issue in the queue and/or make a pull request. 

## Licensing

This is released under a Creative Commons Attribution Non-Commercial Share-Alike 4.0 License: https://creativecommons.org/licenses/by-nc-sa/4.0/
