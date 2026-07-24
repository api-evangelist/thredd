# Thredd (thredd)

Thredd (formerly Global Processing Services / GPS) is a London-headquartered issuer-processor and next-generation payments technology company, founded in 2007, rebranded to Thredd in 2023, and backed by Advent International. It provides card issuing and issuer processing for fintechs, neobanks, banking-as-a-service platforms, and program managers across Mastercard, Visa, and Discover, spanning 40+ countries, with real-time transaction authorization (External Host Interface / EHI), digital-wallet tokenization, 3-D Secure / strong customer authentication, card controls, and fraud / scam detection. Its home market is the United Kingdom.

Thredd ships a genuine public developer surface: a self-serve Developer Portal that grants a sandbox client id and secret, an API Hub REST API at `https://api.thredd.com/api/v1`, and a ReadMe-hosted API reference documenting roughly 129 endpoints across more than a dozen product OpenAPI definitions. Authentication is FAPI-grade OAuth2 client-credentials using `private_key_jwt` client assertions over mutual TLS (mTLS), brokered by Cloudentity with Raidiam Connect acting as the certificate authority. Webhooks and event subscriptions are supported. The underlying OpenAPI files render only through the hub and are not anonymously downloadable.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/thredd/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thredd/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Issuer Processor
- Card Issuing
- Payment Processing
- Banking-as-a-Service
- Digital Wallets
- Cross-Border
- Fraud
- Open Banking
- FAPI

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Thredd Cards API

Create, retrieve, update, renew, replace, and convert physical and virtual cards; manage card status, cardholder details, card images, encrypted card data, and bulk card creation. The core issuing surface of the Thredd API Hub.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/create-card](https://cardsapidocs.thredd.com/v2.0/reference/create-card)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd Card Transactions API

Retrieve card transactions and transaction history, including load / unload operations and balances.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/get-card-transactions](https://cardsapidocs.thredd.com/v2.0/reference/get-card-transactions)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd Card Controls & Limits API

List and update card control groups, manage merchant allow / disallow lists and card acceptors, and configure card spend limits.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/list-card-control-groups-1](https://cardsapidocs.thredd.com/v2.0/reference/list-card-control-groups-1)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd 3-D Secure (SCA) API

Create, list, update, and delete 3-D Secure credentials and configuration for strong customer authentication on issued cards.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/create-3ds-credentials](https://cardsapidocs.thredd.com/v2.0/reference/create-3ds-credentials)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd PIN & CVV Management API

Set, retrieve, and unblock cardholder PINs, and retrieve and unblock CVV2 values and their status.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/set-pin](https://cardsapidocs.thredd.com/v2.0/reference/set-pin)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd Digital Wallets API

Enroll and provision cards into Apple Pay and Google Pay, generate wallet web-provisioning tokens, and manage payment-instrument tokenization.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/apple-wallet-1](https://cardsapidocs.thredd.com/v2.0/reference/apple-wallet-1)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd Webhooks & Event Subscriptions API

Create and manage webhooks and event subscriptions to receive asynchronous notifications of card, transaction, and account events.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/create-webhook](https://cardsapidocs.thredd.com/v2.0/reference/create-webhook)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd Credit API

Credit account and credit-program endpoints for managing credit overviews and related credit issuing capabilities.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/credit-overview](https://cardsapidocs.thredd.com/v2.0/reference/credit-overview)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd Custom PAN API

Create customisable card numbers (custom PAN) so programs can define specific primary account number patterns.

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/create-custom-pan-1](https://cardsapidocs.thredd.com/v2.0/reference/create-custom-pan-1)
- **Base URL:** `https://api.thredd.com/api/v1`

### Thredd Accounts API

Account-level endpoints supporting account records and money-movement flows (including ACH / micro-deposit verification).

- **Human URL:** [https://cardsapidocs.thredd.com/v2.0/reference/accounts](https://cardsapidocs.thredd.com/v2.0/reference/accounts)
- **Base URL:** `https://api.thredd.com/api/v1`

## Common Properties

- [Website](https://www.thredd.com/)
- [Developer Portal](https://devportal.thredd.com/)
- [Documentation](https://docs.thredd.com/)
- [API Reference](https://cardsapidocs.thredd.com/v2.0/)
- [Getting Started](https://cardsapidocs.thredd.com/v2.0/docs/getting-started-1)
- [Authentication](https://cardsapidocs.thredd.com/v2.0/docs/get-an-authentication-token)
- [Sign Up](https://cardsapidocs.thredd.com/v2.0/docs/gaining-access-to-the-developer-portal)
- [LinkedIn](https://www.linkedin.com/company/thredd/)
- [Privacy Policy](https://www.thredd.com/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
