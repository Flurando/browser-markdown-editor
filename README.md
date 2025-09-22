# browser-markdown-editor
A standalone, single-file HTML Markdown editor for restricted environments. No installation needed.

**This branch removed marked.js stuff along with the preview functionality, so older browsers could display it correctly.**

# Portable Markdown Editor (No Install Needed)
## A Standalone HTML/JavaScript Markdown Editor for Restricted Environments

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Frustrated by not being able to install Markdown editors like Obsidian or VS Code on locked-down work or public computers? This project provides a solution: a simplistic Markdown editor that runs entirely from a single `.html` file in your browser.**

*   **Zero Installation:** Just download the file and open it.
*   **No Admin Rights Needed:** Perfect for restricted environments.
*   **100% Client-Side:** No backend server required. All processing and saving happens in *your* browser.

---

## Key Features

*   **Editing Aids:**
    *   **Formatting Toolbar:** Quick buttons for Headings, Bold, Italic, Lists, Links, Code, etc.
    *   **Auto-Pairing:** Automatically closes `()`, `[]`, `{}`, `""`, `''`, `` ` ``.
    *   **Auto-List Continuation:** Automatically adds the next list marker on Enter.
*   **Session Persistence:** Your notes, content, settings (theme, pane size, sidebar state, sort order) are automatically saved to your browser's `localStorage`. Reopen the `.html` file, and your session should be restored.
*   **Light/Dark Theme:** Toggle between themes for comfort (preference is saved).
*   **Keyboard Shortcuts:** Basic shortcuts for Bold (`Ctrl+B`), Italic (`Ctrl+I`).


## Technology Stack

This project is intentionally kept simple and dependency-light to maximize portability:

*   **HTML5**
*   **CSS3** (Utilizing CSS Variables for easy theming)
*   **JavaScript (Vanilla ES6+)** - No frameworks!
*   **Libraries (loaded via CDN):**
    *   [marked.js](https://marked.js.org/): For parsing Markdown to HTML.

## Contributing

**Contributions are highly welcome and greatly appreciated!**

As mentioned, the initial code was AI-assisted. There's a fantastic opportunity for developers to help refine, optimize, and expand this tool. Whether it's fixing bugs, improving the UI, optimizing the JavaScript, or adding new features, your help can make this even better for users stuck in restricted environments.

**How to Contribute:**

1.  **Find an Issue or Suggest One:** Look through the open [Issues](https://github.com/ThinkerDan/browser-markdown-editor/issues) to see what needs attention. If you have a new idea or bug fix, feel free to open a new issue first to discuss it.
2.  **Fork the original Repository:** Create your own copy of ThinkerDan's project on GitHub.
3.  **Create a Branch:** Make a new branch in your fork for your changes (e.g., `git checkout -b feature/add-wikilinks` or `fix/sidebar-rendering-bug`).
4.  **Make Your Changes:** Implement your feature or fix the bug.
5.  **Commit Your Changes:** Write clear, concise commit messages explaining your changes.
6.  **Push to Your Fork:** Upload your branch to your GitHub fork (`git push origin your-branch-name`).
7.  **Open a Pull Request (PR):** Submit your changes back to this main repository. Describe your changes clearly in the PR description.

Please try to adhere to the project's core philosophy: maintaining it as a **standalone, client-side application** that works from a single HTML file with minimal external runtime dependencies (CDNs are okay).

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for full details. You are free to use, modify, and distribute this software.
