# Sorcia Documentation

Official documentation for Sorcia - AI-Powered Enterprise Knowledge Base

Built with [Mintlify](https://mintlify.com), this repository contains comprehensive guides, API references, and integration documentation for Sorcia.

## 📚 Documentation Structure

- **Introduction** - What is Sorcia, key features, getting started
- **Getting Started** - Quickstart, installation, environment setup
- **Core Concepts** - How Sorcia works, architecture, permissions
- **Integrations** - Slack, Notion, Google Drive, GitHub, and more
- **API Reference** - Authentication, query endpoints, webhooks
- **Team Management** - Roles, permissions, access control
- **Security & Compliance** - Row-level security, audit logs, compliance
- **Advanced** - Self-hosting, optimization, troubleshooting

## 🎨 Brand Colors

- **Primary**: `#F97316` (Sorcia Orange)
- **Dark**: `#1a1a1a` (Black)
- **Background**: `#FAF9F5` (Cream)
- **Accent**: `#F0EEE6` (Beige)

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
