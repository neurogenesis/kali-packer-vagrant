# Kali Packer Vagrant

This project is a simplified way to generate a
[Kali Linux](https://www.kali.org/) virtual machine image supported
by [Vagrant](https://www.vagrantup.com/) by building it on-the-fly
with [Packer](https://packer.io/).

This is useful when you are paranoid about using a non-official virtual
machine image because you do not know what has been bundled with it. This
tool uses the official ISO from Kali, and open sources the build process
so you know exactly what you are getting.

## Getting Started

Run ``make deps`` to find out what tools you need.  At a minimum, you will
need the following:

* Vagrant
* Packer
* Kali Linux ISO

Other dependencies and tools may exist, so please do not rely on this
list as an exhaustive resource.

## License

This project is open source.

Please see the [LICENSE](LICENSE) file for more information.
