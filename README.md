# email-assets

Public image assets for Crunchloop email signatures.

Files in this repository are loaded directly by email clients,
so they must stay public and their paths must not change.

## Structure

signature/
  crunchloop-tile.png      Isotype tile (64px, exported @2x)
  company-linkedin.png     Company social icons (20px, @2x)
  company-instagram.png
  company-github.png
  company-x.png
  personal-linkedin.png    Optional personal icons (20px, @2x)
  personal-x.png

## Usage

Assets are served through jsDelivr:

https://cdn.jsdelivr.net/gh/crunchloop/email-assets@main/signature/<file>.png

## Rules

- Do not rename, move or delete files: emails already sent depend on these URLs.
- To update an asset, replace the file keeping the same name.
- Source files live in the Signatures Figma file (Assets page).
- Only add assets meant to be public.

## Credits and rights

- `crunchloop-tile.png` is a Crunchloop trademark. All rights reserved.
- Social icons are from [Pixelarticons](https://pixelarticons.com) by Gerrit Halfmann,
  licensed under the MIT License. See `LICENSE-pixelarticons`.
- LinkedIn, Instagram, GitHub and X logos are trademarks of their respective owners.
