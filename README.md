# assignment7-project
Create a new project and its corresponding GitHub repository named assignment7-project
Make sure that:

The folder /structure is created inside of the container as the user root with permissions 777

That the user sync creates the folder /structure/sync-work

That the user nobody creates the folder /structure/nobody-work

That the user collin exists in the container

That the port 80 is exposed

That the httpd service is installed and executed at the container run with

ENTRYPOINT /usr/sbin/httpd -DFOREGROUND

That the file `/var/www/html/index.html` exists and has the text "Containers are easy!" in it.
