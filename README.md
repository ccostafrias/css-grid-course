![](https://res.cloudinary.com/wesbos/image/upload/v1515524452/GRID-social-share_wlfzk3.png)

# CSS Grid Video Course

Repositório destinado a aprender e resolver os exercícios do curso [CSSGrid.io](https://CSSGrid.io).

## Course FAQ

### Q: I'm getting "This is meant to be run from within npm script."

Not sure why this is happening, but try these commands instead:

**windows:** `npm run start:win32`

**mac and linux:** `start:darwin:linux`

Very few people get this, but please contact me if you find out why `npm start` command isn't running.

### Q: I'm getting Browsersync Couldn't open browser (if you are using BrowserSync in a headless environment, you might want to set the open option to false)

This is because some versions of Firefox are "FirefoxDeveloperEdition" and some new downloads are "Firefox Developer Edition". If you had downloaded the browser before the course, just remove the spaces from the package.json command so it says "FirefoxDeveloperEdition"

### Q: I can't see the lines / numbers of Firefox' CSS Grid Inspection Tools

Make sure to turn off both "Use recommended performance settings" & "Use hardware acceleration when available“ within Preferences > Performance
