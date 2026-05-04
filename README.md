# fe-assignment-template

Problem Statement
Build a tiny, production-ready React micro-app that lets a user search and bookmark GitHub repositories.
We want to see how you write modern, performant and maintainable front-end code while respecting real-
world constraints (time, performance, design polish).
Scope & Requirements
1. Search
– One text input. Debounced (≥ 300 ms) call to GitHub’s public /search/repositories endpoint.
– Show first 30 results in a clean card list (title, description, star count, language, avatar).
– Empty, loading and error states must be handled gracefully.
REST
2. Bookmarks
– Each card has a "★ Bookmark" toggle.
– Persist bookmarks to localStorage – Add a filter toggle: "All Bookmarked only".
; they must survive reloads.
3. Performance
– No unnecessary re-renders (use React.memo, useCallback, etc.)
4. Tooling
– Written in TypeScript, Reactjs – ESLint + Prettier configured; no warnings on npm run lint.
5. Delivery
Public GitHub repo with a README that explains how to install, run, test and build
A small write up in README walking through decisions, trade-offs and possible next steps
A deployed demo (Vercel/Netlify/GitHub Pages)
Time
2 Days: (≈ 6–8 focused hours total). We do not expect every pixel perfect; we expect thoughtful
prioritization and clear code.
Evaluation Rubric
– JavaScript & React fluency (hooks, concurrency, effects).
– Component architecture & reusability.
– State-management choices (context, reducer, or external lib).
– Documentation clarity.
Good luck!
