# devops-azure-study
Guia de Máquina Virtual no Azure
Objetivo
Documentar o processo de criação e configuração de VMs no Azure para estudos DevOps.

Passo a Passo
1. Criando a VM
Acesse o Portal Azure
Clique em "Criar um recurso" > "Máquina Virtual"
Preencha os parâmetros básicos:
Grupo de recursos: DIO_25
Nome da VM: my-devops-vm
Região: (US) West US
Imagem: Ubuntu Server 24.04 LTS -x64 Gen2
Tamanho: Standard_B1s (1 vCPU, 1 GiB memória)
2. Configurações de Rede
Criar nova rede virtual
Habilitar porta SSH (22)
IP público básico
3. Gerenciamento
Monitoramento básico habilitado
Sem autenticação Azure AD
