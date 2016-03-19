# F. Glossary

Many of the definitions below are taken from the OWASP glossary ([https://www.owasp.org/index.php/Category:Glossary](https://www.owasp.org/index.php/Category:Glossary)), and the NIST Glossary of Key Information Security Terms, NISTIR 7298, revision 2 ([http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)). Definitions taken from these documents contain links to the source document in the title of the glossary term.

## A

<a name="h.glossary-api"></a>**API**

Application Programming Interface. For web and mobile applications, this is a network-facing interface that the application can use to request user-specific information from the application's servers.

<a name="h.glossary-auth-cookie"></a>**Authentication Cookie** 

See [Session Token](glossary.md#h.glossary-session-token)

## C

<a name="h.glossary-certificate"></a>[**Certificate**](https://www.owasp.org/index.php/Category:Glossary%23C)

A data object that binds information about a person or some other entity to a public key. The binding is generally done using a digital signature from a trusted third party (a certification authority).

<a name="h.glossary-ca"></a>[**Certification Authority**](https://www.owasp.org/index.php/Category:Glossary%23C)

An entity that manages digital certificates — i.e., issues and revokes.

<a name="h.glossary-cipertext"></a>[**Ciphertext**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Data in its encrypted form.

<a name="h.glossary-cookies"></a>[**Cookies**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Data exchanged between an HTTP server and a browser (a client of the server) to store state information on the client side and retrieve it later for server use.

<a name="h.glossary-xss"></a>[**Cross-site scripting**](https://www.owasp.org/index.php/Category:Glossary%23C)

A class of problems resulting from insufficient input validation where one user can add content to a web site that can be malicious when viewed by other users to the web site. For example, one might post to a message board that accepts arbitrary HTML and include a malicious code item.

## E

<a name="h.glossary-eavesdropping"></a>[**Eavesdropping attack**](https://www.owasp.org/index.php/Category:Glossary%23E)

Any attack on a data connection where one simply records or views data instead of tampering with the connection.

<a name="h.glossary-encryption"></a>[**Encryption**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Conversion of plaintext to ciphertext through the use of a cryptographic algorithm.

<a name="h.glossary-exploit"></a>**Exploit**

Successfully leveraging a security vulnerability to gain unauthorized access to a system or its contents.

<a name="h.glossary-exploitability"></a>**Exploitability**

The ease with which a given vulnerability can be successfully exploited.

## H

<a name="h.glossary-hash-function"></a>[**Hash function**](https://www.owasp.org/index.php/Category:Glossary%23H)

A function that maps a string of arbitrary length to a fixed size value in a deterministic manner. Such a function may or may not have cryptographic applications.

<a name="h.glossary-http"></a>**HTTP**

Hypertext Transport Protocol. The network messaging protocol commonly used for transmission of requests and responses (including web pages and data) between browser and mobile applications and their servers.

<a name="h.glossary-https"></a>**HTTPS**

Secure HTTP. HTTP sent over a secure link to protect the authenticity, privacy, and security of the information being transmitted.

## I

<a name="h.glossary-impact"></a>[**Impact**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

The magnitude of harm that can be expected to result from the consequences of unauthorized disclosure of information, unauthorized modification of information, unauthorized destruction of information, or loss of information or information system availability.

<a name="h.glossary-intercepting-proxy"></a>**Intercepting proxy** 

See [Proxy](glossary.md#h.glossary-proxy).

<a name="h.glossary-internet-protocol"></a>[**Internet Protocol**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Standard protocol for transmission of data from source to destinations in packet-switched communications networks and interconnected systems of such networks.

## L

<a name="h.glossary-localhost"></a>**localhost**

A standard name used to define the network name of the host computer to programs running on that computer. In other words "this computer". For example setting the IP address in a proxy program to localhost tells it to monitor that computer's network interface. This can also be represented with the default address 127.0.0.1.

## M

<a name="h.glossary-man-in-the-middle"></a>[**Man-in-the-middle attack**](https://www.owasp.org/index.php/Category:Glossary%23M)

An eavesdropping attack where a client's communication with a server is proxied by an attacker. Generally, the implication is that the client performs a cryptographic key exchange with an entity and fails to authenticate that entity, thus allowing an attacker to look like a valid server.

<a name="h.glossary-mitm"></a>**MITM** 

See [Man-in-the-middle attack](glossary.md#h.glossary-man-in-the-middle).

## P

<a name="h.glossary-phishing"></a>[**Phishing**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

A digital form of social engineering that uses authentic-looking—but bogus—emails to request information from users or direct them to a fake Web site that requests information.

<a name="h.glossary-plaintext"></a>[**Plaintext**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

Intelligible data that has meaning and can be understood without the application of decryption.

<a name="h.glossary-proxy"></a>**Proxy**

A program that acts as an intermediary between a user's applications and the internet. In security testing, a proxy can be used to examine and modify the requests and responses between an application and its servers.

## R

<a name="h.glossary-remote-attack"></a>**Remote attack**

A remote attack can be exploited without access to a user's network traffic. For example, an API that provides user information without checking that the requestor has access rights for the information makes a remote attack possible.

## S

<a name="h.glossary-salt"></a>[**Salt**](https://www.owasp.org/index.php/Category:Glossary%23S)

Data that can be public but is used to prevent against precomputation attacks.

<a name="h.glossary-secure-socket-layer"></a>[**Secure Socket Layer**](https://www.owasp.org/index.php/Category:Glossary%23S)

A popular protocol for establishing secure channels over a reliable transport, utilizing a standard X.509 Public Key Infrastructure for authenticating machines. This protocol has evolved into the TLS protocol, but the term SSL is often used to generically refer to both.

<a name="h.glossary-session-token"></a>[**Session Token**](https://www.owasp.org/index.php/Category:Glossary%23S)

A value that represents a user's identity during their session. Typically the user provides some form of credentials (e.g., username, password, possibly a one-time token value from a second authentication factor) and the server returns a token value that represents the user's identity. In web applications, this token is often returned in a cookie. The client application includes the session token with each request, enabling the server to associate each request with the same user, role, and session.

<a name="h.glossary-session-hijack"></a>**Session Hijack**

An attack that takes over a session belonging to another user. This is typically accomplished through acquiring the user's Session Token cookie and installing it in an attacker's browser.

<a name="h.glossary-sidejack"></a>**Sidejack** 

See [Session Hijack](glossary.md#h.glossary-session-hijack).

<a name="h.glossary-snooping"></a>[**Snooping**](https://www.owasp.org/index.php/Category:Glossary%23S) 

Attacks where data is read off a network while in transit without modifying or destroying the data.

See also:[Eavesdropping attack](glossary.md#h.glossary-eavesdropping)

<a name="h.glossary-social-engineering"></a>[**Social engineering**](http://nvlpubs.nist.gov/nistpubs/ir/2013/NIST.IR.7298r2.pdf)

A general term for attackers trying to trick people into revealing sensitive information or performing certain actions, such as downloading and executing files that appear to be benign but are actually malicious.

<a name="h.glossary-spoofing"></a>**Spoofing**

The practice of falsifying data to masquerade as a legitimate resource or entity.

<a name="h.glossary-ssl"></a>**SSL** 

See [Secure Socket Layer](glossary.md#h.glossary-secure-socket-layer).

<a name="h.glossary-ssl-spoofing"></a>**SSL Certificate Spoofing**

An attack that provides an SSL Certificate from an untrusted source in an attempt to gain access to encrypted SSL communications. Problems in a mobile application's certificate verification can allow this attack to succeed.

## T

<a name="h.glossary-tls"></a>**TLS** 

See [Transport Layer Security](glossary.md#h.glossary-transport-layer-security).

<a name="h.glossary-transport-layer-security"></a>[**Transport Layer Security**](https://www.owasp.org/index.php/Category:Glossary%23T)

The successor to SSL, a protocol for establishing secure channels over a reliable transport, using a standard X.509 Public Key Infrastructure for authenticating machines. The protocol is standardized by the IETF.

See also: [Secure Socket Layer](glossary.md#h.glossary-secure-socket-layer).

## U

<a name="h.glossary-url"></a>**URL**

Uniform Resource Locator: another term for a site's "web address", specifying how to find it on the internet. For example: https://www.graphite.org.

## V

<a name="h.glossary-vulnerability"></a>**Vulnerability**

A security weakness in a system or application. A vulnerability creates an opportunity for an exploit that can impact an application and its users by compromising the system or its contents.
