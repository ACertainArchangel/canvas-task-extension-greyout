# Tasks for Canvas – Grey-Out Fork

This repository contains an **unofficial fork** of the open-source **Tasks for Canvas** browser extension.

👉 **Original project:**  
https://github.com/UseBetterCanvas/canvas-task-extension

All credit for the original design, functionality, and ongoing development belongs to the original author and contributors.

---

## Why this fork exists

This fork exists somewhat backwards compared to a typical open-source workflow.

I originally made this modification for personal use, by surgically editing the *compiled production build* of the extension to add a visual **grey-out behavior** for tasks. At the time, I had not yet realized that a clean, open-source version of the project was available on GitHub — which would have been a far more pleasant experience to modify.

Once I discovered that the project was open source and MIT licensed, it felt wrong to keep such a useful modification private, especially given how much it's improved my own experiance on canvas. This repository and accompanying Chrome Web Store release are the result of cleaning up and redistributing that change.

After initially implementing the grey-out behavior by directly modifying the compiled production build, I later updated the uncompiled source (`src`) to faithfully reflect those same changes. The repository now includes both the modified source code and the corresponding production build, ensuring that the published extension behavior is fully represented in readable source form.


---

## What this fork changes

This fork focuses on a **single, targeted behavior change**:

- Adds a visual grey-out check box to completed or inactive tasks to reduce cognitive noise
- Preserves all original functionality and user interface elements
- Does not introduce new permissions, tracking, or data collection

The goal is not to be a long term divergence from the original project, but to offer a small usability enhancement that some may find extremely helpful as I have.

---

## Relationship to the upstream project

- This fork is **unofficial**
- It is **not affiliated with or endorsed by** the original author
- All upstream credit and licensing are preserved
- Users looking for the canonical version should use the original repository linked above

If this modification proves broadly useful, it would likely be better suited as an upstream contribution rather than a long-lived fork.

---

## License

This project is licensed under the **MIT License**, in accordance with the original project.

See the `LICENSE` file for details.
