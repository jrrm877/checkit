# Google Sites Copy

Google Sites does not work like GitHub Pages for uploading a folder of HTML files directly as a website.

Use the files in this `site/` folder in one of two ways:

## Fastest Option

Use GitHub Pages or another static host for `index.html`, `privacy.html`, and `styles.css`.

## If You Want Google Sites Specifically

1. Create a new Google Site.
2. Make a home page called `Home`.
3. Make a second page called `Privacy Policy`.
4. Copy the text below into the matching Google Sites pages.
5. Add your cover/support email before publishing.

## Home Page Copy

### Drive Folder Checklist

Add customizable checklists directly inside Google Drive folders so each folder can track its own tasks, links, colors, and layout preferences.

### What It Does

Drive Folder Checklist adds a checklist panel to Google Drive folder pages. Each folder keeps its own checklist, so you can organize work by client, project, trip, or document set.

### Features

- Per-folder checklists
- Item colors and saved color preferences
- Compact and standard views
- Item linking for files and folders
- Custom outer shell color per folder

### Support

For support, questions, or bug reports, contact:

`YOUR-COVER-EMAIL@EXAMPLE.COM`

## Privacy Policy Page Copy

### Privacy Policy for Drive Folder Checklist

Drive Folder Checklist stores checklist data in Chrome extension storage so the checklist can persist between visits to Google Drive folders.

#### Data the extension stores

- Checklist item text
- Checklist checked state
- Checklist item colors
- Checklist item link targets
- Preferred checklist density and layout
- Saved color preferences
- Per-folder checklist shell color

#### Where data is stored

- `chrome.storage.local` for per-folder checklist data and saved folder shell colors
- `chrome.storage.sync` for lightweight preference data such as saved colors and layout preferences

#### What the extension does not do

- It does not send checklist data to an external server
- It does not collect analytics
- It does not sell personal data
- It does not use remote code

#### Website access

The extension runs on `https://drive.google.com/drive/*` because it adds checklist UI to Google Drive pages.

#### Contact

For privacy or support questions, contact:

`YOUR-COVER-EMAIL@EXAMPLE.COM`

## Cover Email Options

The easiest non-personal options are:

- Create a separate Gmail account just for support, مثل `drivefolderchecklist.help@gmail.com`
- Use a forwarding alias from a domain you own
- Use Cloudflare Email Routing if you have a domain

The fastest option for most people is simply creating a new Gmail account used only for extension support.
