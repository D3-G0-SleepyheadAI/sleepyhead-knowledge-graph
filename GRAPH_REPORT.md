# Graph Report - backend  (2026-04-13)

## Corpus Check
- Corpus is ~46,497 words - fits in a single context window. You may not need a graph.

## Summary
- 450 nodes · 457 edges · 58 communities detected
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 7 edges (avg confidence: 0.65)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Constructor Gethello|Constructor Gethello]]
- [[_COMMUNITY_Nestjs Decorators|Nestjs Decorators]]
- [[_COMMUNITY_Children Create|Children Create]]
- [[_COMMUNITY_Create Family|Create Family]]
- [[_COMMUNITY_Weight Create|Weight Create]]
- [[_COMMUNITY_Sleep Create|Sleep Create]]
- [[_COMMUNITY_Subscriptions Constructor|Subscriptions Constructor]]
- [[_COMMUNITY_Auth Oauth|Auth Oauth]]
- [[_COMMUNITY_Guard Canactivate|Guard Canactivate]]
- [[_COMMUNITY_Coach Chat|Coach Chat]]
- [[_COMMUNITY_Authservice Constructor|Authservice Constructor]]
- [[_COMMUNITY_Database Constructor|Database Constructor]]
- [[_COMMUNITY_Authcontroller Constructor|Authcontroller Constructor]]
- [[_COMMUNITY_Familiesservice Acceptinvitation|Familiesservice Acceptinvitation]]
- [[_COMMUNITY_Family Children|Family Children]]
- [[_COMMUNITY_Firm Dimension|Firm Dimension]]
- [[_COMMUNITY_Familymembershipservice Assertchildaccess|Familymembershipservice Assertchildaccess]]
- [[_COMMUNITY_Backendauthguard Canactivate|Backendauthguard Canactivate]]
- [[_COMMUNITY_Adminguard Canactivate|Adminguard Canactivate]]
- [[_COMMUNITY_Project Rules|Project Rules]]
- [[_COMMUNITY_Project Context|Project Context]]
- [[_COMMUNITY_Getting Started|Getting Started]]
- [[_COMMUNITY_Claude Commands|Claude Commands]]
- [[_COMMUNITY_Read B2b|Read B2b]]
- [[_COMMUNITY_Fix Users|Fix Users]]
- [[_COMMUNITY_Security Hardening|Security Hardening]]
- [[_COMMUNITY_Revenuecat Webhook|Revenuecat Webhook]]
- [[_COMMUNITY_Refactor Children|Refactor Children]]
- [[_COMMUNITY_Dockerfile Prod|Dockerfile Prod]]
- [[_COMMUNITY_Architecture Overview|Architecture Overview]]
- [[_COMMUNITY_Rate Limiting|Rate Limiting]]
- [[_COMMUNITY_Anatomy Nestjs|Anatomy Nestjs]]
- [[_COMMUNITY_Typescript Guidelines|Typescript Guidelines]]
- [[_COMMUNITY_Revenuecat Testing|Revenuecat Testing]]
- [[_COMMUNITY_Root Vps|Root Vps]]
- [[_COMMUNITY_Auth Api|Auth Api]]
- [[_COMMUNITY_Drizzle Relations|Drizzle Relations]]
- [[_COMMUNITY_Gemini Provider|Gemini Provider]]
- [[_COMMUNITY_Botblocker Blocker|Botblocker Blocker]]
- [[_COMMUNITY_Rate Limiter|Rate Limiter]]
- [[_COMMUNITY_Family Role|Family Role]]
- [[_COMMUNITY_Admin Decorator|Admin Decorator]]
- [[_COMMUNITY_Drizzle Config|Drizzle Config]]
- [[_COMMUNITY_E2e|E2e]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Subscription History|Subscription History]]
- [[_COMMUNITY_Subscriptions|Subscriptions]]
- [[_COMMUNITY_Sessions|Sessions]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Helmet Middleware|Helmet Middleware]]
- [[_COMMUNITY_Current User|Current User]]
- [[_COMMUNITY_Auth Provider|Auth Provider]]
- [[_COMMUNITY_Backend Jwt|Backend Jwt]]
- [[_COMMUNITY_Dimension Identity|Dimension Identity]]
- [[_COMMUNITY_Dimension Invitation|Dimension Invitation]]
- [[_COMMUNITY_Dimension Coach|Dimension Coach]]
- [[_COMMUNITY_Dimension Subscription|Dimension Subscription]]
- [[_COMMUNITY_Cross Dimension|Cross Dimension]]

