<!-- NXCodes: Addon skeleton readme · @copyright 2026 One Man's Junk Games -->

# NXCodes Addon Skeleton

A starting point for building an NXCodes addon. Click **Use this template** to create your own addon repository.

> ⚠️ NXCodes is in development. The addon API (manifest format, hooks, UI kit) is still being designed and **will change** before 1.0. This template tracks the current draft.

## Layout

```
addon.json            ← manifest: id, version, engine compatibility, requirements
src/                  ← PHP, namespace Addons\<Vendor>\<Name>\
database/migrations/  ← your tables
resources/views/      ← Blade views (use the NXCodes UI kit components)
resources/phrases.json
Setup/                ← Install, Upgrade_x_y_z, Uninstall steps
```

Zip the folder and upload it in the NXCodes staff panel under **Addons → Upload**.
