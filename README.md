# base ubuntu book

## Requirements

- ansible

mac

```bash
brew install ansible
```

## run

1. cp env

```bash
cp env.example env
```

2. update env ip

3. run it

```bash
ansible-playbook -i env playbook.yml
```