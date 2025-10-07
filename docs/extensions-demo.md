# Markdown Extensions Demo

This page shows examples of **MkDocs + Material** markdown extensions you can use to enrich your documentation.

---

## 🚨 Admonitions (`admonition`, `pymdownx.details`)

!!! info "Info Box"
    Use these to add extra information.

!!! note "Note Box"
    This is a note with collapsible details.

??? warning "Warning (collapsible)"
    This is useful when you want to draw attention and allow the user to expand or collapse the section.

---

## 🔀 Tabs (`pymdownx.tabbed`, `pymdownx.superfences`)

=== "UI Steps"
    Click **Submit** in the toolbar to complete the action.

=== "CLI Steps"
    ```bash
    curl -X POST https://api.example.com/submit
    ```

=== "Python Code"
    ```python
    import requests
    requests.post("https://api.example.com/submit")
    ```

---

## 🔁 Reusable Snippets (`pymdownx.snippets`)

--8<-- "docs/admin-guide/installation.md"

➡️ This content is pulled directly from another file!

---

## 🎛 Keyboard Keys (`pymdownx.keys`)

Press ++Ctrl+Alt+Del++ to open Task Manager.

---

## 📊 Grid Table (`pymdownx.grid_tables`)

```grid
+-------------------+-------------------------+
| Feature           | Description             |
+===================+=========================+
| Admonition        | Info, warning, note     |
| Tabs              | Multi-view display      |
| Code Highlighting | Syntax-aware formatting |
+-------------------+-------------------------+
