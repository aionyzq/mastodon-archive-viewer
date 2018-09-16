# mastodon-archive-to-html
A python script to take a mastodon archive and convert it into a human-readable webpage for viewing

# Features:
* organizes your old posts into a conveniently readable timeline
* includes media attachments in posts
* Preserves content warnings/summaries
* Uses the header.png from the archive as the background
* Uses the avatar.png from the archive as the avatar next to your old posts

# Usage
Just drop the "html_from_archive.py" script in the root of the archive (the folder that has "outbox.json" and "media_attachments" in it) and run it using python3. Open the resulting "processed_archive.html" file in your web browser.
