## SET PASSWORDLESS AUTHENTICATION ##
```bash
ssh-copy-id -f "-o IdentityFile <PATH TO PEM FILE>" ubuntu@<INSTANCE-PUBLIC-IP>
```
ssh-copy-id: This is the command used to copy your public key to a remote machine.
-f: This flag forces the copying of keys, which can be useful if you have keys already set up and want to overwrite them.
"-o IdentityFile ": This option specifies the identity file (private key) to use for the connection. The -o flag passes this option to the underlying ssh command.
ubuntu@: This is the username (ubuntu) and the IP address of the remote server you want to access.
