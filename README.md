# Image-Manager---Shell-Upload-PoC
The ImageManager WordPress plugin was affected by a Shell Upload security vulnerability.

Preparation:
Replace wordpress_url with the target WordPress site.
Adjust the upload_endpoint if necessary (inspect the plugin code or observe its behavior to confirm the upload path).

Run:
Save the script as imagemanager_exploit.py.
Run: python3 imagemanager_exploit.py.
Post-Upload:

Once the script confirms upload success, access the shell at:

http://target-wordpress-site.com/wp-content/uploads/shell.php