## God Nodes (most connected - your core abstractions)
1. `AuthService` - 16 edges
2. `AuthController` - 13 edges
3. `FamiliesService` - 13 edges
4. `FamiliesController` - 13 edges
5. `SubscriptionEventHandler` - 10 edges
6. `SupabaseAuthProvider` - 8 edges
7. `ChildrenService` - 8 edges
8. `FamilyMembershipService` - 7 edges
9. `WeightService` - 7 edges
10. `SleepService` - 7 edges

## Surprising Connections (you probably didn't know these)
- `Firm Billing Strategies` --semantically_similar_to--> `Dimension 8 Firm Billing And Reporting`  [INFERRED] [semantically similar]
  backend/docs/firm-billing-strategies.md → backend/uml-diagrams/b2b-firms/dimension-8-firm-billing-and-reporting.pdf
- `Dimension 2 Firm Family` --semantically_similar_to--> `Dimension 8 Firm Billing And Reporting`  [INFERRED] [semantically similar]
  backend/uml-diagrams/b2b-firms/dimension-2-firm-family.pdf → backend/uml-diagrams/b2b-firms/dimension-8-firm-billing-and-reporting.pdf
- `Dimension 2 Firm Family` --semantically_similar_to--> `Dimension 1 User Firm`  [INFERRED] [semantically similar]
  backend/uml-diagrams/b2b-firms/dimension-2-firm-family.pdf → backend/uml-diagrams/b2b-firms/dimension-1-user-firm.pdf
- `Dimension 2 Firm Family` --semantically_similar_to--> `Dimension 3 Firm Child`  [INFERRED] [semantically similar]
  backend/uml-diagrams/b2b-firms/dimension-2-firm-family.pdf → backend/uml-diagrams/b2b-firms/dimension-3-firm-child.pdf
- `Dimension 8 Firm Billing And Reporting` --semantically_similar_to--> `Dimension 1 User Firm`  [INFERRED] [semantically similar]
  backend/uml-diagrams/b2b-firms/dimension-8-firm-billing-and-reporting.pdf → backend/uml-diagrams/b2b-firms/dimension-1-user-firm.pdf

## Hyperedges (group relationships)
- **docs knowledge group** — dockerfile_prod_explained_md, architecture_md, rate_limiting_deep_dive_md, firm_billing_strategies_md, nestjs_module_anatomy_md, typescript_guidelines_md, revenuecat_testing_md, vps_security_setup_md [INFERRED 0.70]
- **b2b-firms knowledge group** — dimension_2_firm_family_pdf, dimension_5_identity_pdf, dimension_8_firm_billing_and_reporting_pdf, dimension_1_user_firm_pdf, dimension_3_firm_child_pdf, dimension_7_invitation_pdf, dimension_4_coach_access_pdf, dimension_6_subscription_pdf [INFERRED 0.70]
- **plans knowledge group** — b2b_firms_md, fix_session_refresh_logout_md, security_hardening_md, revenuecat_webhook_module_md, refactor_children_sleep_weight_md [INFERRED 0.70]

## Communities

### Community 0 - "Constructor Gethello"
Cohesion: 0.05
Nodes (9): AllExceptionsFilter, AppController, AppModule, AppService, EnvironmentVariables, GrowthDataController, GrowthDataModule, HealthController (+1 more)

### Community 1 - "Nestjs Decorators"
Cohesion: 0.06
Nodes (0): 

### Community 2 - "Children Create"
Cohesion: 0.08
Nodes (6): ChildrenController, ChildrenModule, ChildrenService, CreateChildDto, FamilyChildrenController, UpdateChildDto

### Community 3 - "Create Family"
Cohesion: 0.07
Nodes (7): AcceptInvitationDto, CreateFamilyDto, CreateInvitationDto, FamiliesController, FamiliesModule, UpdateFamilyDto, UpdateMemberRoleDto

### Community 4 - "Weight Create"
Cohesion: 0.09
Nodes (6): ChildWeightController, CreateWeightDto, UpdateWeightDto, WeightController, WeightModule, WeightService

### Community 5 - "Sleep Create"
Cohesion: 0.09
Nodes (6): ChildSleepController, CreateSleepDto, SleepController, SleepModule, SleepService, UpdateSleepDto

### Community 6 - "Subscriptions Constructor"
Cohesion: 0.08
Nodes (4): SubscriptionEventHandler, SubscriptionsController, SubscriptionsModule, SubscriptionsService

### Community 7 - "Auth Oauth"
Cohesion: 0.09
Nodes (6): AuthModule, OAuthCallbackDto, OAuthUrlDto, SignInDto, SignUpDto, SupabaseAuthProvider

### Community 8 - "Guard Canactivate"
Cohesion: 0.11
Nodes (5): ChildAccessGuard, CommonModule, FamilyRoleGuard, SleepAccessGuard, WeightAccessGuard

