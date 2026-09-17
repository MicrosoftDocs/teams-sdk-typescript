---
title: Microsoft Teams SDK for TypeScript Reference
description: Reference documentation for Microsoft Teams SDK for TypeScript.
ms.date: 09/17/2026
author: nickwalkmsft
ms.author: nickwalk
ms.reviewer: nickwalk
ms.topic: reference
---

# Teams SDK for TypeScript reference

**Current version: 2.1.0**, released September 16 2026 ([release notes](https://github.com/microsoft/teams.ts/releases/tag/v2.1.0))

Report issues and explore the source on [GitHub](https://github.com/microsoft/teams.ts).

## npm packages

| Package                               | npmjs                                                              | Description                                                                                                                                                                                                                                                                        |
|---------------------------------------|--------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| @microsoft/teams.api                  | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.api/v/2.1.0) | Core types and client implementation for the Teams Platform API. Used for fetching data, authentication, and sending activities.                                                                                                                                                   |
| @microsoft/teams.apps                 | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.apps/v/2.1.0) | Tools for building server side apps for Microsoft Teams.                                                                                                                                                                                                                           |
| @microsoft/teams.botbuilder           | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.botbuilder/v/2.1.0) | A plugin implementation, allowing developers to integrate an existing botbuilder Adapter into a project using Teams. This plugin allows you to use botbuilder as the Sender and Receiver of activities, while still being able to leverage Teams's new typings and routing system. |
| @microsoft/teams.cards                | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.cards/v/2.1.0) | Adaptive Cards typings and builders for type safe and intuitive card design.                                                                                                                                                                                                       |
| @microsoft/teams.client               | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.client/v/2.1.0) | A client used to create app/bot surfaces such as tabs using @microsoft/teams.ts.                                                                                                                                                                                                   |
| @microsoft/teams.common               | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.common/v/2.1.0) | Common implementations used by all the packages, for example logging.                                                                                                                                                                                                              |
| @microsoft/teams.graph                | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.graph/v/2.1.0) | Microsoft Graph API client.                                                                                                                                                                                                                                                        |
| @microsoft/teams.graph-endpoints      | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.graph-endpoints/v/2.1.0) | A collection of strongly typed request configuration builders for Microsoft Graph endpoints, designed to be used together with @microsoft/teams.graph.                                                                                                                             |
| @microsoft/teams.graph-endpoints-beta | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.graph-endpoints-beta/v/2.1.0) | A collection of strongly typed request configuration builders for Microsoft Graph preview endpoints, designed to be used together with @microsoft/teams.graph.                                                                                                                     |
| @microsoft/teams.m365extensions       | [2.1.0](https://www.npmjs.com/package/@microsoft/teams.m365extensions/v/2.1.0) | Extensions for integrating Teams SDK routing into Microsoft 365 Agents SDK apps.                                                                                                                                                                                                   |