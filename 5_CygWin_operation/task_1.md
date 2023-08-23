The command or sequence of commands that succeeded in obtaining the desired logs:

> $ cd logs/2019/12 
> grep -R "^233.201."

Logs:
> apache_2019-12-18.txt:233.201.188.154 - - [18/12/2019:21:46:01 +0000] "DELETE /events HTTP/1.1" 403 3971
> apache_2019-12-21.txt:233.201.182.9 - - [21/12/2019:21:56:20 +0000] "PATCH /users HTTP/1.1" 400 4118

