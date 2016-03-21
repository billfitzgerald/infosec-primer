# Information Security Primer for Evaluating Educational Software

The **Information Security Primer for Evaluating Educational Software** is a toolkit for people looking to learn more about evaluating the information security practices of educational software. While the primary audience for this document is people interested in running information security tests, our secondary audience includes people who will not be running tests but who want to learn more about what "information security" means.

As the title states, this document is a primer, not a comprehensive guide. We intend for this document to grow and evolve over time. Future versions will include more advanced testing scenarios, but for the initial version, we wanted to provide resources to allow people to learn how to do security reviews safely.

This guide was developed as part of the [Common Sense District Privacy Evaluation Initiative](https://www.graphite.org/privacy). If you work at a school district and would like to join the consortium of districts working in the United States to help streamline the process of evaluating privacy policies for edtech apps, you can [learn more and sign up here](https://www.graphite.org/privacy/about/districts).

## Contents

* A. [Introduction: Who Should Read This](introduction.md)
* B. [Responsible Disclosure](responsible.md)
* C. [Setting Up the Testing Toolkit](getting_started.md)
  * C1 [The Toolkit: A Summary](getting_started.md#h.toolkit-summary)
  * C2 [Installing and Using Firebug to Observe HTTP and HTTPS Traffic](getting_started.md#h.toolkit-firebug)
  * C3 [Installing and Using an Advanced Cookie Manager](getting_started.md#h.toolkit-adv-cookie-manager)
  * C4 [Installing and Using a ZAP Proxy to Observe HTTP and HTTPS Traffic](getting_started.md#h.toolkit-zap-proxy)
    * C4.1 [Installation and Initial Setup](getting_started.md#h.toolkit-zap-proxy-install)
    * C4.2 [Basic Setup, Browser and Proxy on Same Computer](getting_started.md#h.toolkit-zap-proxy-same-box)
    * C4.3 [Mobile Device (or Browser) on Different Computer from the Proxy](getting_started.md#h.toolkit-zap-proxy-different-box)
    * C4.4 [Installing Proxy SSL Certificate to Browser and Mobile Devices](getting_started.md#h.toolkit-zap-proxy-ssl-cert)
    * C4.5 [Observing WebSockets Traffic Using ZAP Proxy](getting_started.md#h.toolkit-zap-proxy-websockets)
* D. [Preparing Your Browser](browser_prep.md)
  * D1 [Set Firefox Home Page](browser_prep.md#h.browser-homepage)
  * D2 [Clear History](browser_prep.md#h.browser-history)
  * D3 [Accept Cookies](browser_prep.md#h.browser-cookies)
* E. [Testing Scenarios](testing_scenarios.md)
  * E1 [Sensitive Information in URLs](testing_scenarios.md#h.testing-url-info)
  * E2 [Encryption and Transport Layer Security](testing_scenarios.md#h.testing-tls)
  * E3 [TLS for Email Sent by an Application to Users](testing_scenarios.md#h.testing-email-tls)
  * E4 [Caching and History Storage of Pages with Sensitive Information](testing_scenarios.md#h.testing-cache)
  * E5 [Authentication Token and Cookie Handling](testing_scenarios.md#testing-auth-token)
  * E6 [Password Handling](testing_scenarios.md#h.testing-password)
  * E7 [Username Enumeration](testing_scenarios.md#h.testing-username)
  * E8 [Observation of WebSockets Traffic](testing_scenarios.md#h.testing-websockets)
  * E9 [Information Leakage](testing_scenarios.md#h.testing-leakage)
  * E10 [API Authentication Checks](testing_scenarios.md#h.testing-api)
  * E11 [Mobile Application Testing](testing_scenarios.md#h.testing-mobile)
* F. [Glossary](glossary.md)

## Author Credits

Tony Porterfield, Jim Siegl, and Bill Fitzgerald are the primary authors of this text.

Girard Kelly, Jeff Graham, and Omar Khan provided editing support and testing.

Jenny Pritchett copyedited the initial version.

## Contact Information

Please contact Bill Fitzgerald (bfitzgerald@commonsense.org) with any questions or comments on this handbook.

We will also respond -- as time permits -- to issues in the issue queue.

## Get Involved

We will be modifying this document over time to keep the tests current and to add tests. If you would like to contribute, please open an issue in the queue and/or make a pull request. 

## Licensing

This is released under a Creative Commons Attribution Non-Commercial Share-Alike 4.0 License: https://creativecommons.org/licenses/by-nc-sa/4.0/

Visit the [Licensing and Attribution](licensing_attribution.md) page for complete details.
