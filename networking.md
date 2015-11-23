# networking

## Internet

The Internet is the hardware network that allows us to transmit data.

## Web

The Web is a collection of linked hypertext documents.

## IP address

An Internet Protocol address (IP address) is a numerical label assigned to each device (e.g., computer, printer) participating in a computer network.

## Protocol

Protocol usually refers to a set of rules that define an exact format for communication between systems For example the HTTP protocol defines the format for communication between web browsers and web servers.

## Firewall

Filtering function. Network security system that controls the incoming and outgoing network traffic.
HTTP over SSL typical port is 443.

## Proxy

An agent authorised to act for another behalf which authorizes the agent so to act.
SSL proxy server allows anonymous web browsing (cannot trace your real IP) through secure SSL encryption.

## SNI

Server Name Indication is an extension to the TLS computer networking protocol by which a client indicates which hostname it is attempting to connect to at the start of the handshaking process.

This allows a server to present multiple certificates on the same IP addresses and hence allows multiple secure (HTTPS) websites to be served of the same IP address.

## DNS

The Domain Name System - a hierarchical distributed naming system for computers, services, or any resource connected to the Internet or a private network.

## CNAME record

A Canonical Name record.
CNAME record - a type of resource record in the DNS used to specify that a domain name is an alias for another domain, the "canonical" domain.
For example, beta.domain.com points to the DNS A record for www.domain.com, which points to the IP-address. Then, if the IP-address ever changes, one only has to record the change in one place within the network: in the DNS A record. This is the reason why CNAME records must always point to another domain name, never directly to an IP-address.

[RFC 1035: CNAME](http://tools.ietf.org/html/rfc1035#page-12)

## A record

The A in A record stands for Address. Simply put, an A record is used to find the address of a computer connected to the internet from a name.

[RFC 1035: DOMAIN NAMES - IMPLEMENTATION AND SPECIFICATION](https://tools.ietf.org/html/rfc1035)

## API

Application Programming Interface - the rules which developers follow to communicate with outside world from inside their own programs or websites.


## SOAP

Simple Object Access Protocol - An XML (Extensible Mark-up Language) specification which is used to communicate with the API.

