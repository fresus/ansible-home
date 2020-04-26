# ansible-home

- Installation:

```
git clone https://github.com/fresus/ansible-home 
cd ansible-home
ansible-playbook site.yml \
  -i inventories/localhost \
  -e ansible_python_interpreter=$(which python) \
  -D -K
```
