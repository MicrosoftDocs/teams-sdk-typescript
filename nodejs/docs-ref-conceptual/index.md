---
title: Microsoft Teams AI Library v2 Reference (TypeScript)
description: TypeScript reference documentation for Microsoft Teams AI Library version 2.
ms.date: 05/15/2025
ms.topic: reference
keywords: sdk msteams teams ai javascript typescript library reference latest
---

# Microsoft Teams AI Library v2 Reference (TypeScript)

The Microsoft Teams AI Library v2 provides a Teams-centric interface for integrating GPT-based language models and user intent engines. It simplifies the development process by reducing the need to write and maintain complex conversational bot logic. You can leverage prebuilt, reusable code snippets that allow you to quickly build intelligent apps. This capabilities-driven approach allows you to focus on business logic rather than learning the intricacies of Microsoft Teams conversational frameworks.

## Finding the library

For more about the TypeScript version of Teams AI Library v2, refer to the source repo at [Teams SDK: TypeScript](https://github.com/microsoft/teams.ts).

For more about the .NET version of Teams AI Library v2, refer to the source repo at [Teams SDK: DotNet](https://github.com/microsoft/teams.net).

### Library packages

The TypeScript version of the library is provided through a suite of packages available via [npm](https://docs.npmjs.com/about-npm). Those packages are:

| Package  | Description  |
|---------|---------|
| [@microsoft/teams.apps](https://www.npmjs.com/package/@microsoft/teams.apps)       | Tools for building server side apps for Microsoft Teams. |
| [@microsoft/teams.api](https://www.npmjs.com/package/@microsoft/teams.api)        | Core types and client implementation for the Teams Platform API. Used for fetching data, authentication, and sending activities.        |
| [@microsoft/teams.ai](https://www.npmjs.com/package/@microsoft/teams.ai)         | Tools to facilitate integrating apps with LLM's and enabling multi-agent scenarios.        |
| [@microsoft/teams.botbuilder](https://www.npmjs.com/package/@microsoft/teams.botbuilder) | A plugin implementation, allowing developers to integrate an existing `botbuilder Adapter` into a project using Teams. This plugin allows you to use `botbuilder` as the `Sender` and `Receiver` of activities, while still being able to leverage Teams's new typings and routing system.        |
| [@microsoft/teams.cards](https://www.npmjs.com/package/@microsoft/teams.cards)      | Adaptive Cards typings and builders for type safe and intuitive card design.        |
| [@microsoft/teams.cli](https://www.npmjs.com/package/@microsoft/teams.cli)        | A CLI for building apps using `@microsoft/teams.ts`.        |
| [@microsoft/teams.client](https://www.npmjs.com/package/@microsoft/teams.client)     | A client used to create app/bot surfaces such as tabs using `@microsoft/teams.ts`.        |
| [@microsoft/teams.common](https://www.npmjs.com/package/@microsoft/teams.common)    | Common implementations used by all the packages, for example `logging`.        |
| [@microsoft/teams.dev](https://www.npmjs.com/package/@microsoft/teams.dev)        | Developer tools to streamline the development process.        |
| [@microsoft/teams.graph](https://www.npmjs.com/package/@microsoft/teams.graph)      | MSGraph api client.  |
| [@microsoft/teams.openai](https://www.npmjs.com/package/@microsoft/teams.openai)     | AI model implementations for **OpenAI**, allowing you to integrate your models with the core `@microsoft/teams.ai` package.        |
