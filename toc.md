# Table of Contents

[A. Introduction: Who Should Read This?](#h.introduction)

[B. Responsible Disclosure](#h.responsible-disclosure)

[C. Setting Up the Testing Toolkit](#h.getting-started)

[C1 The Toolkit: A Summary](#h.toolkit)

[C2 Installing and Using Firebug to Observe HTTP and HTTPS Traffic](#h.zet3vk1pkrjs)

[C3 Installing and Using an Advanced Cookie Manager](#h.ykszsnquvupn)

[C4 Installing and Using a ZAP Proxy to Observe HTTP and HTTPS Traffic](#h.mwfpqjd3xlon)

[C4.1 Installation and Initial Setup of OWASP ZAP](#h.7fymp72b8omo)

[C4.2 Basic Setup, Browser and Proxy on Same Computer](#h.wjqpd39gw4cq)

[C4.2.1 ZAP Local Proxy Address](#h.vbuo171i6w5z)

[C4.2.2 Browser Proxy Address](#h.8kovtfgyr4u)

[C4.3 Setup for Testing Mobile Devices and/or Web Browsers on a Different Computer from the Proxy](#h.y5dvombqyalq)

[C4.3.1 Find the Network Address of the Proxy Computer](#h.lpyknvs2zi4w)

[C4.3.1.1 Windows:](#h.7sr83bitb0bi)

[C4.3.1.2 Apple OS X:](#h.94gc7w9tdrj7)

[C4.3.1.3 Linux/Unix:](#h.p2a5n871tlz8)

[C4.3.2 In ZAP Proxy: Change "Local proxy" Address](#h.bfzt3oeiw3qh)

[C4.3.3 In Firefox: Change the "Manual proxy configuration" Address](#h.5rw78s2srk55)

[C4.3.4 iOS Device Setup](#h.ysk2ity9xmk2)

[C4.3.5 Android Device Proxy Setup](#h.8jfxtoyy0jab)

[C4.4 Installing Proxy SSL Certificate on Browser and Mobile Devices](#h.36skx6gn1zj3)

[C4.4.1 Save Proxy Certificate to File](#h.siot5sn7ei32)

[C4.4.2 Import Proxy Certificate to Browser](#h.ks9tnnahqy09)

[C4.4.3 Import Proxy Certificate to iOS Device](#h.a4b21qxt3trn)

[C4.4.3.1 Transfer Proxy Certificate File to the Device](#h.m56l827otmz2)

[C4.4.3.2 Install Proxy Certificate File on the Device](#h.wnsj3vacbwja)

[C4.4.4 Import Proxy Certificate to Android Device](#h.z2734tzgu0dd)

[C4.4.4.1 Transfer Proxy Certificate File to the Device](#h.m5dfy2vt2a5c)

[C4.4.4.2 Install Proxy Certificate File to the Device](#h.tr59wlfhqrl3)

[C4.5 Observing WebSockets Traffic Using a ZAP Proxy](#h.w3vwwdi4lrrz)

[D. Preparing Firefox for Testing](#h.ntcxwqbe2jar)

[D1 Set Firefox Home Page](#h.d9g9h0yzj6wu)

[D2 Clear History](#h.9fq5l852406x)

[D3 Verify That Cookies Are Allowed and Do Not Track Is Off](#h.g8chgdd0ceta)

[E. Testing Scenarios and Procedures](#h.tmw1mwtzn0nf)

[E1 Sensitive Information in URLs](#h.x0w34x37470m)

[E1.1 Summary](#h.hwm0291uwy92)

[E1.2 Exploitability and impact](#h.4js8e57p6ig)

[E1.3 Setup and tests](#h.49829xsxl7k2)

[E2 Encryption and Transport Layer Security](#h.fq9rsjwj4yq4)

[E2.1 Summary](#h.iwkpldsr7060)

[E2.2 Exploitability and Impact](#h.1juqpryjxlfz)

[E2.3 Setup and Tests](#h.o7vew9ih5ppt)

[E2.3.1 Tools](#h.vbqip5ovcxrs)

[E2.3.2 Tests](#h.hhk99qwpsg4)

[E2.3.2.1 Check Whether the Login Form or Page Is Served Using HTTPS (Web Applications)](#h.ums2y3iaiipo)

[E2.3.2.2 Check Whether Login Credentials Are Posted Using HTTPS (Web Applications and Mobile Apps)](#h.8h2oa44hb1gb)

[E2.3.2.3 Check Whether Authenticated Sessions Continue to Use HTTPS After Login (Both Web Applications and Mobile Apps)](#h.3ynwconnsi5c)

[E2.3.2.4 Check Whether the Application Uses Strict-Transport-Security Headers (Web Applications)](#h.5ieyh23nijsl)

[E2.3.2.5 Check the Rigor of the Service's SSL Configuration](#h.oa9sl89xof6l)

[E3 TLS for Email Sent by an Application to Users](#h.25vsmkjogdt8)

[E3.1 Summary](#h.4ps217mycyrw)

[E3.2 Exploitability and Impact](#h.5niv7akow7s7)

[E3.3 Setup and Tests](#h.j1roabe90h4r)

[E3.3.1 Email Header Inspection](#h.8py9kcjqa0cc)

[E3.3.2 Google's Safer Email Transparency Report](#h.9wjy7cj5r8zr)

[E3.3.3 Checktls.com](#h.fwm7cp7yqcyi)

[E4 Caching and History Storage of Pages with Sensitive Information](#h.ad79s4u8zvhc)

[E4.1 Summary](#h.s6l7mchrhbia)

[E4.2 Exploitability and Impact](#h.mh1a5lue9obq)

[E4.3 Setup and Tests](#h.h3wu53hfc3t5)

[E4.3.1 Overview](#h.vwc3l336fxrh)

[E4.3.2 Header Response Inspection](#h.7ps9ful4q6r)

[E4.3.3 Browser-Based History Test](#h.i8oxvlmno7bx)

[E4.3.4 Browser Cache Inspection](#h.8yja7zn6i6t7)

[E4.3.5 Recommended Test Steps](#h.loc23z8234lk)

[E5 Authentication Token and Cookie Handling](#h.jgbj7m6ef85r)

[E5.1 Summary](#h.gzsbf5qtrhuw)

[E5.2 Exploitability and Impact](#h.go1005ch8716)

[E5.3 Setup and Tests](#h.hfasjjvfytwr)

[E5.3.1 How to Identify Authentication Cookies](#h.jjxwgd1wcntq)

[E5.3.2 Flags That Protect Authentication Cookies](#h.lrlgliorty2o)

[E5.3.3 Invalidation of Authentication Cookies at Logout](#h.lxaguwf157fz)

[E5.3.4 Logout Links](#h.hz9cbgh9f8dp)

[E6 Password Handling](#h.o0yfi4ju8qc4)

[E6.1 Summary](#h.p0qyv29uhye)

[E6.2 Exploitability and Impact](#h.bycob2ftdmmd)

[E6.3 Setup and Tests](#h.wpt7namartcy)

[E6.3.1 Encryption and Transport Layer Security](#h.4m74lanyrk6d)

[E6.3.2 Recovering Lost Passwords](#h.9xo3mg78sh5h)

[E7 Username Enumeration](#h.9dzibh2zsmhu)

[E7.1 Summary](#h.mflcozt3veb3)

[E7.2 Exploitability and Impact](#h.12n9dlp4hivh)

[E7.3 Setup and Tests](#h.roihhrjluacf)

[E7.3.1 User Login](#h.pqjlaodys6pv)

[E7.3.2 Password Recovery](#h.ft0vj9gi6k2z)

[E8 Observation of WebSockets Traffic](#h.84zlnvdl3nqp)

[E8.1 Summary](#h.vapinpbwcs48)

[E8.2 Exploitability and Impact](#h.61n72nw4mfkk)

[E8.3 Setup and Tests](#h.8fjtmad0hqb3)

[E8.3.1 Check Contents of WebSockets Traffic for Sensitive Information](#h.3060boikmptv)

[E8.3.2 Check Whether the WebSockets Connection Is Encrypted](#h.pgk5io8rnrmf)

[E9 Information Leakage](#h.krhp5dinabwe)

[E9.1 Summary](#h.608106vxg5v2)

[E9.2 Exploitability and Impact](#h.5akdv6pporg0)

[E9.3 Setup and Tests](#h.qqzeo9fxpqfu)

[E9.3.1 Examples of Information Leakage](#h.tffq0u5vsua6)

[E9.3.1.1 Email Leakage](#h.21x8s0z82hry)

[E9.3.1.2 Leaking Names and Emails](#h.56iz4o3483a7)

[E9.3.1.3 Leaking Student Information](#h.94oxul5fhdmt)

[E9.3.1.4 Leaking Full Name, School, State, and User ID](#h.rp7yummv8hnm)

[E9.3.1.5 Leaking Username, Activity Information, Name, and Teacher ID](#h.e2qh0r4gqtn7)

[E10 API Authentication Checks](#h.rnno329obb2d)

[E10.1 Summary](#h.aghuyfymsb8f)

[E10.2 Exploitability and Impact](#h.bge6s9opq4oq)

[E10.3 Setup and Tests](#h.oayw74esjvsl)

[E11 Mobile Application Testing](#h.i96tfugoo84q)

[E11.1 Summary](#h.8uim1fdsxml)

[E11.2 Exploitability and Impact](#h.jr8jg8hlmmg)

[E11.3 Setup and Testing](#h.kcl39z7wypqk)

[E11.3.1 Browser-Based Tests That Remain Relevant for Mobile Apps](#h.c41szg1g16ya)

[E11.3.2 SSL Certificate Validation (SSL Certificate Spoofing) Tests That Are Specific to Mobile Applications](#h.r03vdv9ggz1i)

[F. Glossary](#h.glossary)
