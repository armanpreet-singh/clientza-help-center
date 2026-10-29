# Clientza Help Center

Customer documentation for Clientza business owners and prospective owners.

This is a public documentation repository powered by Mintlify.

## Purpose

The Help Center explains how owners use Clientza in plain language, including:

- Getting started and onboarding
- Business settings and daily operations
- Services, providers, customers, appointments, and payments
- Profile, account access, FAQs, and troubleshooting

This repository is for customer help content, not developer documentation.

## Audience

- Prospective Clientza owners
- New owners completing onboarding
- Existing owners managing day-to-day workflows

## Repository layout

- docs.json: Site configuration, navigation, and branding
- index.mdx: Help Center homepage
- getting-started/: Onboarding and access guides
- business-settings/: Business profile and availability settings
- services/, providers/, customers/, appointments/, payments/, communications/: Feature guides
- account/: Profile and account-recovery guides
- troubleshooting/ and faq.mdx: Problem-solving content
- internal/: Internal review artifacts and evidence logs (not in public navigation)

## Local development

Prerequisites:

- Node.js 18+

Run locally:

1. Open this folder in a terminal.
2. Start the Mintlify preview server:

	npx mintlify dev

3. Open the local URL shown in terminal output.

## Content standards

- Write for non-technical business owners.
- Keep instructions task-focused and step-by-step.
- Use visible UI labels from the product.
- Do not publish API, schema, or internal implementation details.
- Do not present preview or unverified workflows as fully available.
- Avoid inventing policies, fees, legal terms, or support guarantees.

## Quality checklist before merge

- docs.json is valid JSON.
- Every page listed in navigation exists.
- Internal links resolve.
- Frontmatter and MDX render correctly.
- No starter content or placeholder links remain.
- Feature claims match currently verified behavior.

## Contribution workflow

1. Create a branch for your changes.
2. Update content and navigation as needed.
3. Run local preview and spot-check changed pages.
4. Validate links and article paths.
5. Open a pull request with:
	- Summary of content changes
	- User impact
	- Any known limitations or review-required items

## Public repo policy

- Treat this repository as publicly visible.
- Do not commit secrets, private credentials, or internal-only sensitive details.
- Keep internal notes in controlled internal pages and exclude them from public navigation.

## Brand

The Help Center uses the Clientza brand palette configured in docs.json:

- Primary: #A65370
- Light: #F8E9EE
- Dark: #8F3D5A

## License

No license file is currently included in this repository.
Add an explicit license before wider external reuse is permitted.
