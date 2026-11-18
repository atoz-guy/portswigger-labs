# Server-Side Request Forgery (SSRF)

SSRF happens when an attacker can make the application server send requests to a destination of the attacker's choosing. Because the request comes from the server, it can reach internal services, such as admin panels and back-end systems, that are not exposed to the internet.

## Labs

| # | Lab | Key idea |
|---|---|---|
| 01 | [Basic SSRF against the local server](Lab01-Basic-SSRF/README.md) | `localhost` means the server itself, which trusts its own requests |
