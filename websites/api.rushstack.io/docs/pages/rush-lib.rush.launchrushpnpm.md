---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [Rush](./rush-lib.rush.md) &gt; [launchRushPnpm](./rush-lib.rush.launchrushpnpm.md)

## Rush.launchRushPnpm() method

This API is used by the `@microsoft/rush` front end to launch the "rush-pnpm" command-line. Third-party tools should not use this API. Instead, they should execute the "rush-pnpm" binary and start a new Node.js process.

**Signature:**

```typescript
static launchRushPnpm(launcherVersion: string, options: ILaunchOptions): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  launcherVersion | string |  |
|  options | [ILaunchOptions](./rush-lib.ilaunchoptions.md) |  |

**Returns:**

void
