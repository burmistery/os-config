keyboard --vckeymap=us --xlayouts='us'
lang en_US.UTF-8

authselect enable-feature with-fingerprint

network --bootproto=dhcp --device=link --activate

clearpart --all --initlabel
autopart

rootpw --lock

ostreecontainer --url=dhcr.io/burmistery/os-config:fedora44

reboot
