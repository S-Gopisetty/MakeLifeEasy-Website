# MakeLifeEasy Website

Version 1.0.0. Upload these files to any static host. No Node program has to stay running.

## Files to upload

Keep these side by side. Do not rename `assets/`.

```text
index.html
time.html
awake.json
favicon.svg
assets/
```

Open `index.html`. **Open** on the home page goes to the clock list. **Convert** is the other tab.

## Awake download

`awake.json` starts with an empty link, so the button says the GitHub link is coming later.

When you have a file to offer, edit `awake.json` on the server:

```json
{
  "_comment": "Paste an https://github.com/... link in downloadUrl. Any other address is ignored.",
  "downloadUrl": "https://github.com/S-Gopisetty/MakeLifeEasy-Awake/releases/download/v1.0.0/awake.zip"
}
```

Only an `https://github.com/...` address is accepted. Any other address is ignored. You do not need to rebuild the site.

## Other repos

- Clock source: [MakeLifeEasy-Clock](https://github.com/S-Gopisetty/MakeLifeEasy-Clock)
- Awake: [MakeLifeEasy-Awake](https://github.com/S-Gopisetty/MakeLifeEasy-Awake) is reserved and empty

Times are converted in the browser. They are not sent to a server.
