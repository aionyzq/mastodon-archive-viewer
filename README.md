# Mastodon Archive Viewer
A python script to take a mastodon archive and convert it into a human-readable webpage for viewing. Currently available as a python script or a hacky html file with some inline JS.

# Features:
* organizes your old posts into a conveniently readable timeline
* includes media attachments in posts
* Preserves content warnings/summaries
* Tries to use the header from the archive as the background
* Tries to use the avatar from the archive as the avatar next to your old posts

# Usage
<b>With Python:</b>
* To make a webpage to view your archive, just place the `html_from_archive.py` script in the root of the archive (the folder that has `outbox.json` and `media_attachments` in it) and run it using python3 
* * From the command line: `python3 html_from_archive.py`
* * You can also set it as executable and run it directly or, on Windows, right click and open it with python 3.
* Open the resulting `processed_archive.html` file in your web browser.
<b>Without Python:</b>

* Download the attached `archive_page.html` file and place it in the root of the archive (the folder that has `outbox.json` and `media_attachments` in it).
* Next open `archive_page.html` in your web browser. It will attempt to load your archive automatically. If it fails you'll just need to browse for and open the `outbox.json` file from within the page and it will load it.
