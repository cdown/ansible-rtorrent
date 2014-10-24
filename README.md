This repository contains an [Ansible][] playbook to quickly set up an rtorrent
machine.

[Ansible]: http://ansible.com

## Quick setup

Run on the machine:

    curl -Lo /tmp/setup https://bit.ly/1FMk6CC
    $EDITOR /tmp/setup # don't just run arbitrary scripts from the internet...
    chmod a+x /tmp/setup
    /tmp/setup
