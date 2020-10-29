# Ansible Role: Varnishncsa

Configures the [Varnish HTTP Cache](https://varnish-cache.org/) NCSA Module on RedHat/CentOS or Debian/Ubuntu Linux.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    varnish_package_name: "varnish"

Varnish package name you want to install. See `apt-cache policy varnish` or `yum list varnish` for a listing of available candidates.

    varnishncsa_systemd_config_file: varnishncsa.service.j2

Varnishncsa config file location

## License

MIT / BSD

## Author Information

This role was created from geerlingguy role which was created from the role in 2014 by [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
