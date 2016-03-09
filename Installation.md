Installation Instructions for MechEdit

# System Requirements #

This software requires PHP5 to operate.  It does not support PHP4.

**MySQL is NOT required.**

# Quick Installation #

Quick Installation
  * Unzip files and upload to server
  * Modify the configure.php in the root directory.  **make sure you place the data directory in a non-public directory**
> > Permissions on data directory should be 777 so php can access it.
  * Login with default login/password which is admin/adminpass

# Using The Software #

So far the software only works with HTML pages.  You simply need to add class="clienteditor" to the tags you want your client to edit.

After you have defined this in the HTML as the admin (admin/adminpass) you'll need to setup the site.  It requires the FTP login and password for the site.  After that you'll need to add pages through the same interface.  Simply reselect the site and add pages.

Once you add the pages, then your editor can use the software.  They can login with (editor/editorpass) and edit pages.  They will not have access to add/remove sites.

The page edit interface allows the editor, or the admin the ability to edit the pages through the interface.

Since the software uses XHR, page updates take place the moment you click save.  This results in the FTP connection being made, then the changes updated.