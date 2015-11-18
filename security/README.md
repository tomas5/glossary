# security

## PKI

A public key infrastructure

[Interoperability in PKI](https://www.sans.org/reading-room/whitepapers/vpns/interoperability-pki-724)

## X.509

X.509 system certification - is an ITU-T standard for a public key infrastructure (PKI)

The X.509 comes from the X series of the International Telecommunications Union – Telecommunications (ITU-T), formerly known as the CCITT.

The purpose of the X series is the standardization of data networks and open system communications.

## SSL 

Secure Sockets Layer - is the standard security technology for establishing an encrypted link/connection between a web server and the internet browser. This link/connection ensures that all data passed between two parties/sides remain private and integral.

## What SSL is used for?

The SSL is used to encrypt the data (communication) between the server (website) and the end-user (Personal Computer) where the server sends you its own public key which you use to encrypt the data on your machine and then you sent it over that encrypted data, where the server uses its matching private key to decrypt your data (secret message). This established using PKCS.

## PKCS

Public Key Cryptographic Standards. 

## SSO

Single Sign On.
Multi-factor authentication.
With single authentication we may access multiple systems/services without re-entering passwords (various authentication validations) multiple times.

## SSO protocols

Lightweight Directory Access Protocol (LDAP).
Active Directory.
[Single Sign On Concepts & Protocols](https://www.giac.org/paper/gsec/3618/single-sign-concepts-protocols/105876)

## SPF records

Sender Policy Framework (SPF). An SPF record is a type of Domain Name Service (DNS) record that identifies which mail servers are permitted to send email on behalf of your domain.

The purpose of an SPF record is to prevent spammers from sending messages with forged From addresses at your domain. Recipients can refer to the SPF record to determine whether a message purporting to be from your domain comes from an authorized mail server.

[About SPF records](https://support.google.com/a/answer/33786?hl=en)

## DKIM

DomainKeys Identified Mail (DKIM) is an email validation system designed to detect email spoofing by providing a mechanism to allow receiving mail exchangers to check that incoming mail from a domain is authorized by that domain's administrators and that the email (including attachments) has not been modified during transport.