# Motrix Expansion Privacy Policy

Last updated: 2026-04-21

## Overview

Motrix Expansion is a browser extension that helps users send downloads and links to their own Motrix or aria2 RPC endpoint.

Motrix Expansion does not operate a developer-hosted backend service for collecting user data. Data handled by the extension is used only to provide the extension's download integration features on the user's device and with the user's configured Motrix or aria2 endpoint.

## Data the Extension May Access

Depending on the features the user enables, the extension may access:

- Download URLs and page URLs
- Link, image, audio, and video source URLs selected by the user
- Request headers such as `Referer`
- Cookies for supported download requests
- Custom headers entered by the user in extension settings
- Local extension settings and recent activity logs stored in the browser

## How Data Is Used

The extension uses this data only to:

- Send selected or intercepted downloads to the user's configured Motrix or aria2 RPC endpoint
- Preserve required request context for downloads when the user enables options such as cookie or referer forwarding
- Display connection status, transfer statistics, and recent activity inside the extension UI
- Store user preferences locally in browser extension storage

## Data Sharing

Motrix Expansion does not sell user data and does not send user data to the developer.

When the user enables Motrix integration, relevant request data may be transmitted to the RPC endpoint configured by the user. That endpoint is controlled by the user or the user's chosen environment, not by the developer of this extension.

## Local Storage

The extension stores configuration and limited recent activity logs locally in the browser so the extension can function correctly.

Examples include:

- RPC connection settings
- UI preferences
- Feature toggles
- Recent action and error logs

## User Controls

Users can control data handling by:

- Disabling Motrix integration in the popup
- Disabling browser download takeover in Settings
- Turning off cookie forwarding
- Turning off referer forwarding
- Removing custom headers from Settings
- Removing the extension at any time through the browser's extension management page

## Third-Party Services

Motrix Expansion does not include developer analytics, advertising SDKs, or developer-operated telemetry services.

If the user configures the extension to communicate with a Motrix or aria2 RPC endpoint, that communication is subject to the privacy and security practices of the system the user configures.

## Security

The extension uses browser-provided extension storage and standard browser extension APIs. Users are responsible for securing their own Motrix or aria2 environment, including any RPC secret, host, or network exposure.

## Changes to This Policy

This privacy policy may be updated if the extension's features or data handling practices change. Updated versions will be published in this document.

## Contact

For support or privacy questions, see `SUPPORT.md` in this repository.
