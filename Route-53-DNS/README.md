# Route 53 and DNS

## Overview

Amazon Route 53 is a highly available and scalable DNS (Domain Name System) web service provided by AWS.

## What is DNS?

DNS translates human-readable domain names into IP addresses.

For example:

example.com → IP address

This allows users to access websites using domain names instead of remembering IP addresses.

## Route 53

Route 53 can be used for:

- Domain registration
- DNS management
- Health checking
- Routing traffic to AWS and external resources

## DNS Record Types

Common DNS records include:

- A – Maps a domain name to an IPv4 address.
- AAAA – Maps a domain name to an IPv6 address.
- CNAME – Maps one domain name to another domain name.
- MX – Specifies mail servers for a domain.
- TXT – Stores text information associated with a domain.

## Routing Policies

Route 53 supports different routing policies, including:

- Simple routing
- Weighted routing
- Latency-based routing
- Failover routing
- Geolocation routing

## Key Takeaways

- DNS translates domain names into IP addresses.
- Route 53 is AWS's DNS service.
- Route 53 can manage domains and DNS records.
- Routing policies determine how Route 53 directs traffic.
- Route 53 can improve application availability using health checks and routing.
