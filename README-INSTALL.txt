TEACHER KHEN — HOW TO INSTALL AND UPDATE GUIDES

INSTALL (GitHub website repository)
1. Back up your current index.html, games.js, script.js and style.css.
2. Upload the four files from this package to the root of your website repository.
3. Upload the entire guides folder, including all 22 JSON files.
4. Keep your existing logo, image, and other website assets unchanged.
5. Wait for GitHub Pages to publish. Refresh your site, then click a game card.
6. Test free games, premium locked games, and a premium account.

HOW TO EDIT A GUIDE
1. Open guides/monster-egg.json (or the appropriate game guide) in GitHub.
2. Click the pencil icon to edit.
3. Change description, steps, or buttons. Keep quotation marks and commas valid.
4. To add a video, paste a specific YouTube Shorts URL in the video field.
5. Commit changes. Refresh the website after publishing.

HOW TO ADD A NEW GAME
1. Add a new game object to the games array in games.js as usual.
2. Add a property: guide: "guides/my-new-game.json",
3. Copy an existing guide JSON file and rename it my-new-game.json.
4. Edit title, description, steps, buttons, jsonHelp, and video.
5. Commit both files to GitHub. No further HTML or CSS editing needed.

VIDEO RULES
- For a specific YouTube Short: "video": "https://www.youtube.com/shorts/VIDEO_ID"
- No video: "video": ""
- Phonics Race currently uses videoChannel because you supplied the Shorts channel, not a specific video.

IMPORTANT
- Guide JSON files explain the game; they are NOT the game-data JSON files teachers export.
- Guides are public, including premium game guides. Premium game access remains checked.
- Some instructions are general because individual game source files were not provided.
  Review each guide against its actual game controls before publishing.
- If an existing game does not support export/import, set jsonHelp to false.
- The supplied HTML references games.js and script.js; the uploaded script(1).js was packaged as script.js.
