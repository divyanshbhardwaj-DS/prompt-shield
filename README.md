# prompt-shield

A cybersecurity workspace for scanning prompts, reviewing scan history, and configuring security rules. Built with React and Vite.

## Run locally

1. Install Node.js (18+ recommended).
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed by Vite.

## Included
- Overview dashboard
- Prompt scanner with local heuristic demo checks
- Scan history with search
- Security rule toggles
- Workspace settings
- Responsive sidebar and mobile layout

## Important
This is a frontend prototype. The scanner runs simple pattern checks in the browser. It is not a production prompt-injection firewall and is not connected to a backend. Connect the scan action to your backend API before using it for real security decisions.
