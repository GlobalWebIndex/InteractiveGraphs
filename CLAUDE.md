# InteractiveGraphs

## Version eyebrow rule

Whenever you change the script (`source/gwi-chart.js`, `gwi-chart.standalone.js`, or anything else that ships a new version of `<gwi-chart>`), update the eyebrow in the `<header>` of `index.html` so it shows the latest version.

- Format: `V<version> - GWI <Month> <Year>`, for example `V1.6.0 - GWI October 2026`.
- Use the same version number as the git tag and the `@x.y.z` in the embed snippet in `index.html` and `README.md`. Keep all of them in sync.
- Update the month and year to the current date when the version changes.
- Only the header eyebrow carries the version. The other `.eyebrow` elements are chart section labels, so leave them alone.
