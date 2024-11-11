# XQ_AbalyzeSHEET

# Set up GitHub push with SSH keys.md
# https://gist.github.com/xirixiz/b6b0c6f4917ce17a90e00f9b60566278

# add ssh key into ssh-agent
# https://stackoverflow.com/questions/17846529/could-not-open-a-connection-to-your-authentication-agent
-----
linus@DESKTOP-TradingPC MINGW64 ~/.ssh
$ eval `ssh-agent.exe -s`
Agent pid 294

linus@DESKTOP-TradingPC MINGW64 ~/.ssh
$ ssh-add ~/.ssh/id_rsa
Enter passphrase for /c/Users/linus/.ssh/id_rsa:
Identity added: /c/Users/linus/.ssh/id_rsa (linushsao@gmail.com)

-----
