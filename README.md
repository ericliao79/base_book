# ubuntu ansible base book

## Requirements

- ansible

mac

```bash
brew install ansible
```

## run

1. cp env

```bash
cp inventory.example inventory
```

2. update env ip

3. run it

```bash
ansible-playbook -i inventory playbooks/playbook.yml
```
