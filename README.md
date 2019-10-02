#  Accept GitHub Invitations (agi)

A bash script to make accepting large numbers of GitHub invitations much simpler.

Tested using bash 5 and python 3

    ./agi --help
    Accept GitHub Invitations
    Usage: ./agi [-l|--(no-)list] [-a|--(no-)accept-all] [-p|--password <arg>] [-h|--help] <github-user>
        <github-user>: GitHub username
        -l, --list, --no-list: List all active invitations (off by default)
        -a, --accept-all, --no-accept-all: Accept all active invitations.  If off, interactive mode is used. (off by default)
        -p, --password: GitHub password or personal access token (no default)
        -h, --help: Prints help
