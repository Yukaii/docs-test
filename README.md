How to make a doc site on GitHub with HackMD
===

1. Clone or fork this repo on GitHub
2. Change the `baseurl` to your repo name in `_config.yml`
3. Open new branch named `gh-pages` and push to your GitHub remote (e.g. `git branch gh-pages && git push origin gh-pages`)
4. Ensure you setup GitHub Pages source uses `gh-pages` branch
5. Create a new note on HackMD
6. Select `Pull from GitHub` and select your repo, `master` branch and select `README.md` from the file dropdown then click `Pull`
7. Modify the content on HackMD
8. Select `Versions` on the top right menu, click `Push to GitHub`
9. Fill the new Version name and click `Push`
10. Wait for GitHub Actions build your doc site
