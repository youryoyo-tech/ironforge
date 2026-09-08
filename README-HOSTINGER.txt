IRONFORGE ATHLETIC CLUB — HOW TO PUT THIS WEBSITE ONLINE ON HOSTINGER
=====================================================================

What is in this ZIP
-------------------
Everything the website needs: all 9 pages, images, styles, scripts,
the favicon, robots.txt and an .htaccess file for clean page addresses.
No extra software, no server setup, nothing to install.

Steps
-----
1. Log in to Hostinger -> hPanel -> your website -> "File Manager".
2. Open the folder named  public_html
3. Delete anything already inside it (for example the default
   "default.php" or "index.html" placeholder page).
4. Click Upload and upload this ZIP file into public_html.
5. Right-click the uploaded ZIP -> "Extract" -> extract into public_html.
   IMPORTANT: the files (index.html, assets, about, contact, ...) must sit
   DIRECTLY inside public_html — not inside an extra sub-folder.
   If they landed in a sub-folder, move them up one level and delete the
   empty folder.
6. Delete the ZIP file from public_html when the extraction is done.
7. Visit your domain. The site is live.

After extracting, public_html should look like this:
  public_html/
    index.html
    .htaccess
    favicon.ico
    robots.txt
    assets/          (images, styles, scripts)
    about/index.html
    classes/index.html
    contact/index.html
    faq/index.html
    gallery/index.html
    membership/index.html
    schedule/index.html
    trainers/index.html

Notes
-----
* Make sure hidden files are visible in File Manager (Settings -> "Show
  hidden files") so that .htaccess is uploaded/extracted too. It keeps
  addresses like yourdomain.com/about working.
* Turn on the free SSL certificate in hPanel so the site loads on https.
* The signup, booking and contact forms show a confirmation on screen but
  do not yet send you an email. Tell me if you want real email delivery
  or a database and I will connect it.
* The club name, address, phone number, email and opening hours are
  realistic stand-ins. Send me your real details and I will update them.
