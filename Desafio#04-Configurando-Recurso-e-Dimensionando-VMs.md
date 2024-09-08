# Desafio - Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## Configuração e dimensionamento de VMs

### 1º passo
Vá na barra lateral do portal Azure, procure por 'Máquina virtual' e depois clique em '+ Criar'. Escolha o Grupo de Recursos, dê um nome para sua VM e escolha a região.

![image](https://github.com/user-attachments/assets/4e72c1c3-6f9e-4447-a5b0-702212f9adf9)

Ao clicar em 'Opções de disponibilidade' o menu dropdown oferecerá três opções. A depender do seu objetivo, se escolher a opção 'Conjunto Dimensionamento de Máquinas Virtuais', você poderá criar um novo 
conjunto para projetar uma arquitetura de aplicativo altamente disponível e escalável.

![image](https://github.com/user-attachments/assets/c22307cc-c384-44d5-8396-a6ca370f895e)


### 2º passo
Clique em 'Avançar: Disco' para configurar os dicos de armazenamento e criptografia. Garanta que a opção 'Excluiur com VM' esteja selecionada para não ter surpresas com custos ocultos depois.

![image](https://github.com/user-attachments/assets/29568062-295d-47c6-bbe7-1e9436cbe8eb)

### 3º passo
Avanace para a aba 'Rede', escolha uma redes ou crie uma nova no botão 'Criar novo'. Os endereços IP públicos e as NICs persistem independentemente da máquina virtual. Você pode optar por excluir
automaticamente o endereço IP público e a NIC quando a máquina virtual associada for excluída se marcar a opção.

![image](https://github.com/user-attachments/assets/5a820cfd-3c64-4e29-9abe-f180cf527163)

### 4º passo
Avance para a opção 'Gerenciamento'. Nesta aba, será tratada questões de segurança, acesso, desligamento automático, backup e atualizações do SO convidado.

![image](https://github.com/user-attachments/assets/b061c142-3033-4eeb-9829-f8259e7399c0)
![image](https://github.com/user-attachments/assets/fbae9fa8-fd22-4595-b4ae-0d4c07c962ab)

### 5º passo
Avance para 'Monitoramento'. Nesta aba você pode: habilitar 'Alertas' para ser notificado sobre eventos importantes que ocorrem em seu recurso, 'Diagnóstico' para solucionar problemas de falha de
inicialização de imagens personalizadas ou de plataforma e, por fim, 'Integridade' para habilitar o monitoramento de integridade para o conjunto de dimensionamento. 

![image](https://github.com/user-attachments/assets/b97b9f09-c981-472c-a246-3fe7f4e4309f)

### 6º passo
Na aba 'Avançado' você pode adicionar configuração, agentes, scripts ou aplicativos adicionais por meio de extensões da máquina virtual ou cloud-init.

![image](https://github.com/user-attachments/assets/626121d4-02de-44f9-9828-3aff29d61936)
![image](https://github.com/user-attachments/assets/881358cc-50d8-467c-978c-a52587c5f431)

### 7º passo
Em 'Marcas', classifique recursos e exiba o faturamento consolidado aplicando a mesma marca a vários recursos e grupos de recursos.

![image](https://github.com/user-attachments/assets/28022972-0616-43b1-b8ec-42eb399da39c)

### 8º passo
Agora chegou a hora de revisar toda a configuração feita até aqui, verificar o cursto mensal e finalmente criar a sua VM.

![image](https://github.com/user-attachments/assets/536060cf-2268-467a-b10b-6dcfc7eafa87)
