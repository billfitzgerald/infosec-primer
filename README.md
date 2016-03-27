# Information Security Primer for Evaluating Educational Software

The **Information Security Primer for Evaluating Educational Software** is a toolkit for people looking to learn more about evaluating the information security practices of educational software. While the primary audience for this document is people interested in running information security tests, our secondary audience includes people who will not be running tests but who want to learn more about what "information security" means.

As the title states, this document is a primer, not a comprehensive guide. We intend for this document to grow and evolve over time. Future versions will include more advanced testing scenarios, but for the initial version, we wanted to provide resources to allow people to learn how to do security reviews safely.

This guide was developed as part of the [Common Sense District Privacy Evaluation Initiative](https://www.graphite.org/privacy). If you work at a school district and would like to join the consortium of districts working in the United States to help streamline the process of evaluating privacy policies for edtech apps, you can [learn more and sign up here](https://www.graphite.org/privacy/about/districts).

## Contents

* A. [Introduction: Who Should Read This](introduction.md#a-introduction-who-should-read-this)
* B. [Responsible Disclosure](responsible.md#b-responsible-disclosure)
* C. [Setting Up the Testing Toolkit](getting_started.md#c-setting-up-the-testing-toolkit)
  * C1 [The Toolkit: A Summary](getting_started.md#c1-the-toolkit-a-summary)
  * C2 [Installing and Using Firebug to Observe HTTP and HTTPS Traffic](getting_started.md#c2-installing-and-using-firebug-to-observe-http-and-https-traffic)
  * C3 [Installing and Using an Advanced Cookie Manager](getting_started.md#c3-installing-and-using-an-advanced-cookie-manager)
  * C4 [Installing and Using ZAP Proxy to Observe HTTP and HTTPS Traffic](getting_started.md#c4-installing-and-using-zap-proxy-to-observe-http-and-https-traffic)
    * C4.1 [Installation and Initial Setup of OWASP ZAP](getting_started.md#c41-installation-and-initial-setup-of-owasp-zap)
    * C4.2 [Basic Setup, Browser and Proxy on Same Computer](getting_started.md#c42-basic-setup-browser-and-proxy-on-same-computer)
    * C4.3 [Setup for Testing Mobile Devices and/or Web Browsers on a Different Computer from the Proxy](getting_started.md#c43-setup-for-testing-mobile-devices-andor-web-browsers-on-a-different-computer-from-the-proxy)
    * C4.4 [Installing Proxy SSL Certificate on Browser and Mobile Devices](getting_started.md#c44-installing-proxy-ssl-certificate-on-browser-and-mobile-devices)
    * C4.5 [Observing WebSockets Traffic Using ZAP Proxy](getting_started.md#c45-observing-websockets-traffic-using-zap-proxy)
* D. [Preparing Firefox for Testing](browser_prep.md#d-preparing-firefox-for-testing)
  * D1 [Set Firefox Home Page](browser_prep.md#d1-set-firefox-home-page)
  * D2 [Clear History](browser_prep.md#d2-clear-history)
  * D3 [Verify That Cookies Are Allowed and Do Not Track Is Off](browser_prep.md#d3-verify-that-cookies-are-allowed-and-do-not-track-is-off)
* E. [Testing Scenarios and Procedures](testing_scenarios.md#e-testing-scenarios-and-procedures)
  * E1 [Sensitive Information in URLs](testing_scenarios.md#e1-sensitive-information-in-urls)
  * E2 [Encryption and Transport Layer Security](testing_scenarios.md#e2-encryption-and-transport-layer-security)
  * E3 [TLS for Email Sent by an Application to Users](testing_scenarios.md#e3-tls-for-email-sent-by-an-application-to-users)
  * E4 [Caching and History Storage of Pages with Sensitive Information](testing_scenarios.md#e4-caching-and-history-storage-of-pages-with-sensitive-information)
  * E5 [Authentication Token and Cookie Handling](testing_scenarios.md#e5-authentication-token-and-cookie-handling)
  * E6 [Password Handling](testing_scenarios.md#e6-password-handling)
  * E7 [Username Enumeration](testing_scenarios.md#e7-username-enumeration)
  * E8 [Observation of WebSockets Traffic](testing_scenarios.md#e8-observation-of-websockets-traffic)
  * E9 [Information Leakage](testing_scenarios.md#e9-information-leakage)
  * E10 [API Authentication Checks](testing_scenarios.md#e10-api-authentication-checks)
  * E11 [Mobile Application Testing](testing_scenarios.md#e11-mobile-application-testing)
* F. [Glossary](glossary.md#f-glossary)

## Author Credits

Tony Porterfield, Jim Siegl, and Bill Fitzgerald are the primary authors of this text.

Girard Kelly, Jeff Graham, and Omar Khan provided editing support and testing.

Jenny Pritchett copyedited the initial version.

## Contact Information

Please contact Bill Fitzgerald (bfitzgerald@commonsense.org) with any questions or comments on this primer.

We will also respond -- as time permits -- to issues in the issue queue.

## Get Involved

We will be modifying this document over time to keep the tests current and to add tests. If you would like to contribute, please open an issue in the queue and/or make a pull request. 

## Licensing

This is released under a Creative Commons Attribution Non-Commercial Share-Alike 4.0 License: https://creativecommons.org/licenses/by-nc-sa/4.0/

Visit the [Licensing and Attribution](licensing_attribution.md) page for complete details.
