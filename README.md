# National Energy Policy 2025: interactive report

An interactive, single-page guide to the Prjmnestwe **National Energy Policy 2025**, covering electric vehicles, rural rail "pulse timetables", building efficiency standards and heat pumps.

**Live site:** `https://<your-username>.github.io/<repo-name>/` (after you enable GitHub Pages, see below)

## What's inside

- Animated hub-and-spoke rail and bus network showing how a pulse timetable works
- EV phase explorer, Norway comparison table, and barriers vs policy responses
- EV fleet pathway model: does ending combustion sales in 2040 deliver the 2050 target?
- Stylised charging-load chart (managed vs unmanaged charging)
- Filterable 2025-2050 policy roadmap
- Home retrofit and heat pump calculator

> The calculator, pathway model and charging chart are **illustrations** built on ranges quoted in the report. Starting EV sales shares, car lifetime and the charging curves are placeholder assumptions, labelled as such on the page.

## Repository layout

```
index.html                  the whole interactive page (no build step, no dependencies)
report/
  National-Energy-Policy-2025.pdf    full report, opens in a new tab from the page
.nojekyll
README.md
```

## Deploy on GitHub Pages

1. Create a new repository on GitHub and upload everything in this folder (keep the `report` folder).
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute, your site is live at the address shown on that page. Paste it into the **Live site** line above.

## Run locally

Open `index.html` in a browser. The report links work when the `report` folder sits beside it.

## Notes

- The page uses Google Fonts. It still works offline with fallback fonts.
- Student ID numbers were removed from the report cover before publishing.
- The report is shared as a PDF only. The editable Word file is not included.
- Check licensing and co-author permission before making the repository public. The report was drafted by four authors.

## Author

Interactive version by Haritha: [LinkedIn](https://www.linkedin.com/in/haritha-esd-architect/)
