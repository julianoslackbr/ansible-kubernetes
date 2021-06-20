# ansible-kubernetes
Exemplo de criação de manifests e deploy utilizando ansible

## obrigatorio
```bash
pip3 install pip --upgrade
pip3 install kubernetes==11.0.0 openshift==0.11.0
pip3 install ansible==2.9

```
## criando variaveis
```bash
ansible-playbook sample-playbook-createvars.yml
```

## criando manifests e efetuando o deploy de uma app
```bash
ansible-playbook sample-playbook-k8s.yml
```

## criando manifests e efetuando o deploy de um cronjob
```bash
ansible-playbook sample-playbook-k8s.yml
```

## variaveis opcionais

## variaveis obrigatorias
