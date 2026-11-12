# HTML Live Editor

A lightweight, single-file split-screen HTML, CSS, and JavaScript live editor and compiler modeled after the W3Schools Tryit Editor. Built entirely with vanilla HTML5, CSS3, and JavaScript with zero external dependencies.

## Features

- **Split-Screen Workspace:** View your code and rendered output side-by-side or stacked vertically, with a smooth draggable resizer bar (mouse and touch supported, double-click to reset to 50/50).
- **Responsive Design:** Automatically adapts to smaller and mobile viewports by stacking the editor above the preview pane.
- **Line-Numbered Code Editor:** Includes synchronized scrolling line numbers, live cursor line/column tracking, and monospace typography (`Consolas`, `Monaco`, `Courier New`).
- **Tab Indentation Support:** Pressing `Tab` inserts spaces directly in the editor rather than shifting focus away from the textarea, with `Shift + Tab` support for outdenting.
- **Live Output Preview:** Renders code inside an `<iframe>` using `srcdoc` and displays real-time viewport dimensions (`Width x Height px`) as you resize the panes.
- **Theme Switcher:** Toggle seamlessly between Dark Mode and Light Mode.
- **Starter Template & Reset:** Loads with an interactive HTML/CSS/JS boilerplate and includes a Reset button to restore the default code.
- **One-Click Download:** Export your current code directly as an `index.html` file.

## Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + Enter` / `Cmd + Enter` | Compile and run code in the preview pane |
| `Tab` | Insert indentation spaces |
| `Shift + Tab` | Remove indentation |

## Getting Started

Because the entire application is self-contained in a single file, no build tools, package managers, or local servers are required.

1. Clone this repository or download `index.html`:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   ```
2. Open `index.html` directly in any modern web browser.

## Hosting with GitHub Pages

You can host a live version of this editor for free using GitHub Pages:

1. Push `index.html` to the root of your GitHub repository.
2. Go to **Settings > Pages** in your repository.
3. Under **Build and deployment**, set the source to **Deploy from a branch**, select your `main` branch and `/ (root)` folder, and click **Save**.
4. Your live editor will be available at `https://your-username.github.io/your-repo-name/`.

## Project Structure

```text
.
├── index.html   # Complete editor application (HTML, CSS, and JavaScript)
└── README.md    # Project documentation
```
