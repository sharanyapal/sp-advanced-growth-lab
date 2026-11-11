<div align="center">

# Growth Experiments

**A test bench for growth questions and measurement.**

<sub>ADVANCED LAB &nbsp; / &nbsp; HTML · CSS · JavaScript &nbsp; / &nbsp; SOURCE-TRANSPARENT</sub>

[Concept](#concept) &nbsp;•&nbsp; [Launch](#launch) &nbsp;•&nbsp; [Under the hood](#under-the-hood) &nbsp;•&nbsp; [Study notes](#study-notes)

</div>

---

## Concept

Compare conversion tests and run epsilon-greedy multi-armed bandits against seeded campaigns.

**Explore, don't assume:** change the inputs and compare the visible result with the implementation. This is an educational lab, not a production service.

## Launch

```bash
python -m http.server 8000
```

Open `http://localhost:8000/`. All browser assets are served from this repository.

## Under the hood

| Source | What it contains |
| :-- | :-- |
| [`README.md`](./README.md) | Documentation |
| [`app.js`](./app.js) | Application logic and state |
| [`index.html`](./index.html) | Interactive frontend |
| [`styles.css`](./styles.css) | Visual system and responsive layout |

## Study notes

Use synthetic or otherwise approved data for exploration. Where the demo models decisions or predictions, the results depend on the assumptions encoded in the project and should not be treated as operational advice.

<details>
<summary><strong>Read preserved technical background & original instructions</strong></summary>

# Growth Experiments

Compare conversion tests and run epsilon-greedy multi-armed bandits against seeded campaigns.

Run locally with a static server: `python -m http.server 8000` from the Advanced Labs root and open `http://localhost:8000/apps/growth-lab/`.

No credential or secret is embedded. See app.js for implementation and edge cases.

</details>

---

<sub>One of the [interactive labs in Sharanya Pal's GitHub collection](https://github.com/sharanyapal?tab=repositories).</sub>
