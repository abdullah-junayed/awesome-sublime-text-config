# ✨ My Sublime Text Setup

A clean, modern, and distraction-free **Sublime Text** configuration designed for coding on a **14-inch display**.

The goal of this setup is to provide:

- 🌙 A warm dark theme
- ⚡ Smooth editing experience
- 👀 Comfortable readability
- 🧹 Automatic cleanup on save
- 💻 Minimal yet productive workflow

---

# Preview

> Theme: **Adaptive**
>
> Color Scheme: **Aura Theme**
>
> Font: **JetBrains Mono**

---

# Features

## 🎨 Modern UI

Uses the **Adaptive Theme** so the sidebar automatically matches the editor colors.

```json
"theme": "Adaptive.sublime-theme"
```

### Why?

- Native Sublime appearance
- Clean sidebar
- Better dark mode integration

---

## 🌙 Aura Color Scheme

```json
"color_scheme": "Packages/Aura Theme Color Scheme/aura-theme.tmTheme"
```

Aura provides

- warm purple accents
- soft contrast
- comfortable syntax highlighting
- less eye strain during long coding sessions

---

## 🔤 Font

```json
"font_face": "JetBrains Mono"
```

Recommended because it provides

- programming ligatures
- excellent readability
- clean punctuation
- beautiful italics

Install it from:

https://www.jetbrains.com/lp/mono/

---

# Display Optimization

Designed for **14-inch laptops**.

```json
"font_size": 12,
"ui_scale": 1.25,
"line_padding_top": 15,
"line_padding_bottom": 15
```

Benefits

- more breathing room
- comfortable reading
- better code focus
- reduced visual clutter

---

# Cursor & Scrolling

```json
"caret_style": "phase",
"smooth_scrolling": true,
"scroll_past_end": true,
"animation_enabled": true
```

This enables

- smooth scrolling
- animated cursor
- scrolling past the last line
- subtle UI animations

---

# Editing Experience

```json
"highlight_line": true,
"word_wrap": true,
"auto_match_enabled": true,
"match_brackets": true,
"match_brackets_content": true
```

These settings provide

- current line highlighting
- automatic bracket pairing
- bracket content matching
- wrapped long lines

---

# Save Behavior

```json
"save_on_focus_lost": true,
"trim_trailing_white_space_on_save": true,
"ensure_newline_at_eof_on_save": true
```

Every save automatically

- removes trailing spaces
- ensures a newline at the end of the file
- saves when the editor loses focus

---

# Indentation

```json
"tab_size": 4,
"translate_tabs_to_spaces": true
```

Uses

- 4 spaces
- spaces instead of tabs

---

# Format on Save

```json
"format_on_save": true
```

> **Note:** This requires an LSP formatter or a language-specific formatter plugin. Sublime Text does not format files on save by itself.

Examples include

- LSP
- LSP-pyright
- Prettier
- Black
- clang-format

depending on the language you use.

---

# Installation

## 1. Install Sublime Text

Download the latest version:

https://www.sublimetext.com/

---

## 2. Install Package Control

Open

```
Tools → Install Package Control
```

or follow the official installation guide:

https://packagecontrol.io/installation

---

## 3. Install Required Packages

Recommended packages

- Adaptive Theme
- Aura Theme
- LSP
- Package Control

Optional

- GitGutter
- SidebarEnhancements
- Terminus
- SublimeLinter

---

## 4. Install JetBrains Mono

Download:

https://www.jetbrains.com/lp/mono/

Install the font on your operating system.

---

## 5. Open Preferences

```
Preferences
    → Settings
```

Replace your existing configuration with:

```json
{
    "theme": "Adaptive.sublime-theme",
    "color_scheme": "Packages/Aura Theme Color Scheme/aura-theme.tmTheme",
    "highlight_line": true,

    "font_face": "JetBrains Mono",
    "font_size": 12,
    "line_padding_top": 15,
    "line_padding_bottom": 15,
    "word_wrap": true,
    "ui_scale": 1.25,

    "animation_enabled": true,
    "caret_style": "phase",
    "scroll_past_end": true,
    "smooth_scrolling": true,

    "auto_match_enabled": true,
    "match_brackets": true,
    "match_brackets_content": true,

    "save_on_focus_lost": true,
    "trim_trailing_white_space_on_save": true,
    "ensure_newline_at_eof_on_save": true,

    "tab_size": 4,
    "translate_tabs_to_spaces": true,

    "format_on_save": true
}
```

---

# Recommended Extensions

| Package | Purpose |
|----------|---------|
| Package Control | Install packages |
| Adaptive Theme | Modern UI |
| Aura Theme | Color scheme |
| LSP | Language Server support |
| GitGutter | Git diff indicators |
| SidebarEnhancements | Better file explorer |
| Terminus | Integrated terminal |
| SublimeLinter | Real-time linting |

---

# Who Is This Setup For?

This configuration is ideal for

- Python developers
- Web developers
- C/C++ programmers
- Java developers
- Students
- Anyone who prefers a minimal coding environment

---

# License

Feel free to use, modify, and share this configuration.

If it helps improve your workflow, consider giving this repository a ⭐.
