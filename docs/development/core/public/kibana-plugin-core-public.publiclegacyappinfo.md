<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-core-public](./kibana-plugin-core-public.md) &gt; [PublicLegacyAppInfo](./kibana-plugin-core-public.publiclegacyappinfo.md)

## PublicLegacyAppInfo type

Information about a registered [legacy application](./kibana-plugin-core-public.legacyapp.md)

<b>Signature:</b>

```typescript
export declare type PublicLegacyAppInfo = Omit<LegacyApp, 'updater$'> & {
    legacy: true;
    status: AppStatus;
    navLinkStatus: AppNavLinkStatus;
};
```
