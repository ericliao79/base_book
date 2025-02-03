# ubuntu ansible base book

## Requirements

- ansible

mac

```bash
brew install ansible
```

## run

- cp env

```bash
cp inventory.example inventory
```

- update env ip

```bash
[ubuntu]
192.168.70.127 ansible_port=22 ansible_user=ubuntu
```

- run it

```bash
ansible-playbook -i inventory playbooks/playbook.yaml
```
