These are updated to allow us to change to the latest Apache - 2.4.65

After replacing the original conf files...

Syntax check via httpd.exe -t

Runtime check is to testart Apache and hit a quick phpinfo() page over HTTPS to confirm PHP executes (not downloads)