# Homebrew Search for Alfred
![GitHub downloads](https://img.shields.io/github/downloads/chrisgrieser/alfred-homebrew/total?label=GitHub%20Downloads&style=plastic&logo=github)
![Alfred Gallery downloads](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchrisgrieser%2F.config%2Frefs%2Fheads%2Fmain%2FAlfred.alfredpreferences%2Falfred-workflow-download-count.yaml&query=alfred-homebrew&style=plastic&logo=alfred&label=Gallery%20Downloads&color=%235C1F87)
![Latest release](https://img.shields.io/github/v/release/chrisgrieser/alfred-homebrew?label=Latest%20Release&style=plastic)

Search, install, or uninstall Homebrew packages conveniently via Alfred.

<img width="70%" alt="showcase brew install" src="https://github.com/chrisgrieser/alfred-homebrew/assets/73286100/a46f48c7-e5ce-4eb2-aeb1-451231043b26">

<img width="70%" alt="showcase brew uninstall" src="https://github.com/chrisgrieser/alfred-homebrew/assets/73286100/b40a4300-7b2d-44fd-89a3-90fdf0190271">

## Requirements
- [Homebrew](https://brew.sh/)
- Optional:
  [AlfredExtraPane](https://github.com/mr-pennyworth/alfred-extra-pane) for
  previews of package homepages.

## Usage
- Search for a Homebrew package via the `bi` keyword. (+ The download counts
refer to the number of downloads per 90 days.)
	+ <kbd>⏎</kbd>: Install the package (`brew install`) in the Terminal. (Uses
	the terminal app you have configured [in your Alfred
	settings](https://www.alfredapp.com/help/features/terminal/).)
	+ <kbd>⌘⏎</kbd>: Open the package's homepage (`brew home`).
	+ <kbd>⌥⏎</kbd>: Copy the package's homepage to the clipboard.
	+ <kbd>⇧⏎</kbd>: Show package information (`brew info`) in Text View.
	+ <kbd>⌘Y</kbd> Quick Look a screenshot of the app, if available.
- Uninstall a package via the `bu` keyword (`brew uninstall`).
	+ <kbd>⇧⏎</kbd>: Show package information (`brew info`) in Text View.
	+ <kbd>⌃⏎</kbd>: Reinstall the package (`brew reinstall`).

> [!NOTE]
> The workflow uses the local homebrew packages cache. This means that the list
> of packages is automatically updated when you run `brew update` in your
> terminal.

## Mac App Store apps
You might also be interested in [this workflow to search the Mac App
Store](https://alfred.app/workflows/chrisgrieser/mac-app-store-search/).

> [!TIP]
> You can set both of them to the same keyword to simultaneously search homebrew
> and the Mac App Store.

## Installation
[➡️ Download the latest release.](./releases/latest)

The workflow auto-updates via Alfred's workflow-update mechanism.

## Credits
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

- [Website](https://chris-grieser.de/)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

<a href='https://ko-fi.com/Y8Y86SQ91' target='_blank'> <img height='36'
style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3'
border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
