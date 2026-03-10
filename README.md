# KAuthNZ
                                                                                                                                                                         
  Identity Infrastructure built from first principles.                                                                                                                                                                         

  Not a wrapper. Not a hosted service.
  A ground-up implementation of sovereign, federated identity
  for organizations that cannot afford to trust a third party
  with their users.

  ---

  ## What makes it different

  Most identity systems centralize trust by design.
  KAuthNZ makes trust a cryptographic property — not a policy.

  - **Liquid Identity** — one persistent Subject ID across tenants,
    with cryptographic isolation between them. No tenant can see
    or correlate another tenant's identity data, even for the same user.

  - **Sovereign tenants** — each master tenant is an autonomous
    OIDC provider with its own keys, its own trust anchor,
    and its own cryptographic boundary.

  - **Federation as consequence** — nodes federate because the
    architecture allows it, not because federation was bolted on top.
    The Isolated Border Pattern ensures no partition ever reads
    another partition directly.

  - **Cryptography first** — DEK lifecycle, BYOK, post-quantum
    readiness (ML-DSA) from day one. Not planned. Built in.

  ---

  ## Protocol compliance

  Built strictly against IETF RFCs and OpenID Foundation specifications:

  OAuth 2.1 · OIDC Core · FAPI 2.0 · OpenID Federation 1.0
  PAR · JAR · JARM · DPoP · mTLS · DCR
  JOSE stack (JWA · JWE · JWS · JWK) · Post-Quantum (ML-DSA)

  ---

  ## Who this is for

  Organizations where identity sovereignty is not optional:

  - Financial services operating across jurisdictions
  - Healthtech networks with data residency requirements
  - Government digital identity programs
  - B2B2C SaaS platforms where each tenant must be a
    sovereign identity context

  ---

  ## Status

  Under active development.
  FAPI 2.0 certification in progress.

  ---

  ## Architecture

  Documentation at [blog.kauthnz.com](https://blog.kauthnz.com)
