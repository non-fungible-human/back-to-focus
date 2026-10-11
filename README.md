# Back to Focus

Open a distracting app during Focus. Get sent back to what matters.

A free iPhone Shortcut for iOS 27. While any Focus except Sleep is on, opening X or Instagram sends you straight back to your Home Screen. With no Focus, or during Sleep, nothing happens.

It redirects you; it doesn't lock anything.

**Get it:** https://non-fungible-human.github.io/back-to-focus/

## How it works

```
When X or Instagram is opened
  Get Current Focus
  If all are true:
      Current Focus has any value
      Current Focus Name is not "Sleep"
    Go to Home Screen
  End If
```

## Setup

1. Open the page on your iPhone, tap **Get Back to Focus**, then add the shortcut.
2. Open **Back to focus** in Shortcuts, tap **Edit**, then the arrow next to **Opened**, and switch on **Automation**. It arrives switched off ("Automation is turned off").
3. Optional: tap **X** or **Instagram** in the shortcut to pick your own apps.
4. Turn on any Focus except Sleep and open X to try it.

On an iPhone that isn't set to English, change "Sleep" in the shortcut to your language's name for the Sleep Focus.

To pause it, switch **Automation** off the same way. To remove it, delete the shortcut in the Shortcuts app.

## This repo

`site/` is a single static page, deployed to GitHub Pages on every push to `main`. No accounts, no analytics.

Open source under the [MIT License](LICENSE). Not affiliated with or endorsed by Apple.
