
# Ansible Role: CNI-Plugins

An Ansible Role that install [cni-plugins](https://github.com/containernetworking/plugins/tree/master/plugins) on hosts.

## Requirements

This is role works only on linux distributions currently.

## Role Variables

All variables are also listed in default values.

| Variable                                   | Required | Default                | Description
|--------------------------------------------|----------|------------------------|------------
| cni_plugin_dir | yes | /opt/cni/bin | directory where downloaded file and plugins are stored
| cni_plugin_release_url | yes | https://github.com/containernetworking/plugins/releases/download | Release url for cni plugins
| cni_plugin_release_version | yes | v1.0.0 | Verion of cni-plugins

## Dependencies

None.

## License

GPLv3

## Author Information

* Sören Henning
