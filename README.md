wireguard-mesh
==============

Helper role to propagate [wg-meshconf](https://github.com/k4yt3x/wg-meshconf) configuration.

Setup
-----

You need to have a directory `wg-meshconf` with `output` directory (a result of `wg-meshconf genconfig`), files could be ansible-vault encrypted.


Integration
-----------

`wireguard-mesh` role is part of [k3s-space-harbor](https://github.com/riotkit-org/k3s-space-harbor#pre-setup-of-networking) project, you may want to setup Wireguard and K3s using space-harbor instructions.
