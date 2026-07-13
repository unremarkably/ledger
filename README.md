# Ivory Lion Ledger Sync — plugin repo

This repo hosts the built plugin for the Ivory Lion Trading Co. Ledger. It's
a custom Dalamud plugin repository, not the plugin's source code.

## Installing

1. In-game, open `/xlsettings` → **Experimental** → **Custom Plugin
   Repositories**, and add:

   ```
   https://raw.githubusercontent.com/unremarkably/ledger/main/pluginmaster.json
   ```

2. Save, then go to `/xlplugins` and search for **Ivory Lion Ledger Sync**.
   Install it like any other plugin.
3. `/ledger` in-game → set the server URL → sign in with your Ledger
   account. Only the sync token is stored, never your password.

Updates happen automatically the same way as any other Dalamud plugin —
Dalamud checks this repo periodically and offers the update in
`/xlplugins`.
