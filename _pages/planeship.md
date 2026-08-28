---
layout: archive
title: ""
permalink: /planeship/
author_profile: true
redirect_from:
  - /resume
---


{% include base_path %}

![LinkedIn_Banner](/images/planeship_IDP.jpg)

## An Internal Developer Platform. Built for your organization. Running in your infrastructure.

Most organizations know they need an Internal Developer Platform. Few know how to assemble the right tools in a way that actually benefits a development team — without spending two years getting the first team onboarded.

Planeship would change that.

## The Problem

Backstage, ArgoCD, SonarQube, Trivy, Gitleaks, External Secrets Operator, Grafana, Loki, Prometheus. Every one of these tools is good. None of them works alone. And anyone who wants to build, integrate, and operate them long-term needs capacity that most platform teams simply do not have.

The result: either a half-finished setup nobody trusts, or an 18-month project that dies with the third personnel change.

## How Planeship Would Work

Planeship reverses the order. Instead of introducing tools one by one, a single Kubernetes Operator — the Planeship Operator — deploys the entire platform. You describe what you want in a single Custom Resource. The Operator builds it and keeps it current.

Included in every installation: Backstage with Azure AD Auth, GitHub Actions CI/CD with four stages, ArgoCD, SonarQube, Gitleaks, Trivy, OPA, Grafana, Loki, Prometheus, and External Secrets Operator.

No shared SaaS. No vendor lock-in at the operations layer. Your infrastructure, your control.

## What You Could Add

Beyond the base platform, we have designed four add-on modules for Planeship:

- Planeship Security+: Black Duck SCA, OWASP ZAP DAST, SBOM via CycloneDX
- Planeship AI Pipeline: CodeRabbit code review, CodiumAI test generation
- Planeship Azure Services: MySQL, EventHub, ServiceBus, Redis — provisioned via Terraform, secrets auto-injected
- Planeship Compliance+: SBOM repository, audit reports, extended OPA policies

Each module is independent. You add what you need, when you need it.

## Who Is Behind Planeship

We are a small engineering team with backgrounds in enterprise architecture, Kubernetes, and platform engineering. The concept is solid, the architecture is defined. What we are looking for is the right first customer to build Planeship with us.

This is not a finished product with a price list. It is an offer to organizations that are serious about an IDP and willing to take the first step with a team that knows where it is going.

## Who This Makes Sense For

Organizations with multiple development teams running on Azure, a platform engineering capacity of fewer than two people, and a need for enterprise-grade infrastructure. Organizations that cannot afford to wait 24 months.

## Start a Conversation

If you recognize the problem — reach out. No form, no sales funnel. A direct conversation about whether Planeship fits your organization.

**Write an E-Mail**

-------------

*Planeship is the internal working title we use while the product is in development. The final name may change before launch.*


