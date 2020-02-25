# ansible-home

- Installation:

```
git clone https://github.com/fresus/ansible-home 
cd ansible-home
ansible-playbook site.yml \
  -i "localhost," \
  -c local \
  -e ansible_python_interpreter=$(which python) \
  -D -K
```
