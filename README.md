# git-multiple-identities
Multiple Git identities using SSH

Usage
------
When using Git with multiple target hostnames or urls, you can specify the precise public keys you wish to use.  
If you use a single service, but have multiple accounts or projects on that same service, and which to use separate public keys for the same service, there are methods to accomplish this using unique git url's in your SSH config.  This project offers some examples of how to accomplish each goal.  


Project Files
--------------
`git-multiple-identities/ssh-config.txt`  
* This file demonstrates how to construct a specific ssh public key for different services, as well as multiple accounts with the same service.  

`git-multiple-identities/git-remote-command-examples.txt`  
* This file demonstrates how to set and verify that you have correctly modified the `.git/config` url path/origin settings correctly.  

`git-multiple-identities/repo-git-config-examples.txt`  
* This file demonstrates what a `.git\config` for a repo with various reference scenarios might look like.  


