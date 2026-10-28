# Install your GitHub profile

This package is prepared for the GitHub username `shariyar29`.
It contains a profile README and locally stored graphics, including a looping GIF.
It does not contain activity statistics, language percentages, contribution snakes,
streak counters, visitor counters, API tokens or GitHub Actions workflows.

## Files to upload

Upload these to the root of the public `shariyar29/shariyar29` repository:

```
README.md
assets/
  identity-header.gif
  identity-header.png
  project-identity.png
  project-workspace.png
  project-migrations.png
  project-ai.png
  connect.png
```

Keep `README.md` at the root and preserve the `assets/` folder name.
Do not upload the ZIP itself as a substitute for the extracted files.

## Install through the GitHub website

1. Open your existing profile repository, or create a public repository named
   `shariyar29` under your `shariyar29` account.
2. Keep a backup of your existing README before replacing it.
3. Extract this ZIP on your computer. In the repository, choose Add file > Upload files.
4. Upload `README.md` and the complete `assets` folder. Preserve the folder structure.
   When the browser does not preserve a dragged folder, use Git locally instead.
5. Review the changes, then commit them to the repository's default branch.
6. Open your profile and check the banner, cards and LinkedIn link.

Only the profile repository needs to be public. Your work repositories stay private.
This package is not automatically published to your GitHub account.

## Preview without publishing

Open `preview.html` in a browser. It embeds all artwork and works offline.
The preview approximates GitHub's Markdown layout; GitHub supplies its own fonts,
spacing and table behaviour, which may differ on smaller screens.

## Animation and accessibility

The animation is a pre-generated GIF stored in this repository; it needs no service,
workflow or credentials. The README includes a still PNG for browsers that honour
`prefers-reduced-motion` through the supported HTML picture element.

For an always-static version, change the image source in README.md from
`./assets/identity-header.gif` to `./assets/identity-header.png`.
Image descriptions are included. Project details remain selectable HTML/Markdown.

## Editing your profile

- Update the introduction, project text, technology table and employment dates
  directly in README.md.
- Project links are intentionally omitted because no public project/demo URLs were
  verified. Add links only when they point to material you are authorised to share.
- The experience text retains the CV's conservative "9+ years" wording.
- No phone number, personal email, internal URL, credential or proprietary source code
  is included.
- The decorative system schematic is illustrative, not a production architecture diagram.

## Reference documentation

GitHub profile requirements:
https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme

README relative image paths:
https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

Supported Markdown/HTML images and the picture element:
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

GitHub's own profile page will still have its normal interface. This package removes
only README widgets; it does not change account-level contribution visibility.
