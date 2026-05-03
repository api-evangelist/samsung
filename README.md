# Samsung

Samsung Electronics is a global technology leader offering developer platforms for building applications and services across mobile devices, IoT, smart home, enterprise security, and entertainment. The Samsung Developer ecosystem spans SmartThings (IoT and smart home platform), Knox (enterprise device security and management), Galaxy mobile SDKs, Smart TV, and Tizen cross-platform development. Samsung provides REST APIs, SDKs, and tools that enable developers to create connected experiences for hundreds of millions of Galaxy devices and Samsung smart home products worldwide.

**URL:** [Samsung Developer Portal](https://developer.samsung.com/)

## Tags

Consumer Electronics, Developer Platform, IoT, Mobile, Smart Home, Smart TV, Wearables

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-02

## APIs

### SmartThings API

The SmartThings REST API provides programmatic access to the SmartThings platform for controlling connected devices, creating automations, managing locations, rooms, scenes, and building smart home integrations. Base URL: `https://api.smartthings.com/v1`. Supports OAuth 2.0 Bearer tokens and personal access tokens.

#### Tags

Automations, Connected Devices, IoT, Locations, Rules, Scenes, Smart Home, SmartThings

#### Properties

- [Documentation](https://developer.smartthings.com/docs/)
- [Documentation](https://developer.smartthings.com/docs/api/public) — API Reference
- [OpenAPI](openapi/samsung-smartthings-openapi.yml) — SmartThings REST API

### Knox Cloud APIs

Samsung Knox provides enterprise-grade device management and security APIs including Knox Deployment Program, Knox Mobile Enrollment, Knox Configure, Knox Manage, Knox E-FOTA, Knox Guard, and Knox Asset Intelligence.

#### Tags

Device Management, Enterprise, Knox, MDM, Mobile Device Management, Security

#### Properties

- [Documentation](https://docs.samsungknox.com/dev/)
- [Documentation](https://developer.samsungknox.com/develop)

### Samsung Health SDK

The Samsung Health SDK enables developers to create health and fitness applications for Galaxy Watch and smartphones.

#### Tags

Fitness, Galaxy Watch, Health, Wearables

#### Properties

- [Documentation](https://developer.samsung.com/health)

### Galaxy Mobile SDKs

Samsung Galaxy mobile SDKs provide access to device-specific hardware including S Pen, DeX, AR Emoji, foldable optimization, Samsung Blockchain, and TEEGRIS.

#### Tags

Android, Foldable, Galaxy, Mobile, S Pen, Samsung DeX

#### Properties

- [Documentation](https://developer.samsung.com/)

### Samsung Smart TV SDK

Tizen-based development for Samsung Smart TVs including media playback, smart signage, and hospitality displays.

#### Tags

Media, Smart TV, Streaming, Tizen, TV

#### Properties

- [Documentation](https://developer.samsung.com/smarttv)

### Bixby Developer API

Voice assistant integration for Galaxy devices, Smart TVs, and appliances via Bixby capsules.

#### Tags

AI, Bixby, Natural Language Processing, Voice Assistant

#### Properties

- [Documentation](https://bixby.developer.samsung.com/)

### Samsung Wallet API

Digital pass issuance for tickets, boarding passes, loyalty cards, and payment credentials on Galaxy devices.

#### Tags

Digital Wallet, Loyalty, Passes, Payments, Wallet

#### Properties

- [Documentation](https://developer.samsung.com/wallet)

## Common Properties

- [Documentation](https://developer.samsung.com/) — Samsung Developer Portal
- [Documentation](https://docs.samsungknox.com/dev/) — Knox Developer Documentation
- [Documentation](https://developer.smartthings.com/docs/) — SmartThings Developer Documentation
- [GitHub Organization](https://github.com/SmartThingsCommunity) — SmartThings Community
- [GitHub Organization](https://github.com/samsung) — Samsung GitHub

## OpenAPI Specifications

- [openapi/samsung-smartthings-openapi.yml](openapi/samsung-smartthings-openapi.yml) — SmartThings REST API (devices, locations, rooms, scenes, rules, subscriptions, apps)

## Rules

- [rules/samsung-rules.yml](rules/samsung-rules.yml) — Samsung API Spectral Rules

## Capabilities

### Shared Definitions

- [capabilities/shared/smartthings.yaml](capabilities/shared/smartthings.yaml) — Samsung SmartThings API (devices, locations, scenes, rules, subscriptions)

### Workflow Capabilities

- [capabilities/smart-home-control.yaml](capabilities/smart-home-control.yaml) — Smart Home Control (device control, location management, scenes, automation rules, subscriptions)

## JSON Schema

- [json-schema/samsung-smartthings-device-schema.json](json-schema/samsung-smartthings-device-schema.json) — SmartThings Device

## JSON Structure

- [json-structure/samsung-smartthings-device-structure.json](json-structure/samsung-smartthings-device-structure.json) — SmartThings Device Field Hierarchy

## JSON-LD

- [json-ld/samsung-context.jsonld](json-ld/samsung-context.jsonld) — Samsung JSON-LD Context

## Examples

- [examples/samsung-list-devices-example.json](examples/samsung-list-devices-example.json) — List SmartThings Devices Request/Response
- [examples/samsung-execute-device-command-example.json](examples/samsung-execute-device-command-example.json) — Execute Device Command Request/Response

## Vocabulary

- [vocabulary/samsung-vocabulary.yml](vocabulary/samsung-vocabulary.yml) — Samsung Developer Vocabulary

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
