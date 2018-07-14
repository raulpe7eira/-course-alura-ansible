# course-alura-ansible

Resultado do curso **[Ansible: sua infraestrutura como código](https://cursos.alura.com.br/course/infraestrutura-como-codigo-com-ansible)** da [Alura](https://alura.com.br).

## Anotações

### Rodar playbook

- Linha de comando c/ usuário e senha ([hosts](/raulpe7eira/course-alura-ansible/commit/8ff36d0e1b2d03fe1bce74f3dcf0ae3187e36a4e) s/ credenciais)
```bash
ansible-playbook provisioning.yml -u vagrant -i hosts --private-key .vagrant/machines/wordpress/virtualbox/private_key
```

- Linha de comando s/ usuário e senha ([hosts](/raulpe7eira/course-alura-ansible/commit/8ff36d0e1b2d03fe1bce74f3dcf0ae3187e36a4e) c/ credenciais)
```bash
ansible-playbook provisioning.yml -i hosts
```
