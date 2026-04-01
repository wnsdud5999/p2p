Put downloadable files in this folder.

`files.json` is used by the website to render links without using the GitHub API.
A GitHub Action updates `files.json` automatically on every push that changes `download/**`.

If your uploaded file is not showing yet:
1. Open the repository **Actions** tab and check `Update download manifest`.
2. Confirm `download/files.json` contains your filename.
3. Refresh the page after the workflow completes.
