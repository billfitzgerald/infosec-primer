# F. Glossary

Many of the definitions below are taken from the OWASP glossary ([https://www.owasp.org/index.php/Category:Glossary](https://www.owasp.org/index.php/Category:Glossary)), and the NIST Glossary of Key Information Security Terms, NISTIR 7298, revision 2 ([http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)). Definitions taken from these documents contain links to the source document in the title of the glossary term.

**Authentication Cookie** see **Session Token**

**API**

Application Programming Interface. For web and mobile applications, this is a network-facing interface that the application can use to request user-specific information from the application's servers.

[**Certificate**](https://www.owasp.org/index.php/Category:Glossary%23C)

A data object that binds information about a person or some other entity to a public key. The binding is generally done using a digital signature from a trusted third party (a certification authority).

[**Certification Authority**](https://www.owasp.org/index.php/Category:Glossary%23C)

An entity that manages digital certificates — i.e., issues and revokes.

[**Ciphertext**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Data in its encrypted form.

[**Cookies**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Data exchanged between an HTTP server and a browser (a client of the server) to store state information on the client side and retrieve it later for server use.

[**Cross-site scripting**](https://www.owasp.org/index.php/Category:Glossary%23C)

A class of problems resulting from insufficient input validation where one user can add content to a web site that can be malicious when viewed by other users to the web site. For example, one might post to a message board that accepts arbitrary HTML and include a malicious code item.

[**Eavesdropping attack**](https://www.owasp.org/index.php/Category:Glossary%23E)

Any attack on a data connection where one simply records or views data instead of tampering with the connection.

[**Encryption**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Conversion of plaintext to ciphertext through the use of a cryptographic algorithm.

**Exploit**

Successfully leveraging a security vulnerability to gain unauthorized access to a system or its contents.

**Exploitability**

The ease with which a given vulnerability can be successfully exploited.

[Hash function](https://www.owasp.org/index.php/Category:Glossary%23H)

A function that maps a string of arbitrary length to a fixed size value in a deterministic manner. Such a function may or may not have cryptographic applications.

**HTTP**

Hypertext Transport Protocol. The network messaging protocol commonly used for transmission of requests and responses (including web pages and data) between browser and mobile applications and their servers.

**HTTPS**

Secure HTTP. HTTP sent over a secure link to protect the authenticity, privacy, and security of the information being transmitted.

[**Impact**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

The magnitude of harm that can be expected to result from the consequences of unauthorized disclosure of information, unauthorized modification of information, unauthorized destruction of information, or loss of information or information system availability..

**Intercepting proxy** see **Proxy**

[**Internet Protocol**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Standard protocol for transmission of data from source to destinations in packet-switched communications networks and interconnected systems of such networks.

**localhost**

A standard name used to define the network name of the host computer to programs running on that computer. In other words "this computer". For example setting the IP address in a proxy program to localhost tells it to monitor that computer's network interface. This can also be represented with the default address 127.0.0.1.

[**Man-in-the-middle attack**](https://www.owasp.org/index.php/Category:Glossary%23M)

An eavesdropping attack where a client's communication with a server is proxied by an attacker. Generally, the implication is that the client performs a cryptographic key exchange with an entity and fails to authenticate that entity, thus allowing an attacker to look like a valid server

**MITM** see **Man-in-the-middle attack**

[**Phishing**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

A digital form of social engineering that uses authentic-looking—but bogus—emails to request information from users or direct them to a fake Web site that requests information

[**Plaintext**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Intelligible data that has meaning and can be understood without the application of decryption.

**Proxy**

A program that acts as an intermediary between a user's applications and the internet. In security testing, a proxy can be used to examine and modify the requests and responses between an application and its servers

**Remote attack**

A remote attack can be exploited without access to a user's network traffic. For example, an API that provides user information without checking that the requestor has access rights for the information makes a remote attack possible.

[**Salt**](https://www.owasp.org/index.php/Category:Glossary%23S)

Data that can be public but is used to prevent against precomputation attacks.

[**Secure Socket Layer**](https://www.owasp.org/index.php/Category:Glossary%23S)

A popular protocol for establishing secure channels over a reliable transport, utilizing a standard X.509 Public Key Infrastructure for authenticating machines. This protocol has evolved into the TLS protocol, but the term SSL is often used to generically refer to both.

[**Session Token**](https://www.owasp.org/index.php/Category:Glossary%23S)

A value that represents a user's identity during their session. Typically the user provides some form of credentials (e.g., username, password, possibly a one-time token value from a second authentication factor) and the server returns a token value that represents the user's identity. In web applications, this token is often returned in a cookie. The client application includes the session token with each request, enabling the server to associate each request with the same user, role, and session.

**Session Hijack**

An attack that takes over a session belonging to another user. This is typically accomplished through acquiring the user's Session Token cookie and installing it in an attacker's browser.

**Sidejack** see **Session Hijack**

[**Snooping**](https://www.owasp.org/index.php/Category:Glossary%23S) See also:Eavesdropping

Attacks where data is read off a network while in transit without modifying or destroying the data.

[**Social engineering**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

A general term for attackers trying to trick people into revealing sensitive information or performing certain actions, such as downloading and executing files that appear to be benign but are actually malicious.

**Spoofing**

The practice of falsifying data to masquerade as a legitimate resource or entity.

**SSL** see **Secure Socket Layer**

**SSL Certificate Spoofing**

An attack that provides an SSL Certificate from an untrusted source in an attempt to gain access to encrypted SSL communications. Problems in a mobile application's certificate verification can allow this attack to succeed.

[**Transport Layer Security**](https://www.owasp.org/index.php/Category:Glossary%23T)

The successor to SSL, a protocol for establishing secure channels over a reliable transport, using a standard X.509 Public Key Infrastructure for authenticating machines. The protocol is standardized by the IETF.

See also: **Secure Socket Layer**

**TLS** see **Transport Layer Security**

**URL**

Uniform Resource Locator: another term for a site's "web address", specifying how to find it on the internet. For example: https://www.graphite.org

**Vulnerability**

A security weakness in a system or application. A vulnerability creates an opportunity for an exploit that can impact an application and its users by compromising the system or its contents.
