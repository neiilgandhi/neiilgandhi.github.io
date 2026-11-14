# Neiil Gandhi — Portfolio

Personal portfolio site for Neiil Gandhi, mechanical engineering student and Schreyer Honors Scholar at Penn State.

**Live site:** https://neiilgandhi.github.io/

## What's on it

- **Research:** 3D-printed carbon-fiber quadcopter frame (honors thesis, PACLAB) and a one-predator, two-prey ODE model, which also runs live as the plot at the top of the page
- **Internship and teams:** drone thermal mapping for solar siting at Pittsburgh Drone Services, EV drive-unit benchmarking with the Penn State Advanced Vehicle Team, and the MATE underwater ROV
- **Builds:** autonomous line-following vehicle, Rootline and Uplift (HackPSU)
- **Simulation and lab studies:** finite element analysis, computational fluid dynamics, and manufacturing process labs

## How it's built

One static page: `index.html` holds the markup, styles, and script. There is no build step. GitHub Pages serves the repository root.

| File | Purpose |
|---|---|
| `index.html` | The whole site |
| `images/` | Simulation screenshots and lab charts used in the project panels |
| `Neiil_Gandhi_Resume.pdf` | Resume linked from the download buttons |

## Updating it

- **Add a project:** add a `project-card` button in the Work section, then a matching entry in `projectData` in the script at the bottom of `index.html`. The button's `data-project` value must match the entry's key.
- **Add pictures to a project:** put the files in `images/` and list them under `images` in that project's `projectData` entry.
- **Update the resume:** replace `Neiil_Gandhi_Resume.pdf`, keeping the same file name so the download buttons keep working.
- **Preview locally:** open `index.html` in a browser.

## Contact

npg5444@psu.edu · [LinkedIn](https://linkedin.com/in/neiilgandhi) · [GitHub](https://github.com/neiilgandhi)
