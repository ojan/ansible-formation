# ansible-formation
code for ansible formation


```bash
ssh-keygen -o -a 100 -t ed25519 -f ./env/ssh/keys/id_ed25519 -C "ansible@klanik.com"
```

```bash
ssh -i env/ssh/keys/id_ed25519 ansible@192.168.1.32
```

```bash
python3 -m venv ~/.ansible/latest
source ~/.ansible/latest/bin/activate
pip install ansible
```

```bash
ansible localhost -m ansible.builtin.setup
ansible localhost -m ansible.builtin.ping
```

```bash
ansible-playbook ansible-init.yml
```
