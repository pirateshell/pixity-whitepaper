# Pixity Whitepaper Readme

This readme should get you started with contributing to this whitepaper. Everything is based on Material for MKDocs so if you are interested in how to use it, see the [documentation](https://www.mkdocs.org/).

## Steps to start contributing
1. Contact me for access to the repository so you can edit and commit to it.
2. Make sure to install Python, PIP and Material for MKDocs.
3. If you want to work in Visual Studio Code or other code editor:
  - Pull the repository.
  - Open a terminal / cmd in the folder.
  - Type `.\venv\Scripts\activate` if on Windows and `source /venv/bin/activate` if on Mac to activate the Python environment.
  - After it's active type `mkdocs serve` which will serve the doc live in your browser at the `http://127.0.0.1:8000/` url.
  - You are ready to start adding new pages or editing existing ones! Your changes will be shown live at the local URL when you save.
4. If you want to work from GitHub:
  - Simply edit the md files directly in the repo md editor or add new ones the same way.
5. After you are done with your edits, commit and push them and they will automatically update at `https://pirateshell.github.io/pixity-whitepaper/`.

# Editing & Adding pages
All the existing pages are md files in the `docs` folder. Editing them is as simple as editing those md files.

Adding a new page is as simple as adding a new md file to the `docs` folder. If you want to group pages, simply add a new subfolder and add your pages there. See how I have done the Pixity section.

## Adding pages to the navigation
If you want to add pages to the navigation in a custom way (not just ordered alphabetically), you can do so by changing the `mkdocs.yml` file specifically the `nav` section, where you can add new pages and page groups like I have done already.
