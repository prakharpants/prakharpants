# Prakhar Pant

Co-founder and engineer at [LegalKonnect](https://legalkonnect.in), a legal services platform for India. I build it and I run it.

## LegalKonnect

Legal help at a fixed price. Consultations, document drafting, and case management for clients and for the advocates working with them.

Next.js 16 (App Router), React 19, TypeScript, Tailwind v4, Supabase, Vercel.

A few parts I've put real time into:

- Four portals on one auth model: clients, advocates, internal ops, admin. Postgres row level security is what keeps them apart.
- Razorpay payments, with server side signature checks, webhook reconciliation, and an idempotency table so a retried request can never charge someone twice.
- OTP login, signed URL document access, coupons, invoicing, and the revenue dashboards we actually use day to day.

## Agentic content pipeline

A system that publishes a legal explainer every day. It picks a topic, researches it, drafts, checks the claims against Indian law, reviews, revises, then publishes through the CMS. Every one of those is a separate pass with its own prompt, which turned out to be the only way to stop it sounding like a robot.

## Agent skills

Instruction sets that make AI coding agents better at specific jobs: React and Next.js performance, web interface and accessibility rules, component composition. Written in the [Agent Skills](https://agentskills.io/) format.

## Stack

TypeScript, React, Next.js, Node, Postgres and Supabase, Tailwind, Vercel

## Say hi

[legalkonnect.in](https://legalkonnect.in) · prakhar1pant@gmail.com
