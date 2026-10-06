# Yuecui Cai — Personal Website

This repository powers the GitHub Pages website at:

`https://yuecui0218.github.io/`

## Main files

- `index.html` — website text and section structure
- `style.css` — colors, spacing, layout, tags, mobile design
- `script.js` — mobile navigation and automatic footer year
- `cv.pdf` — add your CV using this exact filename if you want the CV button to work

## How to update text

Open `index.html` in GitHub and click the pencil icon to edit.

Useful sections are marked by IDs such as:

- `about`
- `research`
- `publications`
- `cv`
- `contact`

Commit the change when finished. GitHub Pages will update from the repository.

## How to add your profile picture

1. Upload your image to this repository, for example `profile.jpg`.
2. In `index.html`, find:

```html
<div class="avatar-placeholder">Add photo</div>
```

3. Replace it with:

```html
<img class="avatar-placeholder" src="profile.jpg" alt="Portrait of Yuecui Cai">
```

## How to add a publication

In `index.html`, copy an existing publication block:

```html
<div class="publication">
  <div class="pub-year">2026</div>
  <div>
    <h3>Your publication title</h3>
    <p class="muted">Journal name · publication details</p>
  </div>
</div>
```

Then change the year, title, journal, conference, seminar, or other details.

## How to add links

Replace `#` in the profile links with your actual URLs for:

- Google Scholar
- ORCID
- LinkedIn

Your GitHub link is already set.

## How to change the public email

In `index.html`, replace both occurrences of:

`your.email@example.com`

with the email address you want visible publicly.

## Important privacy note

Everything committed to this repository is public because the website itself is public. Do not upload private documents, unpublished confidential research data, passwords, tokens, or personal information you do not want publicly visible.
