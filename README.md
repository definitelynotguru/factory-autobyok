# Factory Auto BYOK

Single-page helper for Factory Droid custom models.

https://definitelynotguru.github.io/factory-autobyok/

The JSON this page builds is **`settings.json`**. Put it here:

- macOS / Linux: `~/.factory/settings.json`
- Windows: `%USERPROFILE%\.factory\settings.json`

Create the `.factory` folder if it does not exist. If you already have a file there, use the merge box on the page so plugins and trusted folders stay put.

## Tutorial

<video src="./AutoBYOK.mp4" controls width="720">
  <a href="./AutoBYOK.mp4">Watch AutoBYOK.mp4</a>
</video>

Open `index.html` or the Pages URL, fetch `/models`, pick what you want, copy the JSON into that path.

Keys stay in the tab. If the provider blocks browser CORS, paste the `/models` JSON instead.
