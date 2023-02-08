### Setup ssh for first time

Generating ssh keys for a new environment:

    ssh-keygen -t ed25519 -C "<email>"

Copy the public key from:

    cat ~/.ssh/id_ed25519.pub

Add the key to your github account:
https://github.com/settings/keys

Test the connection:

    ssh -T git@github.com

### Clone the course repository

    git clone git@github.com:VU-MIF-SE/dl.git
