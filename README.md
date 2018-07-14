# course-alura-ansible

Resultado do curso **[Ansible: sua infraestrutura como código](https://cursos.alura.com.br/course/infraestrutura-como-codigo-com-ansible)** da [Alura](https://alura.com.br).

---

### Run playbook

- Command Line w/ user and password (hosts w/o credencials)
```bash
ansible-playbook provisioning.yml -u vagrant -i hosts --private-key .vagrant/machines/wordpress/virtualbox/private_key
```

- Command Line w/o user and password (hosts w/ credencials)
```bash
ansible-playbook provisioning.yml -i hosts
```
