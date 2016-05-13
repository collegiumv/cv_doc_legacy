---
title: Carbon
layout: default
---

Carbon is the lounge SSH jump host. Carbon allows you to establish a secure connection to the lounge network, as well as run certain low-overhead text mode programs such as an IRC client. The benefit of this is that you can access your CV files and remotely control your account from anywhere.

To connect to Carbon you will need to install a public key.

To install a public key run at any terminal prompt:

`modpubkey`

This command will open your editor of choice with an authorized_keys file.  Save and close to update your new public key.

Users with existing keys can continue to use their keys with no interruption.

If you are using Putty on windows, you will have to create an authorized_keys file: ~/.ssh/authorized_keys. 

Download and use puttygen to create the keys, and copy the public key generated in the putty box to the authorized_keys file. Then you can save your putty private key to your windows computer. 

In order to use the keys, expand the SSH menu on the side of the putty window and click "auth". There you can choose to use the previously generated putty private key to connect to Carbon.
