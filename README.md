# Random Person Matcher

A simple web app that randomly pairs people together. Each person uses their name and a personal password to check their match — no codes to remember, and nobody can see anyone else's pairing.

## How It Works

1. **Join** — Enter your name and choose a password.
2. **Wait** — An admin runs the matching once enough people have joined.
3. **Check** — Come back anytime, enter your name + password, and see your match. Only you can see it.

## Privacy

- Names are stored as SHA-256 hashes — browsing localStorage won't reveal the pool.
- Matches are encrypted per-person using each person's password hash as the key.
- You can only decrypt your own match by entering the correct password.

## Usage

Open `index.html` in a browser. No server needed — data is stored in localStorage.

### Admin

Default admin password: `matcher2024`

Admin can:
- See how many people are in the pool
- Run the random matching
- Reset everything for a new round
