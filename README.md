# vipaccess

**vip** is a bash shell script to replace the use of the Symantec VIP Access app to get one time passwords.

It expects you to have used Symantec VIP Access to have created the keychain that has the token for generating one time passwords.

This script also requires `oathtool` which may be installed via brew:

    brew install oath-toolkit

This script is based on the the Expect script written by p120ph37 found at https://gist.github.com/p120ph37/8213727.

    USAGE: vip [-v] [-h]

        -v is the verbose flag and prints information as the script runs.
        -h is the help flag and prints this message.

        Command line replacement for the Symantec VIP Access GUI app.
        Echoes and copies to the copy/paste buffer the one time password
        that the Symantec VIP Access GUI app would provide.
