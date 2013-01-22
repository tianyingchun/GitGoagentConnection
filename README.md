GitGoagentConnection
====================

how to use github on windows with goagent proxy

Recenlty we can't submit code change using github client on windows

It seems we must using proxy to access git repository in china.

please simply following below instructions:

1. prepare goagent proxy client server

2. open git command line. and type below command.
   make sure your git repository using https://github..... protocal
   such as https://github.com/xxxx/JqueryPlugins.git
3. set http proxy for git
   > git config --global http.proxy 127.0.0.1:8087   (Goagent proxy server)
4. cloes ssl verify of  git.
   > git config --global http.sslVerify false


and now you can using git hub client on windows. Don't forgot lunched your goagent proxy service.

