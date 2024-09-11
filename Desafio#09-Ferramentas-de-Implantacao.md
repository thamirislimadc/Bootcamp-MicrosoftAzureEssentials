# Desafio 9 - Ferramentas de Implantação na Azure


## 🏹 Azure ARC
![image](https://github.com/user-attachments/assets/0fed7c54-cac4-49c5-b2bd-2f4caa71427f)

Azure Arc é uma plataforma que permite o gerenciamento centralizado de recursos em ambientes híbridos e multicloud, estendendo os serviços do Azure para qualquer infraestrutura. Com ele, é possível gerenciar servidores, clusters Kubernetes e bancos de dados que estão fora do Azure, utilizando as mesmas ferramentas de monitoramento, políticas e segurança.

Principais ferramentas e recursos do Azure Arc:
- <b>Gerenciamento de servidores:</b> Habilita a gestão de servidores físicos e máquinas virtuais fora do Azure.
- <b>Gerenciamento de Kubernetes:</b> Simplifica a orquestração de clusters Kubernetes locais e em nuvens externas.
- <b>Gerenciamento de dados:</b> Oferece serviços como o Azure SQL Managed Instance em ambientes on-premise.


## 💪 Azure ARM
![image](https://github.com/user-attachments/assets/67993071-1981-4880-b5aa-8ebfba44f988)

Azure Resource Manager (ARM) é a camada de gerenciamento que permite a administração e automação de recursos no Azure. Com o ARM, os usuários podem organizar, provisionar e monitorar serviços através de templates declarativos e consistentes.

Principais ferramentas e recursos do ARM:
- <b>Templates ARM:</b> Arquivos JSON que permitem a implementação automatizada e repetível de recursos no Azure.
- <b>Grupos de recursos:</b> Facilita a organização e gerenciamento de múltiplos serviços de maneira coesa.
- <b>Role-Based Access Control (RBAC):</b> Controle granular de permissões sobre os recursos.
- <b>Tags:</b> Etiquetas para categorizar e identificar recursos de forma eficiente.


### Cloud Shell
Cloud Shell é um terminal baseado em navegador que permite a execução de comandos diretamente no portal do Azure, sem precisar configurar um ambiente local. Ele oferece dois ambientes: Bash (para usuários de Linux) e PowerShell (para usuários de Windows), permitindo o gerenciamento de recursos do Azure por meio da linha de comando.

![image](https://github.com/user-attachments/assets/cb7f6b77-7da4-48ef-b64f-94ededae027a)

Como acessar o Cloud Shell no Portal do Azure:
1. Faça login no Portal do Azure.
2. No canto superior direito, clique no ícone de Cloud Shell (um ícone de terminal).
3. Escolha o ambiente de shell (Bash ou PowerShell).
4. O Cloud Shell será iniciado e estará pronto para uso diretamente no navegador.

### Bicep
🔗 Treine a linguagem Bicep no Playgrond: https://azure.github.io/bicep <br>

Bicep é uma linguagem declarativa de código-fonte aberto projetada para simplificar a criação de templates de infraestrutura como código (IaC) no Azure. Ele serve como uma alternativa mais simples e concisa aos arquivos JSON utilizados nos Azure Resource Manager (ARM) Templates, facilitando o provisionamento de recursos na nuvem.

![image](https://github.com/user-attachments/assets/c8ae826b-d539-4288-8800-cbe64ce91646)

Como acessar e usar o Bicep:
1. Pode ser utilizado diretamente no Azure CLI ou no Azure PowerShell.
2. Instalar a CLI Bicep para compilar os arquivos .bicep em templates ARM.
3. Pode ser integrado em pipelines CI/CD para automação de deploys.
