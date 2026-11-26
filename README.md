# Sigma D3 pilot plugin (static build)

Static build of a pilot Sigma custom plugin with six D3 visuals (paired weekly chart with forecast, indexed lines, stage bridge, RTV-style flow tiles, KPI header, monthly stack + line).
Served via GitHub Pages so Sigma can load it over HTTPS.

- Code and synthetic demo fixtures only. No real data is stored or collected here; inside Sigma the
  workbook passes element data to the plugin in the viewer's browser.
- Built with Vite from source commit e0991cf of the (private) project repository.
- Opened directly, the page shows the synthetic demo harness.
