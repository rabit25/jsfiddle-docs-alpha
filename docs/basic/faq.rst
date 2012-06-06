==========================
Frequently Asked Questions
==========================

Code is working on jsFiddle, not on site/local machine
######################################################

Please compare the source on your page with the :ref:`result_draft`. Check 
if your script loads all the specified libraries (check for 404 errors using 
the web console in your browser). We do host some of the libraries, please
upload them to your site before using.

Be aware that scripts may not function properly when loaded in a browser from a local
machine as file:// (drag and drop from outside to inside browser for example)

How can I name a fiddle?
########################

You can name a fiddle by filling in the title in the :ref:`fiddle_settings-info` 
section of Fiddle Settings (Sidebar), but the URL / hashtag will remain the same.

What about a node/PHP/Python/ASP fiddle?
########################################

Our current goal is to help with front-end development. For back-end please 
use `Ideone <http://ideone.com/>`_ or `JSApps <http://jsapp.us/>`_.

Why jsFiddle is not working in IE6 (or other old browser)?
##########################################################

Editor is not designed to be working on old browsers. For testing purposes 
we've created the :ref:`result_draft` feature. It will also help with testing on 
mobile devices.

Why is my Papersript (paper.js) code not working?
#################################################
Make sure that paper.js has been added as a resource.  If you did not fork a working 
paperscript example, the paper.js resource must be added manually in (:ref:`add-resources`)
py pasting this link: https://raw.github.com/paperjs/paper.js/master/dist/paper.js 
Make sure your have followed all of the other requirements here:  :ref:`paperscript-hack`

