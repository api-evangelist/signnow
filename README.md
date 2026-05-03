# SignNow

SignNow is an e-signature platform by airSlate that enables businesses to send, sign, and manage legally binding documents electronically. It provides a REST API for embedding e-signature workflows, document creation, template management, and bulk signing operations into any application.

- **Website:** https://www.signnow.com
- **Developer Portal:** https://www.signnow.com/developers
- **Documentation:** https://docs.signnow.com/docs/signnow/welcome
- **API Reference:** https://docs.signnow.com/docs/signnow/reference
- **GitHub:** https://github.com/signnow
- **Pricing:** https://www.signnow.com/pricing

## API

The SignNow REST API is available at:
- **Production:** https://api.signnow.com
- **Sandbox:** https://api-eval.signnow.com

Authentication uses OAuth 2.0 Bearer tokens obtained via `POST /oauth2/token`.

## OpenAPI Specs

| Name | Description |
|---|---|
| [SignNow REST API](openapi/signnow-openapi.yml) | Full REST API covering documents, templates, signing, users, webhooks, and envelopes |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [signnow](capabilities/shared/signnow.yaml) | SignNow REST API consumed definition |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [Document Signing](capabilities/document-signing.yaml) | End-to-end e-signature workflow: upload, invite, sign, download |

## Rules

| Name | Description |
|---|---|
| [SignNow Spectral Rules](rules/signnow-rules.yml) | Spectral ruleset enforcing SignNow API conventions |

## JSON Schema

| Name | Description |
|---|---|
| [Document Schema](json-schema/signnow-document-schema.json) | Schema for the SignNow Document resource |

## JSON Structure

| Name | Description |
|---|---|
| [Document Structure](json-structure/signnow-document-structure.json) | Structural documentation for SignNow Document and related resources |

## JSON-LD

| Name | Description |
|---|---|
| [SignNow Context](json-ld/signnow-context.jsonld) | JSON-LD context mapping SignNow terms to schema.org |

## Examples

| Name | Description |
|---|---|
| [Upload Document](examples/signnow-upload-document-example.json) | Example: uploading a PDF document |
| [Send Signature Invite](examples/signnow-send-signature-invite-example.json) | Example: sending signature invitations to recipients |

## Vocabulary

| Name | Description |
|---|---|
| [SignNow Vocabulary](vocabulary/signnow-vocabulary.yml) | Domain terms for the e-signature platform |

## Maintainers

**API Evangelist**
- URL: https://apievangelist.com
- Email: info@apievangelist.com
