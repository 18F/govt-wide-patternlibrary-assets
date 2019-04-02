# USWDS for designers

This repository hosts editable, open source [United States Web Design System](https://designsystem.digital.gov/) design files for government designers or anyone wishing to make use of the USWDS components or visual styles.

With the release of USWDS 2.0, we've made some major changes to the way our assets are structured. **For now, these assets are only available as Sketch files for the Macintosh.** These files have been tested with Sketch 53. We'll be working to provide assets for other formats as soon as possible.

## Included files
### Sketch Libraries
- USWDS block: a layout and design helper tool synchronized to USWDS tokens
- USWDS system colors
- USWDS default theme colors
- Customizable project theme colors
- USWDS system typescale in Public Sans
- USWDS handoff symbols (Beta)
- USWDS Avatars (Beta)

### Sketch project file
This package includes `uswds-sketch` — stickersheet and project file synchronized to USWDS tokens.

### Fonts
- Font Awesome
- Merriweather
- Public Sans
- Roboto Mono
- Source Sans Pro

We encourage your input. Please leave any feedback in the as issues in this repo.

## Before you start: Install fonts

- Unzip the zipped packages in `fonts`.
- Add them to your computer's available fonts, by dragging them into the `Font Book` application.

Now the most recent versions of Font Awesome, Merriweather, Public Sans, Roboto Mono, and Source Sans Pro are installed and available.

## Before you start: Install Sketch libraries

- Clone or download this repo using the green `Clone or download` button in the top-right of the `uswds-for-designers` repo. This will copy the repo files to your computer. If you downloaded the files, unzip the package and move the new files to an accessible spot on your computer.
- Open Sketch > Preferences > Libraries
- Select `Add Library...`
- Select all the files in `sketch/libraries`. You can also add the files in `sketch/libraries/project-libraries`, but they are optional.

Now, all the USWDS libraries are connected to your installation of Sketch, making their styles, symbols, and colors available.

:warning: **Don't directly edit these library files.** All USWDS system and theme libraries are designed to keep your local files in sync with most current USWDS design tokens. Don't customize the library files — rather, use the shared libraries and styles to customize your project files. If you want to create specialized palettes for your project, use copies of the special `project-libraries` libraries, discussed below.

### Updating USWDS libraries
Occasionally, we'll make updates to these USWDS libraries and update our user with an email, a tweet, or a message to our public Slack. When you hear that there's a new release of our design assets, either pull that version from GitHub directly, or download the new assets with the provided link and replace the files manually. When you update the library files with a new USWDS release, Sketch will notify you that there are library updates in any affected files, and you can review and accept those updates. This process keeps your local files in sync with USWDS. 

## Using USWDS Sketch assets

### Sketch

more to come...

## Updating the USWDS documentation site

These archive files generated by `npm run release` may then be manually copied over to the [files directory](https://github.com/uswds/uswds-site/tree/master/files) of the USWDS Site for distribution on the [For Designers - Getting Started](https://designsystem.digital.gov/getting-started/designers/) page.
