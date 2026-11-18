# BioGlow Run Planner

A scoring and route-planning app for the FIRST LEGO League BioGlow season.

## Put it on GitHub Pages
1. Create a new repository on GitHub (for example `bioglow-planner`).
2. Upload `index.html` and `map.jpg` to the root of the repository.
3. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute the app is live at `https://<your-username>.github.io/<repo-name>/`.

## How it works
- Pick the team at the top. "Error 404" appears in full ("Error 404: Chicken Not Found") on printouts and saved scores.
- Click the red or blue launch area to set the starting point, then click missions in order. Blue lines go out to missions; red lines go back to a launch area.
- White boxes hold Missions 13, 14 and 15. Students choose which mission goes in each box.
- Every plan starts at 90 points: 50 precision, 20 inspection, 20 Fragile Microhabitats.
- **Start** plays "3, 2, 1, LEGO!" and runs the 2:30 match clock. **PRECISION** removes one token.
- When time runs out, the score adjustment screen opens with every scoring item, precision tokens and Microhabitats.
- Saved scores stay in that browser. Use **Download CSV** to export them and **Print report** for a printout.
