# 📒 Anotações do Projeto - Gerenciando Instâncias EC2 na AWS

## 🛠️ Comandos Simulados AWS CLI

### 1. Criar Instância EC2
```bash
aws ec2 run-instances \
  --image-id ami-12345678 \
  --count 1 \
  --instance-type t2.micro \
  --key-name minha-chave \
  --security-groups meu-grupo-seguranca

aws ec2 create-snapshot \
  --volume-id vol-12345678 \
  --description "Backup do servidor DIO"

aws ec2 create-image \
  --instance-id i-12345678 \
  --name "AMI-Servidor-DIO" \
  --description "Imagem personalizada para replicação"
````

## 🧩 Conclusão
Este documento complementa o README.md, trazendo exemplos práticos de comandos, boas práticas e reflexões sobre EC2, AMIs e Snapshots EBS.







  

