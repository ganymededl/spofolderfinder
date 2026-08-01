# SharePoint Folder Finder

A lightweight browser tool that parses SharePoint video or file URLs and extracts the full folder path hierarchy â€” top-level down to the folder containing the file.

Built by David S. Liu for SLED Â· July 17, 2026.

## What It Does

- Paste any SharePoint video or file link (including recording URLs with ?xsdata=... tracking parameters)
- Instantly see the site, library, and every folder in the path
- Returns a clean, tracking-parameter-stripped copy of the link

## Supported URL Formats

\\\
https://microsoft.sharepoint.com/sites/.../Shared Documents/.../Recording.mp4?xsdata=...
https://microsoft.sharepoint.com/:v:/r/sites/.../stream.aspx?id=%2Fsites%2F...
\\\

## Run Locally

Open index.html directly in a browser â€” no server or build step needed.

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Static single-page app â€” no dependencies