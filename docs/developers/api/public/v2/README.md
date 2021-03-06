---
title: "Public 2.0"
---

# Introduction

This describes the resources that make up the official Public API v2. If you have any problems or requests please [open an issue](https://github.com/ArkEcosystem/core/issues/new/choose).

## Current version

By default, all requests to a relay receive the v1 version of the Public API. We encourage you to explicitly request this version via the `API-Version` header.

## Pagination

Requests that return multiple items will be paginated to 100 items by default. You can specify further pages with the `?page` parameter. For some resources, you can also set a custom page size up to 100 with the `?limit` parameter. Note that for technical reasons not all endpoints respect the `?limit` parameter.

## Public Testing Relay

::: tip
Currently there is no public relay available for the Public API v2 as it currently is under development.
:::
