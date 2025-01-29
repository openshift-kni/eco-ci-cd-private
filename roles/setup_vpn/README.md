setup_vpn
=========

Sets up a persistent `openconnect` vpn process using `tmux`

Requirements
------------

Packages

- tmux
- openconnect

Role Variables
--------------


| Variable                | Required | Default | Choices                   | Comments                                 |
|-------------------------|----------|---------|---------------------------|------------------------------------------|
| tun_name                | yes      |         |                           |                                          |
| vpn_username            | yes      |         |                           |                                          |
| vpn_password            | yes      |         |                           |                                          |
| vpn_url                 | yes      |         |                           |                                          |
