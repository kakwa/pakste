Additional Information
----------------------

GPG Key Management
==================

Packages are signed with a GPG key. Here are essential commands for key management:

.. sourcecode:: bash

    # Generate a new GPG key
    $ gpg --gen-key

    # List available keys
    $ gpg -K

    # Export private key (for multiple build hosts)
    $ gpg --export-secret-key -a "Your Name" > private.gpg

    # Import private key on another system
    $ gpg --import private.gpg

    # Import public key into apt (for testing)
    $ cat public.gpg | apt-key add -

    $ gpg --export-secret-key -a "kakwa" > priv.gpg
