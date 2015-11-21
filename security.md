# security

## PKI

A Public Key Infrastructure.

Public keys binded with respective user identities issued by a certificate authority).

[Interoperability in PKI](https://www.sans.org/reading-room/whitepapers/vpns/interoperability-pki-724)

## X.509

X.509 system certification - is an ITU-T standard for a public key infrastructure (PKI)

The X.509 comes from the X series of the International Telecommunications Union – Telecommunications (ITU-T), formerly known as the CCITT.

The purpose of the X series is the standardization of data networks and open system communications.

## X.509 Certificate

This file binds a name to a public key value.

## SSL 

Secure Sockets Layer - is the standard security technology for establishing an encrypted link/connection between a web server and the internet browser. This link/connection ensures that all data passed between two parties/sides remain private and integral.

## TLS

Transport Layer Security - an Internet security protocol used by Internet browsers and Web servers to transmit sensitive information.

## SSL vs TLS

[SSL versus TLS – What’s the difference?](https://luxsci.com/blog/ssl-versus-tls-whats-the-difference.html)

Also

[SSL versus TLS: The Differences and Similarities](https://luxsci.com/blog/ssl-vs-tls-the-difference.html)

## What SSL is used for?

The SSL is used to encrypt the data (communication) between the server (website) and the end-user (Personal Computer) where the server sends you its own public key which you use to encrypt the data on your machine and then you sent it over that encrypted data, where the server uses its matching private key to decrypt your data (secret message). This established using PKCS.

## SSL Handshake

How the browser retrieves a trusted certificate and negotiates what encryption and communication standards it will use.

[SSL Handshake](https://catn.com/2014/09/12/ssl-certificates-tell-me-more/)

## RSA

Ron Rivest, Adi Shamir and Leonard Adleman (RSA) - A public-key cryptosystem used for secure data transmission.
Algorithm publically identified by by Rivest, Shamir and Adleman in 1977.

## ECC

Elliptic Curve Cryptography is a family of public-key algorithms that can provide shorter key lengths and may provide improved performance over systems based on integer factorization and discrete logarithms

## PKCS

Public Key Cryptographic Standards - standards to promote the use of the cryptography techniques.

Format   | Meaning
-------- | -------
PKCS #7  | Contains certificate for the primary domain name as well as the intermediate and root certificate in one file
PKCS #8  | Private key
PKCS #10 | Certificate Signing Request (CSR)
PKCS #11 | Hardware token certificate
PKCS #12 | Contains the private key, certificate for the primary domain as well as the intermediate and root certificate. File is protected with a password

## PEM

Privacy-enhanced Electronic Mail.

This is a Base64 encoded DER certificate. Certificates in this format are used for web servers as they can be read
easily in text editors, such as Notepad. It contains ASCII (Base64) armored data prefixed with a "-----BEGIN
CERTIFICATE REQUEST-----" and "-----END CERTIFICATE REQUEST-----" lines.

## PFX

PKCS#12 format of the certificate. This file is generated if the customer place an order with the Auto-CSR option.
Customer receives Order_Number.PFX file which contains all needed components to successfully install certificate
on the server, it contains the public, intermediate and root certificates and the private key.

## P7M

A file extension used to hold encrypted email messages.

## P7S

A file extension used to hold digital ID signature (public key of the certificate)

## TSA

Time Stamping Authority - Involves securely keeping track of a document's time of signing, prevents documents from being tampered with.

## CRL

Certificate Revocation List - A list of revoked certificates' serial numbers which are no longer considered valid.

## OCSP

Online Certificate Status Protocol - An Internet protocol used to check the revocation status of an X.509 certificate.

## S/MIME

Secure/Multi-purpose Internet Mail Extensions - Public key encryption and signing of MIME data, related to our PersonalSign product.

## API

Application Programming Interface - the rules which developers follow to communicate with outside world from inside their own programs or websites.


## SOAP

Simple Object Access Protocol - An XML (Extensible Mark-up Language) specification which is used to communicate with the API.

## OpenSSL

The Open Source toolkit for SSL/TLS used to convert certificates from one format to another.


## SSO

Single Sign On.
Multi-factor authentication.
With single authentication we may access multiple systems/services without re-entering passwords (various authentication validations) multiple times.

## SSO protocols

Lightweight Directory Access Protocol (LDAP).
Active Directory.
[Single Sign On Concepts & Protocols](https://www.giac.org/paper/gsec/3618/single-sign-concepts-protocols/105876)

## WHOIS record

Provides domain registration information.


## SPF records

Sender Policy Framework (SPF). An SPF record is a type of Domain Name Service (DNS) record that identifies which mail servers are permitted to send email on behalf of your domain.

The purpose of an SPF record is to prevent spammers from sending messages with forged From addresses at your domain. Recipients can refer to the SPF record to determine whether a message purporting to be from your domain comes from an authorized mail server.

[About SPF records](https://support.google.com/a/answer/33786?hl=en)

## DKIM

DomainKeys Identified Mail (DKIM) is an email validation system designed to detect email spoofing by providing a mechanism to allow receiving mail exchangers to check that incoming mail from a domain is authorized by that domain's administrators and that the email (including attachments) has not been modified during transport.