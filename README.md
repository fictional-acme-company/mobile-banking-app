# Acme Mobile Banking

Acme Mobile Banking is the customer-facing mobile app for everyday banking: balances, transfers, bill pay, card controls, and secure account access on the go.

## Overview

This repository represents the native mobile experience used by Acme customers across iOS and Android. The product is designed to provide a fast, reliable, and familiar banking workflow with a strong focus on account visibility, self-service, and security.

## Key Features

- Sign in with biometric or password-based authentication
- View checking, savings, and card balances
- Transfer funds between Acme accounts
- Review recent transactions and pending items
- Lock, unlock, and manage payment cards
- Receive push notifications for important account activity
- Access support and branch/contact details

## Suggested Stack

- React Native
- TypeScript
- Mobile navigation and state management
- REST APIs provided by Acme backend services
- Secure token storage and device biometrics

## Repository Layout

- `.github/workflows/` - CI and automation workflows
- `src/` - application code
- `assets/` - app icons, illustrations, and static media
- `tests/` - unit and integration tests
- `docs/` - product and release notes

## Local Development

Typical setup steps for this project would be:

1. Install dependencies with the package manager used by the team.
2. Start the mobile bundler or native development environment.
3. Run the test suite before opening a pull request.
4. Validate builds on both target platforms when release changes are made.

## Environment Notes

The mobile app is expected to use environment-specific API endpoints for local, staging, and production testing. Secrets and credentials should stay out of source control.

## Automation

This repository includes a DevXP analysis workflow that runs on pushes to `main` and publishes repository metrics for internal reporting.

## Contributors
@david-alonso
@sheila-dev