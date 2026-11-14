# OpenID Client — TrillionAI Engineering Source Reference

Independent pinned source reference of [panva/openid-client](https://github.com/panva/openid-client), for researching secure OAuth 2.0 and OpenID Connect client implementations, PKCE, authorization-code exchanges, token rotation and identity-provider interoperability for the future TrillionAI Connect integration system.

## Source provenance

- Official upstream: `panva/openid-client`
- Pinned source commit: `7eb59483b44241d843a96903e5c7a09a747f6b06`
- Original Git tree: `a95f14972a41c0f69d95d92a686692c3fe5a19a6`
- [Dedicated source snapshot](https://github.com/Anselm04/OpenID-Client-Source-Code-Reference/tree/openid-client-upstream-snapshot/upstream): branch `openid-client-upstream-snapshot`, with the original tracked files under `upstream/`
- [Import and Git-tree verification workflow](https://github.com/Anselm04/OpenID-Client-Source-Code-Reference/actions/workflows/import-openid-client-source.yml)

Treat import as verified only when GitHub Actions verifies that the remote imported subtree matches the pinned original Git tree. An archival snapshot does not contain full Git history, external submodule payloads, independently downloaded Git LFS objects or running third-party identity providers.

## Licence and authorship

The upstream `LICENSE.md` specifies MIT, Copyright (c) 2016 Filip Skokan. The source snapshot keeps the original licence, copyright notices and upstream attribution unchanged. Assess file-specific and dependency licences before reuse.

## TrillionAI engineering separation

This public repository is strictly for lawful research into OAuth/OIDC client security. Keep original source separate from proprietary TrillionAI code. Build the independent TrillionAI Connect service with a Node.js backend, scoped credentials and a Flutter management interface; do not implement custom cryptography or expose credentials to AI agents. No imported code is executed, no paid services are activated and no production deployments are performed as part of this snapshot.
