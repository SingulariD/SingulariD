# Collection of important features as seen in other IDEs

* Editing
  * Syntax highlighting
    * Type id highlighting
    * Symbol reference highlighting
    * (Diff-based highlighting? -- rather an ACE extension?)
  * Code completion
    * Preferably use DScanner for completion item resolution
    * Ctrl+Space / member completion etc.
    * Delegate/lambda/new-expression generation (like when typing '=' or so) etc.
    * Pre-selection of recommended completion items (e.g. enum-items for places where the respective enum kind is required)
  * Goto definition
  * Rename symbols
  * Code refactorings (e.g. pattern-based; for -> foreach and such)
* Project settings
  * Load dub packages & Edit their definitions + insta-reload after save
  * (VisualD/Mono-D readonly import?)
* File browser
  * Besides displaying physical directory structure, be able to have artificial source paths (may be done in dub package definitions)
* Symbol browser
* Visual debugging (gdb, dbgeng, lldb interfaces?)
  * Breakpoints
  * Locals insight
  * Call stack
  * Threads
