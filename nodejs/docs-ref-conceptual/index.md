---
title: Microsoft Teams SDK for TypeScript Reference
description: Reference documentation for Microsoft Teams SDK for TypeScript.
ms.date: 09/08/2026
author: nickwalkmsft
ms.author: nickwalk
ms.reviewer: nickwalk
ms.topic: reference
---

# Teams SDK for TypeScript

**Current version: 2.0.16**, released 9/4/2026 ([release notes](https://github.com/microsoft/teams.ts/releases/tag/v2.0.16))

**Preview version: 2.1.0-preview.3**, released 8/4/2026 ([release notes](https://github.com/microsoft/teams.ts/releases/tag/v2.1.0-preview.3))

Report issues and explore the source on [GitHub](https://github.com/microsoft/teams.ts).

## npm packages

| Package                               | npmjs    | Description                                                                                                                                                                                                                                                                        |
|---------------------------------------|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| @microsoft/teams.api                  | [Current](https://www.npmjs.com/package/@microsoft/teams.api/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.api/v/2.1.0-preview.3) | Core types and client implementation for the Teams Platform API. Used for fetching data, authentication, and sending activities.                                                                                                                                                   |
| @microsoft/teams.apps                 | [Current](https://www.npmjs.com/package/@microsoft/teams.apps/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.apps/v/2.1.0-preview.3) | Tools for building server side apps for Microsoft Teams.                                                                                                                                                                                                                           |
| @microsoft/teams.botbuilder           | [Current](https://www.npmjs.com/package/@microsoft/teams.botbuilder/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.botbuilder/v/2.1.0-preview.3) | A plugin implementation, allowing developers to integrate an existing botbuilder Adapter into a project using Teams. This plugin allows you to use botbuilder as the Sender and Receiver of activities, while still being able to leverage Teams's new typings and routing system. |
| @microsoft/teams.cards                | [Current](https://www.npmjs.com/package/@microsoft/teams.cards/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.cards/v/2.1.0-preview.3) | Adaptive Cards typings and builders for type safe and intuitive card design.                                                                                                                                                                                                       |
| @microsoft/teams.client               | [Current](https://www.npmjs.com/package/@microsoft/teams.client/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.client/v/2.1.0-preview.3) | A client used to create app/bot surfaces such as tabs using @microsoft/teams.ts.                                                                                                                                                                                                   |
| @microsoft/teams.common               | [Current](https://www.npmjs.com/package/@microsoft/teams.common/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.common/v/2.1.0-preview.3) | Common implementations used by all the packages, for example logging.                                                                                                                                                                                                              |
| @microsoft/teams.graph                | [Current](https://www.npmjs.com/package/@microsoft/teams.graph/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.graph/v/2.1.0-preview.3) | Microsoft Graph API client.                                                                                                                                                                                                                                                        |
| @microsoft/teams.graph-endpoints      | [Current](https://www.npmjs.com/package/@microsoft/teams.graph-endpoints/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.graph-endpoints/v/2.1.0-preview.3) | A collection of strongly typed request configuration builders for Microsoft Graph endpoints, designed to be used together with @microsoft/teams.graph.                                                                                                                             |
| @microsoft/teams.graph-endpoints-beta | [Current](https://www.npmjs.com/package/@microsoft/teams.graph-endpoints-beta/v/2.0.16),  [Preview](https://www.npmjs.com/package/@microsoft/teams.graph-endpoints-beta/v/2.1.0-preview.3) | A collection of strongly typed request configuration builders for Microsoft Graph preview endpoints, designed to be used together with @microsoft/teams.graph.                                                                                                                     |