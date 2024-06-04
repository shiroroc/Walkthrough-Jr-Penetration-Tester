Simple enough, this section provides the introduction to favicon, a small icon displayed in the browser's address bar or tab used for branding a website
OWASP host a database of common framework icons that you can use to check against the targets favicon https://wiki.owasp.org/index.php/OWASP_favicon_database.
Open the site- https://static-labs.tryhackme.cloud/sites/favicon/
As already given, run the command: curl https://static-labs.tryhackme.cloud/sites/favicon/images/favicon.ico | md5sum
![image](https://github.com/shiroroc/Walkthrough-Jr-Penetration-Tester/assets/166932167/9cfab28c-2f8d-4190-bb36-a2d48c8dfaaf)
Now, we have the hash for the site, and the instructions are:
If you run the following command on the AttackBox, it will download the favicon and get its md5 hash value which you can then lookup on the
https://wiki.owasp.org/index.php/OWASP_favicon_database.
![image](https://github.com/shiroroc/Walkthrough-Jr-Penetration-Tester/assets/166932167/2bdd4142-36ba-49ec-9d05-f9b6f12fdf50)

Flag: cgiirc
