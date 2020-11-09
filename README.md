# OAuth1-HMAC

OAuth1-HMAC is a simple library implementing the [OAuth1.0 protocol](https://en.wikipedia.org/wiki/OAuth) as a consumer, using the [HMAC signing strategy](https://en.wikipedia.org/wiki/HMAC).

This library wraps the [Google OAuth Client Library for Java](https://developers.google.com/api-client-library/java/google-oauth-java-client) (`google-oauth-client` | [GitHub](https://github.com/googleapis/google-oauth-java-client)) which implements the underlying OAuth1.0 functionality ([JavaDoc](https://googleapis.dev/java/google-oauth-client/1.25.0/com/google/api/client/auth/oauth/package-summary.html)).

Please note that the OAuth1.0 implementation in `google-oauth-client` is in Beta, and is thus subject to change. Its implementation has been tested and verified working for version `1.31.0`. For higher versions, it exhibits buggy behaviour, and thus the version of the `google-oauth-client` dependency shall only be bumped if the OAuth1.0 implementation remains unchanged and works.
 
 **If your project uses a conflicting version of `google-oauth-client`** (such a dependency may come transitively from `google-oauth1-client`) then **usage of this library is highly unrecommended**.
 
 ## Usage
 
 ## Documentation
 
 The latest version of OAuth1-HMAC has a JavaDoc [here](https://omarathon.github.io/oauth1-hmac/).