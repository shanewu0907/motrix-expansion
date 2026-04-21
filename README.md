# Motrix Expansion

Motrix Expansion is a browser extension companion for Motrix / aria2.

This repository is used as a public documentation repository for the extension, including privacy and support information that may be required for store listing and user support.

## Repository Purpose

This repository is intentionally lightweight.

It currently provides:

- `README.md` for product overview and usage information
- `PRIVACY.md` for the extension privacy policy
- `SUPPORT.md` for support and contact guidance

This repository may be used as the public website reference for the extension listing.

## What the Extension Does

Motrix Expansion helps users send downloads and page resources to their own Motrix or aria2 environment.

Main capabilities include:

- Send links to Motrix from the browser
- Send image, audio, video, and page URLs to Motrix
- Intercept browser downloads and forward them to Motrix
- Show connection and transfer status in a popup dashboard
- Configure RPC host, port, path, secret, and related settings
- Optionally forward request context such as headers, cookies, and referer when needed for supported downloads

## Intended Use

The extension is designed for users who already run Motrix or aria2 and want a browser-side control panel and download handoff workflow.

The extension does not provide a hosted cloud service. It works with the RPC endpoint configured by the user.

## Privacy

Privacy details are documented in:

- [PRIVACY.md](./PRIVACY.md)

In short:

- The extension does not operate a developer-hosted telemetry backend
- The extension may access request-related data needed to send downloads to the user's configured Motrix or aria2 endpoint
- Settings and recent activity are stored locally in the browser

## Support

Support details are documented in:

- [SUPPORT.md](./SUPPORT.md)

If you need help, bug reporting and support contact guidance should be listed there.

## Typical Setup

To use the extension successfully, users generally need:

1. A running Motrix or aria2 instance
2. A reachable JSON-RPC endpoint
3. The correct RPC host, port, path, and secret configured in the extension

Common default example:

- Host: `127.0.0.1`
- Port: `16800`
- Path: `/jsonrpc`

## Permissions and Functionality

Depending on the enabled features, the extension may need browser permissions related to:

- downloads
- tabs
- storage
- notifications
- cookies
- request handling

These permissions are used to support download interception, request forwarding, connection testing, and extension UI behavior.

## Store Listing Use

This repository can be used as the public reference for a store listing.

Suggested uses:

- `Website` field: repository homepage
- `Privacy policy URL` field: direct link to `PRIVACY.md`
- support reference: `SUPPORT.md`

## Status

This repository is documentation-first and may not contain the full extension source code.

If the source code is published separately in the future, this README may be updated with the appropriate project links.

## Disclaimer

Motrix and aria2 are separate projects and tools. Users are responsible for their own local or self-hosted environment, including RPC exposure, secrets, and network security.
