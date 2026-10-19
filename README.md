# Wallpaper Lab

A wallpaper maker that runs in Safari on your iPhone. It draws wallpapers at your phone's exact screen resolution in nine styles (Gears, Blueprint, Circuit, Aurora, Gradient, Waves, Halftone, Shapes, Quote) and eight color palettes.

## Use it

1. Open `index.html` in Safari (see "Put it online" below).
2. Pick a style and colors, then tap **Shuffle** until you like it.
3. Tap **Save wallpaper**, press and hold the image, then tap **Save to Photos**.
4. In Photos, tap Share, then **Use as Wallpaper**.

Tip: in Safari, tap Share, then **Add to Home Screen** to open it like an app.

## Put it online (GitHub Pages)

In this repo on GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**, then pick your branch and `/ (root)`. Your app will be at `https://<username>.github.io/<repo>/`.

## Change your wallpaper automatically (Shortcuts)

iOS doesn't let apps set the wallpaper directly, but the Shortcuts app can:

1. Save several wallpapers into a Photos album named **Wallpapers**.
2. Open **Shortcuts → Automation → New Automation → Time of Day** (for example, 7:00 AM daily), and choose **Run Immediately**.
3. Add the actions **Find Photos** (Album is Wallpapers, Sort by Random, Limit 1), then **Set Wallpaper** (Lock Screen and Home Screen). Turn off **Show Preview**.
