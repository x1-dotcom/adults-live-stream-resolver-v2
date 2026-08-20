<p align="center"><img src="./assets/x1-resolver-hero.svg" alt="X1 Adult Live Stream Resolver v2" width="100%" /></p>
<p align="center"><img src="./assets/x1-resolver-status.svg" alt="X1 resolver evidence status" width="100%" /></p>

# X1 Adult Live Stream Resolver v2

**Public X1 utility for resolving and normalizing authorized HLS live-stream sources.**

This repository currently ships a packaged obfuscated v2 release. The package being present in Git does not prove that every upstream source is online, that every channel still resolves, that response time meets a fixed threshold, or that a particular deployment environment is runtime-compatible.

## What this utility is for

The resolver is intended to sit between an authorized upstream HLS source and a client or IPTV control surface, providing a stable resolver endpoint and normalized output for integrations that need it.

<p align="center"><img src="./assets/x1-resolver-boundary.svg" alt="X1 resolver usage boundary" width="100%" /></p>

## Release posture

Current repository evidence proves that an obfuscated v2 release archive is present:

`adults_script_v2.0_OBFUSCATED.zip`

That is **PROVEN BY SOURCE / REPOSITORY CONTENT** only. Runtime behavior depends on the exact upstream source, network path, PHP environment, web server and client integration.

`PACKAGE PRESENT ≠ TESTED ≠ RUNTIME VERIFIED`

## General compatibility target

The packaged utility is designed for PHP/web-server deployment and HLS-oriented integrations. Exact support for a particular PHP release, web server, player, panel or load-balancer environment must be validated against that target rather than inferred from this README.

## Usage boundary

Use this project only with streams and content that you are authorized to access, process and redistribute. This repository does not grant rights to third-party channels, feeds, trademarks or programming.

Do not use the resolver to bypass authentication, subscription controls, DRM, access-control mechanisms or other technical restrictions protecting content you are not authorized to access.

## Operational guidance

- deploy the release in an isolated application path;
- keep production credentials and provider secrets outside the web root and outside Git;
- expose only the endpoints required by the integration;
- validate TLS, CORS and proxy behavior for the actual deployment environment;
- measure resolver latency from the real deployment instead of relying on hard-coded performance claims;
- treat upstream availability as external state that can change independently of the resolver;
- monitor failures and fail closed where source authorization or resolver state is ambiguous.

## Evidence language

When describing the project, distinguish:

`PROVEN BY SOURCE` · `PROVEN BY TEST` · `PROVEN BY RUNTIME` · `INFERRED` · `UNKNOWN / UNPROVEN` · `RUNTIME NOT VERIFIED`

The previous README included absolute claims such as every listed channel being online, fixed sub-200 ms behavior and “100% working”. Those claims are not retained because the current repository alone cannot prove them continuously.

---

**RESOLVE THE SOURCE.**  
**VERIFY THE OUTPUT.**  
**USE AUTHORIZED CONTENT.**

**X1 // PUBLIC MEDIA UTILITY**
