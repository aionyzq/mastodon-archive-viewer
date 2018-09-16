# mastodon-archive-to-html
A python script to take a mastodon archive and convert it into a human-readable webpage for viewing

# Features:
* organizes your old posts into a conveniently readable timeline
* includes media attachments in posts
* Preserves content warnings/summaries
* Uses the header from the archive as the background
* Uses the avatar from the archive as the avatar next to your old posts

# Usage
Make sure to [install the current version of python 3](https://www.python.org/) if you don't have it already.

To make a webpage to view your archive, just place the `html_from_archive.py` script in the root of the archive (the folder that has `outbox.json` and `media_attachments` in it) and run it using python3 

from the command line: `python3 html_from_archive.py`

You can also set it as executable and run it directly or, on Windows, right click and open it with python 3.

Open the resulting `processed_archive.html` file in your web browser.
