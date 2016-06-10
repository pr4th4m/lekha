#### Tips and Tricks

- Add local public key to remote ssh authorized keys

        cat ~/.ssh/id_rsa.pub | ssh user@hostname 'cat >> .ssh/authorized_keys'
