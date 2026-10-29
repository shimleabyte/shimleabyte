<div align="center">
  <img src="./assets/shimleabyte-hero.svg" alt="Shimleabyte — from pixels to persistence, with a pixel-flow system diagram" width="100%" />
  <p>
    <a href="https://shimleabyte.github.io/osbio/"><strong>OPEN THE DESKTOP</strong></a>
    &nbsp; / &nbsp;
    <a href="https://github.com/shimleabyte?tab=repositories">BROWSE THE REPOS</a>
  </p>
</div>

I work where interface behavior meets system rules: browser interactions, local-first tools, persistence, and domain logic. I want to know what a system does, why it does it, and which edge case will break it.

---

<p><sub>01 / SELECTED WORK</sub></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://shimleabyte.github.io/osbio/"><img src="https://raw.githubusercontent.com/shimleabyte/osbio/main/docs/screenshots/osbio-desktop.png" alt="Current OSBio desktop screenshot showing the icon-only Pixel-Flow shell and floating app dock" width="100%" /></a>
      <p><sub>01 — INTERFACE SYSTEM</sub></p>
      <h3><a href="https://github.com/shimleabyte/osbio">OSBio / Pixel-Flow Workstation</a></h3>
      <p>A portfolio that behaves like a desktop instead of a landing page: icon-only shell chrome, a custom split-corner outline system, eleven-icon launcher, draggable windows, and local-first workspace apps. The project README includes real Chromium captures of both the desktop and launcher.</p>
      <p><code>HTML</code> <code>CSS</code> <code>Vanilla JavaScript</code> <code>IndexedDB</code> <code>Playwright</code></p>
      <p><a href="https://github.com/shimleabyte/osbio">Source ↗</a> · <a href="https://shimleabyte.github.io/osbio/">Live desktop ↗</a> · <a href="https://github.com/shimleabyte/osbio#screenshots">Screenshots ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/shimleabyte/mutabaah-cli"><img src="./assets/work-mutabaah.svg" alt="Mutabaah CLI terminal illustration" width="100%" /></a>
      <p><sub>02 — LOCAL-FIRST TOOL</sub></p>
      <h3><a href="https://github.com/shimleabyte/mutabaah-cli">Mutabaah CLI</a></h3>
      <p>A Go terminal app with separate activity and notes workflows. Local JSON storage, input validation, explicit state, and tests; no cloud service or third-party runtime dependencies.</p>
      <p><code>Go</code> <code>JSON</code> <code>CLI</code> <code>Testing</code></p>
      <p><a href="https://github.com/shimleabyte/mutabaah-cli">Inspect the implementation ↗</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/shimleabyte/simpul"><img src="./assets/work-simpul.svg" alt="Simpul order and payment workflow diagram" width="100%" /></a>
      <p><sub>03 — BACKEND DOMAIN</sub></p>
      <h3><a href="https://github.com/shimleabyte/simpul">Simpul</a></h3>
      <p>A reliability-first Go backend starter for order and payment workflows used by small-batch sellers. The domain model and tests exist; transactional database persistence is a later milestone, not a claimed feature.</p>
      <p><code>Go</code> <code>Domain Modeling</code> <code>PostgreSQL</code></p>
      <p><a href="https://github.com/shimleabyte/simpul">Follow the build ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/shimleabyte/optical-anchor-button"><img src="./assets/work-optical-anchor.svg" alt="Optical Anchor burnt-orange eye button illustration" width="100%" /></a>
      <p><sub>04 — INTERACTION STUDY</sub></p>
      <h3><a href="https://github.com/shimleabyte/optical-anchor-button">Optical Anchor Button</a></h3>
      <p>A button built around a custom eye: pointer-responsive gaze, fatigue states, keyboard focus, reduced-motion support, and a precision-hardware surface. Includes React and standalone HTML work.</p>
      <p><code>React</code> <code>TypeScript</code> <code>SVG</code> <code>Vanilla JS</code></p>
      <p><a href="https://github.com/shimleabyte/optical-anchor-button">See the component study ↗</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/shimleabyte/log-salary-tracker"><img src="./assets/work-teacher-log.svg" alt="Teacher Log monthly summary illustration" width="100%" /></a>
      <p><sub>05 — MOBILE UTILITY</sub></p>
      <h3><a href="https://github.com/shimleabyte/log-salary-tracker">Teacher Log &amp; Salary Tracker</a></h3>
      <p>A Flutter logbook for teaching sessions and estimated monthly pay. Device-local persistence and an ARM 32-bit Android target; static analysis and release build still need to be run in a Flutter-enabled environment.</p>
      <p><code>Flutter</code> <code>Dart</code> <code>Android ARMv7</code></p>
      <p><a href="https://github.com/shimleabyte/log-salary-tracker">Inspect the app source ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <img src="./assets/workbench.svg" alt="Current engineering workbench: SQL, transactions, and tests" width="100%" />
      <p><sub>06 — CURRENT WORKBENCH</sub></p>
      <h3>Follow the behavior to the edge.</h3>
      <p>Current study: SQL and database design, transactions and retries, test strategy, data structures, and system design. The aim is to prove the rules before adding infrastructure around them.</p>
      <p><code>Data Modeling</code> <code>Failure Paths</code> <code>Invariants</code></p>
    </td>
  </tr>
</table>

---

<p><sub>02 / DEFAULTS I WORK BY</sub></p>

<table>
  <tr>
    <td width="33%" valign="top">
      <p><strong>01 / State first</strong></p>
      <p>Make transitions and invalid states explicit before adding visual polish.</p>
    </td>
    <td width="33%" valign="top">
      <p><strong>02 / Keep the seam visible</strong></p>
      <p>Separate domain rules, command or UI handling, and persistence so each can be inspected.</p>
    </td>
    <td width="33%" valign="top">
      <p><strong>03 / Test the awkward case</strong></p>
      <p>Retries, invalid input, empty data, and edge states belong in the design — not in the postmortem.</p>
    </td>
  </tr>
</table>

<p><sub>03 / TOOLKIT</sub></p>

<p><strong>Web</strong> &nbsp; HTML · CSS · JavaScript · React · TypeScript<br />
<strong>Systems</strong> &nbsp; Go · CLI design · JSON persistence · REST APIs<br />
<strong>Mobile</strong> &nbsp; Flutter · Dart<br />
<strong>Workflow</strong> &nbsp; Git · automated tests · browser validation</p>

<p><sub>04 / ELSEWHERE</sub></p>

<p><a href="https://github.com/shimleabyte">GitHub profile ↗</a> &nbsp; / &nbsp; <a href="https://shimleabyte.github.io/osbio/">OSBio portfolio ↗</a></p>

<p align="right"><sub>SHIMLEABYTE / INDEPENDENT DEVELOPMENT / BUILT SINCE 2024</sub></p>
