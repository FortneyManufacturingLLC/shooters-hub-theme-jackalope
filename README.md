# Jackalope child-site theme

MIT-licensed presentation code for [Shooters Hub child sites](https://github.com/FortneyManufacturingLLC/shooters-hub-child-sites). Version 0.1.0, manifest protocol 1.

Extends the [Classic parent theme](https://github.com/FortneyManufacturingLLC/shooters-hub-theme-classic). Forest, cream and orange with rail navigation on large screens. No brand artwork is distributed.

## Use

Clone the framework and theme repositories beside one another. Run its build with one `--theme` argument per parent/child, in inheritance order. The framework README provides the complete commands and hosting setup. Pin reviewed commits for releases.

## Customize safely

Fork this theme or create a child manifest whose `parent` is this theme ID. Presentation tokens/layout may change; community scope, providers, credentials and permissions cannot be overridden by themes. Keep licensed deployment artwork under `/assets/` and bind its paths through site configuration. See ASSETS.md.

## Current scope

This is presentation, not the Hub backend, auth service or MatchOps. Canonical Hub entity-page integration is still planned. Do not add independent scoring or account engines to a theme.
