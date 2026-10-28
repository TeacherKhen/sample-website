TEACHER KHEN — GUIDE TROUBLESHOOTING

All 22 JSON guide files are present, valid JSON, and match games.js.
The uploaded index.html, script.js, games.js and style.css matched the ZIP.

IMPORTANT: If you double-click index.html in Windows, the browser uses file:// and normally blocks fetch() for local JSON files. This is NOT a folder error.

To test the site on your computer:
1. Open a terminal in the folder containing index.html.
2. Run: python -m http.server 8000
3. Open: http://localhost:8000/
4. Open: http://localhost:8000/guides/pacman-vocabulary-quest.json

To publish on GitHub Pages:
1. Upload the contents of this ZIP, including guides/ and all 22 JSON files, to the actual published branch/folder.
2. Commit changes and wait for deployment.
3. Check https://teacherkhen.com/guides/pacman-vocabulary-quest.json
4. If it returns 404, check the GitHub Pages publishing source and whether Cloudflare deploys a different repository.

This fix only adds clear diagnostic messages to games.js; the design and membership functions are unchanged.
