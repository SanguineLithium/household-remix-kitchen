# household-remix-kitchen
A simple HTML app to help relieve mental toil of figuring out simple meal prep.


## Run the meal planner

Once GitHub Pages is enabled, open the published website on your iPhone in Safari, or in any modern desktop browser. The app runs fully in the browser; no installation, build step, API key, or account is needed.

### Enable GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main**, then **/(root)**, and save.
4. When GitHub reports the site is live, open **https://sanguinelithium.github.io/household-remix-kitchen/** in Safari.

The entry page is `index.html` in the repository root. Avoid opening a downloaded HTML file in an iPhone preview; restricted file viewers can block JavaScript.

### Features

- Check ingredients on hand and adjust quantities.
- Generate a seven-day dinner plan for the household.
- Prepare four reusable cooking bases and track servings.
- View upstream prep steps and downstream storage guidance.
- Mark meals cooked, undo actions, and reserve manually chosen meals.
- Export/import a JSON backup of locally saved inventory and schedules.

### Data and limitations

The repository and published site are public. Pantry information is stored **locally in each browser** using localStorage, not uploaded to GitHub. Data is not synced across devices. Do not commit exported backups with personal information. Recipe amounts and storage projections are estimates.

The app has passed desktop browser automation at mobile viewport sizes. A physical iPhone/Safari compatibility test is still needed.
