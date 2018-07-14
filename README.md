# course-alura-ansible

Resultado do curso **[Ansible: sua infraestrutura como código](https://cursos.alura.com.br/course/infraestrutura-como-codigo-com-ansible)** da [Alura](https://alura.com.br).

## anotações

### rodar playbook

- Linha de comando c/ usuário e senha (hosts s/ credenciais)
```bash
ansible-playbook provisioning.yml -u vagrant -i hosts --private-key .vagrant/machines/wordpress/virtualbox/private_key
```

- Linha de comando s/ usuário e senha (hosts c/ credenciais)
```bash
ansible-playbook provisioning.yml -i hosts
```
