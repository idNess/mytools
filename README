# HI! 👋 

This is my repo for some useful tools I build.

Small, practical, single-purpose web tools, hosted for free on GitHub Pages. No installs, no accounts: open the link and use it.

**Live site:** https://idness.github.io/mytools/

---

## Tools

| Tool | What it does | Link |
| --- | --- | --- |
| **Expense tracker** | Keeps track of trip expenses from receipts: who paid, what for, how much is left from a grant. Each expense links to its receipt, and everything can be exported. | [Open](https://idness.github.io/mytools/expense_tracker/) |

### Expense tracker projects

- **Pilot Light - Kultur | lx - October 2026**: expenses of the Pilot Light Portugal tour (Fake It Tour), 6 to 10 October 2026, counted against the Kultur | lx grant. [Open](https://idness.github.io/mytools/expense_tracker/pilot_light_kultur_lx_october_2026/)

More tools will land here over time.

---

## How the repo is organised

```
mytools/
├── index.html                  # home page, lists all the tools
├── README.md                   # this file
└── expense_tracker/
    ├── index.html              # list of expense tracker projects
    └── pilot_light_kultur_lx_october_2026/
        ├── index.html          # the tracker for this project
        └── src/                # receipt images and PDFs
```

Every tool lives in its own folder, and every project inside a tool lives in its own subfolder. Each page is a single self-contained HTML file, so there is no build step.

## Run it locally

Just open an `index.html` in your browser. Receipts and the "Download all receipts" button need the `src` folder next to the page, so for the full experience start a tiny local server from the repo root:

```
python3 -m http.server 8000
```

then go to http://localhost:8000/.

## Publish on GitHub Pages

1. Push the files to the `main` branch.
2. In the repo go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. After a minute the site is live at `https://<user>.github.io/mytools/`.

## Adding a new tool

1. Create a folder at the root, for example `my_new_tool/`, with an `index.html` inside.
2. Add a link to it in the root `index.html`.
3. Add a row to the table above.

## Privacy note

Receipts can contain personal details. Before publishing a new project, check that the files in `src/` are ones you are happy to make public, because GitHub Pages serves them to anyone with the link.

## License

Kindly developed by Vanessa Cicognani ✨ and released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

The Pilot Light and Kultur | lx logos belong to their respective owners and are used here only to identify the project.
