For correct work ansible need exchange key for ssh

ssh-keygen -t rsa -b 4096 # Generate keygen

ssh-copy-id root@IP_SERVER # Send key on subordinate server
