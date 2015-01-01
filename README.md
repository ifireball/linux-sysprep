linux-sysprep
=============

'linux-sysprep.sh' is a small shell script meant to be used for a similar
purpose to the 'sysprep' tool used by windows sysadmins. It is meant to be run
on an installed system to remove all system-specific configuration data and make
it ready to be used as an image provisioned into other hosts.

Running this script renders a system mostly unusable until the next time it
boots, therefore it is highly recommended to shut down the system after running
it.

Disclaimer: As it stands, this script had only been tested for use in RHEL7
systems provisioned on top the oVirt virtualization environment. It likely that
it will function properly on similar CentOS and Fedora systems. It will also not
blow up on other Linux systems, but it may not achieve the desired
functionality.

Patches for enhancing compatibility with other Linux versions are welcome!

