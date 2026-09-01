# Random Person Matcher

A simple web app that randomly pairs people together. Your browser remembers who you are — just come back and your match is there. Other people can't see your pairing.

## How It Works

1. **Join** — Enter your name. Your browser remembers you automatically.
2. **Wait** — An admin runs the matching once enough people have joined.
3. **Come back** — Open the page again and your match is shown. No codes, no passwords.

## Privacy

- Each person's identity is tied to their browser via a random token stored in localStorage.
- You can only see your own match — other people's pairings are not visible.
- "Not you? Switch person" lets someone else use the same device.

## Usage

Open `index.html` in a browser. No server needed.

### Admin

Default admin password: `matcher2024`

Admin can:
- See how many people are in the pool
- Run the random matching
- Reset everything for a new round
