# Random Person Matcher

A simple web app that randomly pairs people together. Each person gets a private secret code — only they can see who they're matched with.

## How It Works

1. **Join** — Enter your name to join the pool. You get a unique secret code.
2. **Wait** — An admin runs the matching once enough people have joined.
3. **Check** — Enter your secret code to see your match. Nobody else can see your pairing.

## Usage

Open `index.html` in a browser. No server needed — data is stored in the browser's localStorage.

### Admin

Default admin password: `matcher2024`

Admin can:
- See how many people are in the pool
- Run the random matching
- Reset everything for a new round
