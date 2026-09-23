# cloudkep-legal

Public static application and policy pages for CloudKep projects.

## CloudKep Family Hub

Production URLs:

- https://legal.cloudkep.com/family-hub/
- https://legal.cloudkep.com/family-hub/privacy/
- https://legal.cloudkep.com/family-hub/terms/

## Deployment

This repository deploys to Cloudflare Workers Static Assets through Git integration.

- Build command: none
- Deploy command: `npx wrangler deploy`
- Assets directory: `./public`
- Production branch: `main`

The site is plain static HTML/CSS with no application build step and no runtime secrets.
