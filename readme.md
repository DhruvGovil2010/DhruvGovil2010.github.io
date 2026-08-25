# dhruvgovil2010.github.io

My personal portfolio — live at [dhruvgovil2010.github.io](https://dhruvgovil2010.github.io)

## About

Backend Software Engineer portfolio built as a single static page. No framework, no build step — plain HTML, CSS, and JS, deployed directly via GitHub Pages.

Highlights the async pipeline work from [HireFlow](https://github.com/DhruvGovil2010/ats-ai-backend) (an AI ATS backend that cuts API response time by 95% using BullMQ + Redis), current work at Factrika, and prior work at To The New.

## Stack

- HTML / CSS / vanilla JS
- Google Fonts (JetBrains Mono, Inter)
- Hosted on GitHub Pages

## Structure

```
.
├── index.html     # entire site — markup, styles, and script in one file
├── resume.pdf     # downloadable resume (linked from the "Resume ↓" button)
└── README.md
```

## Running locally

No install needed — just open `index.html` in a browser. Or serve it locally:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Updating content

Everything lives in `index.html`:
- Experience → `<section id="work">`
- Projects → `<section id="projects">`
- Achievements → `<section id="achievements">`
- Skills → `<section id="skills">`
- Links (GitHub/LinkedIn/LeetCode/GFG/resume/project repos) → the `LINKS` object near the bottom of the `<script>` tag

Push to `main` and GitHub Pages redeploys automatically within about a minute.

## Contact

- Email: govildhruv2010@gmail.com
- LinkedIn: [linkedin.com/in/govildhruv](https://linkedin.com/in/govildhruv/)
- LeetCode: [leetcode.com/DhruvGovil2010](https://leetcode.com/DhruvGovil2010)
- GFG: [geeksforgeeks.org/user/dpsdhr27](https://www.geeksforgeeks.org/user/dpsdhr27)