# checkmk_ansible_modules

## requirements

1. Ruby must be installed and the ruby gem ansible_module Version >= 0.9.4 (Tsutomu Kuroda).

```
$ sudo gem install ansible_module
```

2. clone this repository

```
cd /<pathToGitClone>
git clone https://github.com/ogaida/checkmk_ansible_modules
```

3. link to the modules

`/etc/ansible/ansible.cfg`

```
[defaults]
library = /<pathToGitClone>/checkmk_ansible_modules/modules
```
