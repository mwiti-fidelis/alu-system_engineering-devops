SSH Configuration Project

This project focuses on automating SSH key generation, client-side configuration, and server access management using Bash scripts.

File Descriptions

File  Description 
`0-use_a_private_key` Connects to a server using the `~/.ssh/school` private key. 
`1-create_ssh_key_pair`  Generates a 4096-bit RSA key pair named `school` with passphrase `betty`.
`2-ssh_config` Configures the SSH client to use a specific key and disable password logins. 
`3-setup_web_static`  Appends a public key to the server's `authorized_keys` to grant access. 

Usage
Ensure all scripts have executable permissions:
