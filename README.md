## ⚙️ Configuración temporal VS Code

Para evitar que VS Code autocomplete o cierre etiquetas automáticamente, añade estas opciones en tu configuración de usuario:

### 1. Abrir el archivo de configuración
- Presiona `Ctrl + Shift + P` (o `F1`).
- Escribe **Preferences: Open User Settings (JSON)**.
- Se abrirá el archivo `settings.json`.

### 2. Pegar esta configuración antes del último "}" . Asegúrate de añadir una "," al final de la última línea que esté inicialmente escrita.
```jsonc

  ,
  "editor.suggestOnTriggerCharacters": false,
  "editor.quickSuggestions": false,
  "editor.inlineSuggest.enabled": false,
  "editor.acceptSuggestionOnEnter": "off",
  "editor.tabCompletion": "off",
  "editor.snippetSuggestions": "none",

  "editor.autoClosingBrackets": "never",
  "editor.autoClosingQuotes": "never",
  "editor.autoSurround": "never",

  "html.autoClosingTags": false,
  "html.suggest.html5": false,

  "emmet.triggerExpansionOnTab": false,
  "emmet.showExpandedAbbreviation": "never",

  "editor.formatOnType": false


