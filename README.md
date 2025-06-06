﻿# Authorization-jwt-verifier (RS256)

## Browser-Native Implementation:
* Uses Web Crypto API
* Uses TextEncoder/TextDecoder for string/buffer conversion
* No external dependencies required

## Full JWT Verification Features:

* Fetches JWKS from the given endpoint.
* Converts JWK to CryptoKey using Web Crypto API.
* Verifies RS256 signatures.
* Checks token expiration and timing claims.
* Provides detailed feedback on all verification steps.

## Comprehensive Results

* Shows exactly why verification fails/succeeds.
* Displays decoded payload.
* Highlights timing issues (like expiration).
* Shows key matching status.

You can paste in fresh tokens to test with current keys from the given JWKS endpoint.
This implementation works in any modern browser.
