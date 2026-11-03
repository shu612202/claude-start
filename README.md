# claude-start

A one-file relay page (`index.html`). It reads `folder` and `q` from the URL fragment (after `#`) and opens `claude://code/new?folder=...&q=...` in the Claude desktop app.

- The fragment is never sent to the server.
- The only destination is `claude://code/new`. Nothing is loaded from or sent to other sites.
- The text is only placed in the input box; the user sends it.