### Community 9 - "Coach Chat"
Cohesion: 0.16
Nodes (4): AiCoachController, AiCoachModule, AiCoachService, ChatDto

### Community 10 - "Authservice Constructor"
Cohesion: 0.19
Nodes (1): AuthService

### Community 11 - "Database Constructor"
Cohesion: 0.14
Nodes (3): DatabaseModule, DatabaseService, DrizzleProvider

### Community 12 - "Authcontroller Constructor"
Cohesion: 0.21
Nodes (1): AuthController

### Community 13 - "Familiesservice Acceptinvitation"
Cohesion: 0.18
Nodes (1): FamiliesService

### Community 14 - "Family Children"
Cohesion: 0.42
Nodes (0): 

### Community 15 - "Firm Dimension"
Cohesion: 0.36
Nodes (8): Dimension 1 User Firm, Dimension 2 Firm Family, Dimension 3 Firm Child, Dimension 8 Firm Billing And Reporting, 1. Why this document exists, 2. Evaluation axes, Firm billing strategies — research brief, Firm Billing Strategies

### Community 16 - "Familymembershipservice Assertchildaccess"
Cohesion: 0.57
Nodes (1): FamilyMembershipService

### Community 17 - "Backendauthguard Canactivate"
Cohesion: 0.5
Nodes (1): BackendAuthGuard

### Community 18 - "Adminguard Canactivate"
Cohesion: 0.5
Nodes (1): AdminGuard

### Community 19 - "Project Rules"
Cohesion: 0.5
Nodes (4): General Instructions, Project Rules, Persona, Project Rules & Context

### Community 20 - "Project Context"
Cohesion: 0.5
Nodes (4): 1. Project Overview, 2. Tech Stack, Context, Project Context: Sleepyhead AI Backend

### Community 21 - "Getting Started"
Cohesion: 0.5
Nodes (4): Getting Started with Docker, Readme, Prerequisites, Sleepyhead AI Backend

### Community 22 - "Claude Commands"
Cohesion: 0.5
Nodes (3): Commands, Claude, Project

### Community 23 - "Read B2b"
Cohesion: 0.5
Nodes (4): ⚠️ BRAINSTORM FLAG — BILLING (read this when you re-read the plan), Context, Introduce B2B `firms` multi-tenant layer (sleep-coaching marketplace), B2b Firms

### Community 24 - "Fix Users"
Cohesion: 0.5
Nodes (4): Fix: Users getting logged out every ~10 minutes, Fix Session Refresh Logout, Problem, Root Causes Found

### Community 25 - "Security Hardening"
Cohesion: 0.5
Nodes (4): Context, Security Hardening, Phase 1 — CRITICAL (Before Production), Security Hardening — Project Code (Do Now)

### Community 26 - "Revenuecat Webhook"
Cohesion: 0.5
Nodes (4): Architecture Overview, Context, Revenuecat Webhook Module, Plan: Reusable NestJS RevenueCat Webhook Module

### Community 27 - "Refactor Children"
Cohesion: 0.5
Nodes (4): Context, Refactor Children Sleep Weight, Refactor: flatten children / sleep / weight, Target routes

### Community 28 - "Dockerfile Prod"
Cohesion: 0.5
Nodes (4): Dockerfile.prod — Line-by-Line Explanation, Dockerfile Prod Explained, Stage 1: Builder, What is a Multi-Stage Build?

### Community 29 - "Architecture Overview"
Cohesion: 0.5
Nodes (4): Architecture Overview, Architecture, Sleepyhead AI — Architecture, What the NestJS backend handles

### Community 30 - "Rate Limiting"
Cohesion: 0.5
Nodes (4): Rate Limiting Deep Dive, Problem 1 — `authLimiter` and `apiLimiter` Were Never Applied, Rate Limiting — Why It Wasn't Working and How It Was Fixed, The Starting Point — What the Code Looked Like Originally

### Community 31 - "Anatomy Nestjs"
Cohesion: 0.5
Nodes (4): Anatomy of a NestJS Module, Breaking Down `AuthModule`, Nestjs Module Anatomy, The Decorator

### Community 32 - "Typescript Guidelines"
Cohesion: 0.5
Nodes (4): Typescript Guidelines, NestJS-Specific, Strict Rules, TypeScript Guidelines

### Community 33 - "Revenuecat Testing"
Cohesion: 0.5
Nodes (4): Endpoint, Revenuecat Testing, Payload shape, Testing RevenueCat Webhook Events Locally

