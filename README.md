<div align="center">

<img src="./assets/hero-banner.svg" width="100%" alt="Dan Vilar (DevIsola) — Engineering what's next. Full-stack products, applied ML and data-driven systems." />

<br />

**I build thoughtful software — polished web experiences, data-driven tools, and applied machine learning.**

Based in Vancouver, BC. My flagship project is an illustrated, open-source history of the *Magic: The Gathering* Multiverse.

<br />

[**Chronicles of the Multiverse ↗**](https://devisola.github.io/mtg-history/) &nbsp;·&nbsp; [**LinkedIn**](https://www.linkedin.com/in/dev-disola/) &nbsp;·&nbsp; [**Moxfield**](https://moxfield.com/users/devdisola) &nbsp;·&nbsp; [**Ko-fi**](https://ko-fi.com/devdisola)

</div>

<br />

## Featured project

<a href="https://devisola.github.io/mtg-history/">
  <img src="./assets/chronicles-feature.svg" width="100%" alt="Chronicles of the Multiverse — an illustrated history of the Magic: The Gathering Multiverse. 10 chapters, 88 characters, 130 events, 118 relationships and 133 card printings." />
</a>

**[Chronicles of the Multiverse](https://devisola.github.io/mtg-history/)** connects decades of scattered lore — expansions, novels, short fiction and flavour text — into one readable, illustrated chronicle. Ten original chapters run from the ancient Thran to the Omenpaths, with real card printings placed beside the passages they illustrate as *historical artifacts*. It's a reading experience, not a card database.

<p align="center">
  <a href="https://devisola.github.io/mtg-history/chapters/thran/">
    <img src="https://github.com/DevIsola/mtg-history/raw/main/docs/screenshots/chapter-reader.jpg" width="100%" alt="A Chronicles chapter: narrative text beside a card printing shown as a historical moment, with a sticky table of contents" />
  </a>
</p>

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://devisola.github.io/mtg-history/relationships/?person=urza"><img src="https://github.com/DevIsola/mtg-history/raw/main/docs/screenshots/character-profile.jpg" width="100%" alt="Urza's character profile with biography, appearances and featured card" /></a>
      <br /><strong><a href="https://devisola.github.io/mtg-history/relationships/?person=urza">Characters &amp; relationships</a></strong><br />
      <sub>88 profiles and an explorable graph of 118 documented links — family, alliance, conflict, mentorship — shareable by URL.</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://devisola.github.io/mtg-history/timeline/"><img src="https://github.com/DevIsola/mtg-history/raw/main/docs/screenshots/timeline.jpg" width="100%" alt="Timeline atlas with era filter, search and coverage counts" /></a>
      <br /><strong><a href="https://devisola.github.io/mtg-history/timeline/">Timeline atlas</a></strong><br />
      <sub>Ten eras and 130 events in story order, separating in-world chronology from publication history.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://devisola.github.io/mtg-history/archive/"><img src="https://github.com/DevIsola/mtg-history/raw/main/docs/screenshots/card-viewer.jpg" width="100%" alt="Artwork viewer showing a card at full size with illustrator attribution and a Scryfall link" /></a>
      <br /><strong><a href="https://devisola.github.io/mtg-history/archive/">Illustrated archive</a></strong><br />
      <sub>Every card reference with its exact printing, artist credit and historical significance.</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://devisola.github.io/mtg-history/"><img src="https://github.com/DevIsola/mtg-history/raw/main/docs/screenshots/dark-mode.jpg" width="100%" alt="A chapter rendered in the dark theme" /></a>
      <br /><strong><a href="https://devisola.github.io/mtg-history/">Light, dark &amp; mobile</a></strong><br />
      <sub>Theme follows your system, and the whole archive is designed mobile-first.</sub>
    </td>
  </tr>
</table>

**Under the hood**

- **Typed content model** — cards, characters, events, relationships and glossary terms live in typed Astro Content Collections written in MDX.
- **Static by design** — no accounts, database or server; built with Astro and deployed to GitHub Pages through GitHub Actions.
- **Tested like a product** — every deploy runs unit, content-integrity, editorial, type and link checks, plus Playwright regression tests on desktop and mobile Chromium.
- **Reproducible screenshots** — the README tour is captured automatically by Playwright, and a capture fails rather than shipping a broken card image.
- **Accessible interactions** — keyboard-friendly dialogs and inline definitions, and the relationship graph is mirrored by an accessible card list.

`Astro` &nbsp; `TypeScript` &nbsp; `MDX` &nbsp; `SCSS` &nbsp; `Playwright` &nbsp; `GitHub Actions` &nbsp; `GitHub Pages`

<p>
  <a href="https://devisola.github.io/mtg-history/"><strong>Enter the archive ↗</strong></a> &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/DevIsola/mtg-history"><strong>View source ↗</strong></a>
</p>

<img src="./assets/divider.svg" width="100%" alt="" />

## More work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/DevIsola/CommunityEvents">
        <img src="./assets/community-card.svg" width="100%" alt="CommunityEvents project card" />
      </a>
      <h3><a href="https://github.com/DevIsola/CommunityEvents">CommunityEvents</a></h3>
      <p>A community events web application built with Vue and Vite — an example of my frontend application work.</p>
      <p><code>Vue</code> &nbsp; <code>Vite</code> &nbsp; <code>JavaScript</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/DevIsola/ENEB-Project">
        <img src="./assets/analysis-card.svg" width="100%" alt="ENEB Project data analysis card" />
      </a>
      <h3><a href="https://github.com/DevIsola/ENEB-Project">ENEB Project</a></h3>
      <p>Notebook-based academic project work in applied data analysis.</p>
      <p><code>Jupyter Notebook</code> &nbsp; <code>Data analysis</code></p>
    </td>
  </tr>
</table>

### On the workbench

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>◈ MTG Event Hub</strong> &nbsp;<sub><code>in development</code></sub>
      <p>A full-stack platform for community events, vendor workflows and marketplace experiences.</p>
      <sub><code>Next.js</code> &nbsp; <code>TypeScript</code></sub>
    </td>
    <td width="50%" valign="top">
      <strong>◈ Deck Evaluation &amp; ML</strong> &nbsp;<sub><code>research</code></sub>
      <p>Evaluating Commander decks with structured metrics, simulation and calibration in Python.</p>
      <sub><code>Python</code> &nbsp; <code>Simulation</code> &nbsp; <code>PyTorch</code></sub>
    </td>
  </tr>
</table>

<img src="./assets/divider.svg" width="100%" alt="" />

## Toolkit

<img src="./assets/working-stack.svg" width="100%" alt="Working toolkit — Languages: Python, TypeScript, JavaScript. Web: Astro, Next.js, React, Vue, SCSS, Tailwind. AI and data: PyTorch, Jupyter, data analysis. Quality and delivery: Playwright, GitHub Actions, Linux, Git, VS Code." />

## How I build

**Make complexity legible.** I like turning tangled information into something people can navigate — strong foundations underneath, a calm and considered interface on top. That means typed data, automated checks, reproducible analysis, and the small design decisions that make software feel finished.

Away from the editor you'll find me at the intersection of strategy games, storytelling, simulation and machine learning — which is usually where my next project starts.

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">

### Let's connect

Open to collaborating, talking shop, or nerding out about Magic lore.

[**LinkedIn**](https://www.linkedin.com/in/dev-disola/) &nbsp;·&nbsp; [**GitHub**](https://github.com/DevIsola?tab=repositories) &nbsp;·&nbsp; [**Moxfield decks**](https://moxfield.com/users/devdisola) &nbsp;·&nbsp; [**Chronicles**](https://devisola.github.io/mtg-history/)

<br />

<sub>If my open-source work is useful to you, you can support it — entirely optional; everything stays free.</sub>

<a href="https://ko-fi.com/devdisola"><img src="./assets/ko-fi-button.svg" width="220" alt="Support my work on Ko-fi" /></a>

<br /><br />

<sub>Built with intention · Documented with care · Always evolving</sub>

</div>
