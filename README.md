# Nestify Manufacturing Portal

The Nestify Manufacturing Portal is a restricted B2B operational workspace for manufacturers participating in Nestify's property-address plate production and fulfilment process.

## Purpose

The portal enables authorized manufacturing partners to:

- Receive and review Nestify-issued production orders.
- Organize approved orders into production batches.
- Manufacture plates according to Nestify-controlled specifications.
- Assign and manage unique plate serial numbers.
- Perform quality inspections.
- Manage approved inventory.
- Prepare and dispatch completed orders to Nestify.
- Track order and fulfilment progress.

## Operational Boundaries

The Manufacturing Portal does not control Nestify's authoritative property records or address identity lifecycle.

Manufacturers cannot independently:

- Create Nestify-authorized production orders.
- Modify approved plate specifications.
- Verify property ownership or property identity.
- Authorize plate installation.
- Change authoritative property records.

Nestify retains central authority over property identity, verification, installation authorization, and lifecycle records.

## Technology

- React
- Vite
- JavaScript
- ESLint

## Development

Install dependencies:

    npm install

Start the development server:

    npm run dev

Run lint checks:

    npm run lint

Create a production build:

    npm run build

## Architecture

The portal follows a hybrid architecture:

1. Astryx provides shared UI components and design primitives.
2. Nestify theme tokens provide the product's visual identity.
3. Portal-specific React pages implement manufacturing workflows.
4. Nestify backend APIs provide operational data and enforce business rules.

Astryx integration and backend connectivity will be introduced after compatibility and implementation reviews.

## Project Status

Initial frontend scaffold established. Dashboard implementation and subsequent operational modules are planned.
