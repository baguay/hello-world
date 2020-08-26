# Hello, world!
baguay@LIBRWKSPC237057 MINGW64 ~/hello-world (master)
$ git remote add origin git@github.com:baguay/hello-world.git

baguay@LIBRWKSPC237057 MINGW64 ~/hello-world (master)
$ git push -u origin master
The authenticity of host 'github.com (140.82.114.4)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com,140.82.114.4' (RSA) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

baguay@LIBRWKSPC237057 MINGW64 ~/hello-world (master)
$ git remote add origin https://github.com/baguay/hello-world.git
fatal: remote origin already exists.

baguay@LIBRWKSPC237057 MINGW64 ~/hello-world (master)
