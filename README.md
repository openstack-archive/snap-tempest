# Rally Snap

This repository contains the source code of the snap for the OpenStack benchmark
as a service, Rally.

## Installing this snap

The rally snap can be installed directly from the snap store:

    sudo snap install --edge rally

then setup the alias for rally-manage (this will automatically happen at some
point in the future):

    sudo snap alias rally rally-manage

and then initialize your local rally db:

    rally-manage db create

## Support

Please report any bugs related to this snap on
[Launchpad](https://bugs.launchpad.net/snap-rally/+filebug).

Alternatively you can find the OpenStack Snap team in `#openstack-snaps`
on Freenode IRC.