### Community 34 - "Root Vps"
Cohesion: 0.5
Nodes (4): Connect as root first, Vps Security Setup, Step 1: Create a Deploy User (don't work as root), VPS Security Setup Guide

### Community 35 - "Auth Api"
Cohesion: 0.5
Nodes (4): Auth API Reference, Endpoints, Auth Api, OAuth Mobile Flow

### Community 36 - "Drizzle Relations"
Cohesion: 0.5
Nodes (4): Drizzle ORM Relations in NestJS, Drizzle Relations, Overview, Relation Types

### Community 37 - "Gemini Provider"
Cohesion: 0.67
Nodes (1): GeminiModule

### Community 38 - "Botblocker Blocker"
Cohesion: 1.0
Nodes (0): 

### Community 39 - "Rate Limiter"
Cohesion: 1.0
Nodes (0): 

### Community 40 - "Family Role"
Cohesion: 1.0
Nodes (0): 

### Community 41 - "Admin Decorator"
Cohesion: 1.0
Nodes (0): 

### Community 42 - "Drizzle Config"
Cohesion: 1.0
Nodes (0): 

### Community 43 - "E2e"
Cohesion: 1.0
Nodes (0): 

### Community 44 - "Community 44"
Cohesion: 1.0
Nodes (0): 

### Community 45 - "Subscription History"
Cohesion: 1.0
Nodes (0): 

### Community 46 - "Subscriptions"
Cohesion: 1.0
Nodes (0): 

### Community 47 - "Sessions"
Cohesion: 1.0
Nodes (0): 

### Community 48 - "Community 48"
Cohesion: 1.0
Nodes (0): 

### Community 49 - "Helmet Middleware"
Cohesion: 1.0
Nodes (0): 

### Community 50 - "Current User"
Cohesion: 1.0
Nodes (0): 

### Community 51 - "Auth Provider"
Cohesion: 1.0
Nodes (0): 

### Community 52 - "Backend Jwt"
Cohesion: 1.0
Nodes (0): 

### Community 53 - "Dimension Identity"
Cohesion: 1.0
Nodes (1): Dimension 5 Identity

### Community 54 - "Dimension Invitation"
Cohesion: 1.0
Nodes (1): Dimension 7 Invitation

### Community 55 - "Dimension Coach"
Cohesion: 1.0
Nodes (1): Dimension 4 Coach Access

### Community 56 - "Dimension Subscription"
Cohesion: 1.0
Nodes (1): Dimension 6 Subscription

### Community 57 - "Cross Dimension"
Cohesion: 1.0
Nodes (1): Cross Dimension Recommended Model

## Knowledge Gaps
- **90 isolated node(s):** `AppModule`, `DatabaseModule`, `GeminiModule`, `EnvironmentVariables`, `CommonModule` (+85 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Botblocker Blocker`** (2 nodes): `botBlocker()`, `ai-blocker.middleware.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Rate Limiter`** (2 nodes): `rate-limiter.middleware.ts`, `makeStore()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Family Role`** (2 nodes): `family-role.decorator.ts`, `FamilyRoles()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Admin Decorator`** (2 nodes): `Admin()`, `admin.decorator.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Drizzle Config`** (1 nodes): `drizzle.config.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `E2e`** (1 nodes): `app.e2e-spec.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 44`** (1 nodes): `app.controller.spec.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Subscription History`** (1 nodes): `subscription-history.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Subscriptions`** (1 nodes): `subscriptions.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Sessions`** (1 nodes): `sessions.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 48`** (1 nodes): `index.d.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Helmet Middleware`** (1 nodes): `helmet.middleware.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Current User`** (1 nodes): `current-user.decorator.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Auth Provider`** (1 nodes): `auth-provider.interface.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Backend Jwt`** (1 nodes): `backend-jwt-payload.interface.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Dimension Identity`** (1 nodes): `Dimension 5 Identity`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Dimension Invitation`** (1 nodes): `Dimension 7 Invitation`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Dimension Coach`** (1 nodes): `Dimension 4 Coach Access`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Dimension Subscription`** (1 nodes): `Dimension 6 Subscription`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Cross Dimension`** (1 nodes): `Cross Dimension Recommended Model`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `AuthService` connect `Authservice Constructor` to `Auth Oauth`?**
  _High betweenness centrality (0.042) - this node is a cross-community bridge._
- **Why does `FamiliesService` connect `Familiesservice Acceptinvitation` to `Create Family`?**
  _High betweenness centrality (0.034) - this node is a cross-community bridge._
- **What connects `AppModule`, `DatabaseModule`, `GeminiModule` to the rest of the system?**
  _90 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Constructor Gethello` be split into smaller, more focused modules?**
  _Cohesion score 0.05 - nodes in this community are weakly interconnected._
- **Should `Nestjs Decorators` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Children Create` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._
- **Should `Create Family` be split into smaller, more focused modules?**
  _Cohesion score 0.07 - nodes in this community are weakly interconnected._