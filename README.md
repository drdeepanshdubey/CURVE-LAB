# The Curve Lab

An interactive one-page pitch by **Deepansh Dubey**: computational pharmaceutics (PBPK) workshops, a live pharmacokinetic curve simulator, and an explorable map of careers after B.Pharm.

**Live site:** https://career-curve-lab.netlify.app/
**Book a call:** https://topmate.io/deepansh_dubey

## What is inside
- **Curve simulator:** change dose, absorption and clearance and watch the plasma curve, Cmax, Tmax and AUC update (one-compartment oral model).
- **Career map:** 41 careers in six clusters (pharma, clinical and regulatory, tech and AI, business, healthcare, education and entrepreneurship). Tap a dot for a short brief and a "Start with" tip.
- **Workshops and offer:** formats for B.Pharm, D.Pharm, M.Pharm, PhD, industry, ventures and institutions.
- **Reach out:** Ask (LinkedIn), Check and Apply (email) message composer with copy-to-clipboard.

## Project structure
```
index.html          complete single-file page (photo embedded), deploy this
src/template.html   editable source with a __PHOTO__ placeholder
photos/             source portrait
```

## Run locally
Open `index.html` in any browser. No build step and no dependencies.

## Deploy
- **Netlify:** drag `index.html` to https://app.netlify.com/drop
- **GitHub Pages:** Settings, Pages, deploy from branch `main`, folder `/ (root)`.

## Editing
Change `src/template.html`, then replace `__PHOTO__` with a base64 data URI of `photos/me_small.jpg` to regenerate `index.html`.

## Note
Educational illustration. The simulator is a simplified model and not for clinical use.

## License
Apache-2.0, see [LICENSE](LICENSE). Portrait photo and personal details: all rights reserved by Deepansh Dubey.
