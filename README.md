# Reproduction
This is a reproduction highlighting the issues of Storybook Nuxt with a fresh install

# Terminal output when installing Storybook Nuxt
```
@robigan ➜ /workspaces/repro-fresh-install-storybook-nuxt (main) $ yarn dlx storybook@latest init
➤ YN0000: · Yarn 4.9.2
➤ YN0000: ┌ Resolution step
➤ YN0085: │ + storybook@npm:9.0.13, @adobe/css-tools@npm:4.4.3, @esbuild/aix-ppc64@npm:0.25.5, and 70 more.
➤ YN0000: └ Completed in 0s 631ms
➤ YN0000: ┌ Post-resolution validation
➤ YN0086: │ Some peer dependencies are incorrectly met by dependencies; run yarn explain peer-requirements for details.
➤ YN0000: └ Completed
➤ YN0000: ┌ Fetch step
➤ YN0013: │ 49 packages were added to the project (+ 47.26 MiB).
➤ YN0000: └ Completed in 1s 232ms
➤ YN0000: ┌ Link step
➤ YN0007: │ esbuild@npm:0.25.5 must be built because it never has been before or the last one failed
➤ YN0000: └ Completed in 0s 806ms
➤ YN0000: · Done with warnings in 2s 695ms

info Installing dependencies...
info 
info ➤ YN0000: · Yarn 4.9.2
info ➤ YN0000: ┌ Resolution step
info ➤ YN0000: └ Completed in 0s 360ms
info ➤ YN0000: ┌ Post-resolution validation
info ➤ YN0086: │ Some peer dependencies are incorrectly met by dependencies; run yarn
info explain peer-requirements for details.
info ➤ YN0000: └ Completed
info ➤ YN0000: ┌ Fetch step
info ➤ YN0000: └ Completed in 1s 258ms
info ➤ YN0000: ┌ Link step
info ➤ YN0000: └ Completed in 0s 321ms
info ➤ YN0000: · Done with warnings in 2s 106ms
info Dependencies installed
╭───────────────────────────────────────────────────────╮
│                                                       │
│   Adding Storybook version 9.0.13 to your project..   │
│                                                       │
╰───────────────────────────────────────────────────────╯
✔ New to Storybook? › Yes: Help me with onboarding
Attention: Storybook now collects completely anonymous telemetry regarding usage. This information is used to shape Storybook's roadmap and prioritize features.
You can learn more, including how to opt-out if you'd not like to participate in this anonymous program, by visiting the following URL:
https://storybook.js.org/telemetry

 • Detecting project type. ✓
 • Adding Storybook support to your "Nuxt" app
  ✅ Getting the correct version of 4 packages
  ⠦ Installing Storybook dependencies➤ YN0000: · Yarn 4.9.2
➤ YN0000: ┌ Resolution step
➤ YN0000: ⠏ asap@npm:~2.0.3          ➤ YN0085: │ + @chromatic-com/storybook@npm:4.0.1, @nuxtjs/storybook@npm:8.4.1, @storybook/addon-docs@npm:9.0.13, and 108 more.
➤ YN0000: └ Completed in 2s 806ms
➤ YN0000: ┌ Post-resolution validation
➤ YN0060: │ storybook is listed by your project with version 9.0.13 (p53a38), which doesn't satisfy what @nuxtjs/storybook and other dependencies request (but they have non-overlapping ranges!).
➤ YN0086: │ Some peer dependencies are incorrectly met by your project; run yarn explain peer-requirements <hash> for details, where <hash> is the six-letter p-prefixed code.
➤ YN0086: │ Some peer dependencies are incorrectly met by dependencies; run yarn explain peer-requirements for details.
➤ YN0000: └ Completed
➤ YN0000: ┌ Fetch step
➤ YN0000: ⠸ ===----------------------➤ YN0000: ⠸ ====---------------------------------------------------------------------------➤ YN0000: ⠼ =========----------------➤ YN0000: ⠼ ==========---------------------------------------------------------------------➤ YN0000: ⠴ =============------------➤ YN0000: ⠴ ==============-----------------------------------------------------------------➤ YN0000: ⠴ ===============----------➤ YN0000: ⠦ ================---------------------------------------------------------------➤ YN0000: ⠦ =================--------➤ YN0000: ⠧ ==================-------------------------------------------------------------➤ YN0000: ⠧ ===================------➤ YN0000: ⠧ ====================-----------------------------------------------------------➤ YN0000: ⠇ =====================----➤ YN0000: ⠇ ======================---------------------------------------------------------➤ YN0000: ⠇ ========================-➤ YN0000: ⠏ =========================------------------------------------------------------➤ YN0000: ⠏ =========================➤ YN0000: ⠋ ===============================------------------------------------------------- ⠋ Installing Storybook dependencies➤ YN0000: ⠙ ===============================------------------------------------------------➤ YN0000: ⠙ =========================➤ YN0000: ⠙ =================================----------------------------------------------➤ YN0000: ⠹ =========================➤ YN0000: ⠹ =========================================--------------------------------------➤ YN0000: ⠸ =========================➤ YN0000: ⠸ ===============================================--------------------------------➤ YN0000: ⠼ =========================➤ YN0000: ⠼ ====================================================---------------------------➤ YN0000: ⠴ =========================➤ YN0000: ⠴ ===========================================================--------------------➤ YN0000: ⠴ =========================➤ YN0000: ⠦ ===============================================================----------------➤ YN0000: ⠦ =========================➤ YN0000: ⠦ ==================================================================-------------➤ YN0000: ⠧ =========================➤ YN0000: ⠧ ======================================================================---------➤ YN0000: ⠇ =========================➤ YN0000: ⠏ ==========================================================================-----➤ YN0000: ⠏ =========================➤ YN0000: ⠏ ==============================================================================-➤ YN0000: ⠋ =========================➤ YN0000: ⠋ ===============================================================================- ⠹ Installing Storybook dependencies➤ YN0000: ⠙ ===============================================================================- ⠸ Installing Storybook dependencies➤ YN0000: ⠙ ===============================================================================
➤ YN0013: │ 80 packages were added to the project (+ 22.4 MiB).
➤ YN0000: └ Completed in 1s 870ms
  ⠴ Installing Storybook dependencies➤ YN0000: ┌ Link step
  ⠼ Installing Storybook dependencies➤ YN0000: ⠹ -------------------------------------------------------------------------------➤ YN0000: ⠹ ===----------------------➤ YN0000: ⠸ ===----------------------------------------------------------------------------
  ⠦ Installing Storybook dependencies➤ YN0000: ⠸ =====--------------------------------------------------------------------------➤ YN0000: ⠼ =======------------------➤ YN0000: ⠼ ========-----------------------------------------------------------------------➤ YN0000: ⠴ ==========---------------➤ YN0000: ⠦ ==========---------------------------------------------------------------------- ⠇ Installing Storybook dependencies➤ YN0000: ⠦ ===========--------------------------------------------------------------------➤ YN0000: ⠦ =============------------➤ YN0000: ⠧ ==============-----------------------------------------------------------------➤ YN0000: ⠧ ================---------➤ YN0000: ⠇ =================--------------------------------------------------------------- ⠙ Installing Storybook dependencies➤ YN0000: ⠏ =================--------------------------------------------------------------➤ YN0000: ⠏ ===================------➤ YN0000: ⠏ ====================-----------------------------------------------------------➤ YN0000: ⠋ =======================--➤ YN0000: ⠋ ========================-------------------------------------------------------➤ YN0000: ⠙ =========================➤ YN0000: ⠹ ============================---------------------------------------------------➤ YN0000: ⠹ =========================➤ YN0000: ⠹ ==============================-------------------------------------------------➤ YN0000: ⠸ =========================➤ YN0000: ⠸ ========================================---------------------------------------➤ YN0000: ⠼ =========================➤ YN0000: ⠼ ============================================-----------------------------------➤ YN0000: ⠴ =========================➤ YN0000: ⠴ ================================================-------------------------------➤ YN0000: ⠦ =========================➤ YN0000: ⠦ ======================================================-------------------------➤ YN0000: ⠧ =========================➤ YN0000: ⠧ ==================================================================-------------➤ YN0000: ⠧ =========================➤ YN0000: ⠇ ==========================================================================-----
  ⠴ Installing Storybook dependencies➤ YN0008: │ nuxt-app@workspace:. must be rebuilt because its dependency tree changed
  ⠇ Installing Storybook dependencies➤ YN0000: └ Completed in 6s 701ms
  ⠏ Installing Storybook dependencies➤ YN0000: · Done with warnings in 11s 533ms
  ✅ Installing Storybook dependencies
. ✓
info Installing dependencies...
info 
info ➤ YN0000: · Yarn 4.9.2
info ➤ YN0000: ┌ Resolution step
info ➤ YN0000: └ Completed in 0s 351ms
info ➤ YN0000: ┌ Post-resolution validation
info ➤ YN0060: │ storybook is listed by your project with version 9.0.13 (p53a38),
info which doesn't satisfy what @nuxtjs/storybook and other dependencies request (but
info they have non-overlapping ranges!).
info ➤ YN0086: │ Some peer dependencies are incorrectly met by your project; run yarn
info explain peer-requirements <hash> for details, where <hash> is the six-letter
info p-prefixed code.
info ➤ YN0086: │ Some peer dependencies are incorrectly met by dependencies; run yarn
info explain peer-requirements for details.
info ➤ YN0000: └ Completed
info ➤ YN0000: ┌ Fetch step
info ➤ YN0000: └ Completed in 0s 801ms
info ➤ YN0000: ┌ Link step
info ➤ YN0000: └ Completed in 0s 373ms
info ➤ YN0000: · Done with warnings in 1s 667ms
info Dependencies installed
> npx storybook@9.0.13 add --yes @storybook/addon-a11y@9.0.13
npm WARN deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated rimraf@2.6.3: Rimraf versions prior to v4 are no longer supported
Verifying @storybook/addon-a11y
Installing @storybook/addon-a11y@^9.0.13
➤ YN0000: · Yarn 4.9.2
➤ YN0000: ┌ Resolution step
➤ YN0085: │ + @storybook/addon-a11y@npm:9.0.13, axe-core@npm:4.10.3
➤ YN0000: └ Completed in 1s 521ms
➤ YN0000: ┌ Post-resolution validation
➤ YN0060: │ storybook is listed by your project with version 9.0.13 (p53a38), which doesn't satisfy what @nuxtjs/storybook and other dependencies request (but they have non-overlapping ranges!).
➤ YN0086: │ Some peer dependencies are incorrectly met by your project; run yarn explain peer-requirements <hash> for details, where <hash> is the six-letter p-prefixed code.
➤ YN0086: │ Some peer dependencies are incorrectly met by dependencies; run yarn explain peer-requirements for details.
➤ YN0000: └ Completed
➤ YN0000: ┌ Fetch step
➤ YN0013: │ 2 packages were added to the project (+ 3.15 MiB).
➤ YN0000: └ Completed in 1s 626ms
➤ YN0000: ┌ Link step
➤ YN0008: │ nuxt-app@workspace:. must be rebuilt because its dependency tree changed
➤ YN0000: └ Completed in 9s 65ms
➤ YN0000: · Done with warnings in 12s 360ms
Adding '@storybook/addon-a11y@9.0.13' to the "addons" field in .storybook/main.ts
Running postinstall script for @storybook/addon-a11y
> npx storybook@9.0.13 add --yes @storybook/addon-vitest@9.0.13
Verifying @storybook/addon-vitest
Installing @storybook/addon-vitest@^9.0.13
➤ YN0000: · Yarn 4.9.2
➤ YN0000: ┌ Resolution step
➤ YN0085: │ + @storybook/addon-vitest@npm:9.0.13
➤ YN0000: └ Completed in 1s 588ms
➤ YN0000: ┌ Post-resolution validation
➤ YN0060: │ storybook is listed by your project with version 9.0.13 (p53a38), which doesn't satisfy what @nuxtjs/storybook and other dependencies request (but they have non-overlapping ranges!).
➤ YN0086: │ Some peer dependencies are incorrectly met by your project; run yarn explain peer-requirements <hash> for details, where <hash> is the six-letter p-prefixed code.
➤ YN0086: │ Some peer dependencies are incorrectly met by dependencies; run yarn explain peer-requirements for details.
➤ YN0000: └ Completed
➤ YN0000: ┌ Fetch step
➤ YN0013: │ A package was added to the project (+ 546.03 KiB).
➤ YN0000: └ Completed in 1s 259ms
➤ YN0000: ┌ Link step
➤ YN0008: │ nuxt-app@workspace:. must be rebuilt because its dependency tree changed
➤ YN0000: └ Completed in 4s 508ms
➤ YN0000: · Done with warnings in 7s 640ms
Adding '@storybook/addon-vitest@9.0.13' to the "addons" field in .storybook/main.ts
Running postinstall script for @storybook/addon-vitest

╭ 👋 Howdy! ─────────────────────────────────────────────────────────────────╮
│                                                                            │
│   I'm the installation helper for @storybook/addon-vitest                  │
│                                                                            │
│   Hold on for a moment while I look at your project and get it set up...   │
│                                                                            │
╰────────────────────────────────────────────────────────────────────────────╯

╭ ⛔️ Sorry! ─────────────────────────────────────────────────────────────────────────────────────────────────────────╮
│                                                                                                                     │
│   @storybook/addon-vitest's automated setup failed due to the following package incompatibilities:                  │
│                                                                                                                     │
│   • The addon cannot yet be used with @storybook-vue/nuxt                                                           │
│                                                                                                                     │
│   --------------------------------                                                                                  │
│                                                                                                                     │
│   You can fix these issues and rerun the command to reinstall. If you wish to roll back the installation, remove    │
│   @storybook/addon-vitest from the "addons" array                                                                   │
│   in your main Storybook config file and remove the dependency from your package.json file.                         │
│                                                                                                                     │
│   Please check the documentation for more information about its requirements and installation:                      │
│   https://storybook.js.org/docs/next/writing-tests/integrations/vitest-addon                                        │
│                                                                                                                     │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯

╭──────────────────────────────────────────────────────────────────────────────╮
│                                                                              │
│   Storybook was successfully installed in your project! 🎉                   │
│   Additional features: docs, test                                            │
│                                                                              │
│   To run Storybook manually, run yarn storybook. CTRL+C to stop.             │
│                                                                              │
│   Wanna know more about Storybook? Check out https://storybook.js.org/       │
│   Having trouble or want to chat? Join us at https://discord.gg/storybook/   │
│                                                                              │
╰──────────────────────────────────────────────────────────────────────────────╯

Running Storybook
error: unknown option '--quiet'
npm notice 
npm notice New major version of npm available! 9.8.1 -> 11.4.2
npm notice Changelog: https://github.com/npm/cli/releases/tag/v11.4.2
npm notice Run npm install -g npm@11.4.2 to update!
npm notice
```