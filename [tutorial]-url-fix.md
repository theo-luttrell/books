You know how when you open an open-source url is says `https://soft-tutor.github.io/example/folder/index.html`
<br />This looks ugly but luckily there is a fix for this: folders

Github will use the html of `index.html` if present when no file is specified without changing the url.
For examle if the file tree looked like this:
folder > index.html
folder2 > index.html

You could go to `https://soft-tutor.github.io/example/folder`
<br /> or `https://soft-tutor.github.io/example/folder/index.html`

and likewise this: `https://soft-tutor.github.io/example/folder2`
<br /> or this: `https://soft-tutor.github.io/example/folder2/index.html`

### Rules

- Replace all **html** files with folders (e.g., `polar-bears.html` --> `polar-bears > index.html`)
- Use only html files named `index.html`
- To go forward or back use `{folder-name}` (e.g., `main` -> `polar-bears` = `href="polar-bears"`) and `../` (e.g., `polar‑bears` -> `main` = `href="../"` (you can put other folders after the `../`)) respectively.
