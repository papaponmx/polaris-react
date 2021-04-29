# Unreleased changes

Use [the changelog guidelines](https://git.io/polaris-changelog-guidelines) to format new entries. 💜

### Breaking changes

### Enhancements

- Prevented `KeypressListener` attaching/detaching on every render ([#4173](https://github.com/Shopify/polaris-react/pull/4173))
- Added `animated` prop in `ProgressBar` ([#4251](https://github.com/Shopify/polaris-react/pull/4251))
- Added `divider` prop to `Page` component ([#4260](https://github.com/Shopify/polaris-react/pull/4260))
- Add `activator` prop to `Sheet` so the triggering element will regain focus ([#4201](https://github.com/Shopify/polaris-react/pull/4201))
- Rename and expose Card compound components types ([#4261](https://github.com/Shopify/polaris-react/pull/4261))
- Add `monospaced` prop to `TextField` component ([#4264](https://github.com/Shopify/polaris-react/pull/4264))
- Add base tight spacing option to `Stack` component([#4273](https://github.com/Shopify/polaris-react/pull/4273))
- Add `variableHeight` prop to `DropZone` so children control its height ([#4136](https://github.com/Shopify/polaris-react/pull/4136))
- Add print styles to `Card`, `Heading`, `Layout`, `Layout.Section`, `Subheading`, `TextStyle` components ([#4142](https://github.com/Shopify/polaris-react/pull/4142))
- Add `fullWidth` prop to `ColorPicker` so the color picker can take the full width ([#4152](https://github.com/Shopify/polaris-react/pull/4152))
- Add `noScroll` prop to `Modal` which prevents modal contents from scrolling ([#4153](https://github.com/Shopify/polaris-react/pull/4153))
- Added new `color` prop to ProgressBar ([#3415](https://github.com/Shopify/polaris-react/pull/3415))
- Added `requiredIndicator` prop to `Label`, `Labelled`, `Select` and `TextField` ([#4119](https://github.com/Shopify/polaris-react/pull/4119))
- Add `small` prop to `Modal` so that width can be decreased to 380px ([#4177](https://github.com/Shopify/polaris-react/pull/4177))
- Add `status` prop to `IndexTable.Row` to allow table rows to specify background colors([#4146](https://github.com/Shopify/polaris-react/pull/4146))
- Disabled `pointer-events` on the prefix and suffix elements of the `TextField` component ([#4207](https://github.com/Shopify/polaris-react/pull/4207))
- Add `last` prop to `IndexTable.Cell` to create a sticky last cell on viewports larger than small ([#4150](https://github.com/Shopify/polaris-react/pull/4150))

### Bug fixes

- Fix bug in Safari where `Button` text is gray instead of white after changing state from disabled to enabled ([#4270](https://github.com/Shopify/polaris-react/pull/4270))
- Fix console warnings when `DataTable` unmounts ([#4249](https://github.com/Shopify/polaris-react/pull/4249))
- Fix console warnings displaying multiple times in `Sheet` ([#4269](https://github.com/Shopify/polaris-react/pull/4269))
- Remove top shadow when `Popover` and `Scrollable` scroll hinting is complete ([#4265](https://github.com/Shopify/polaris-react/pull/4265))

### Documentation

### Development workflow

### Dependency upgrades

### Code quality

### Deprecations
