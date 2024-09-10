# Desafio 08 - Gerenciando Políticas em Acessos Azure

## Portal de Confiança do Serviço
🔗 Acesse o portal: https://servicetrust.microsoft.com

![image](https://github.com/user-attachments/assets/67b14bb5-87d5-46e4-b240-c136eceedbc2)

O Portal de Confiança do Serviço é uma plataforma da Microsoft que oferece informações detalhadas sobre como a Microsoft garante a segurança, privacidade e conformidade dos seus serviços em nuvem. Ele é uma central de transparência para clientes que desejam garantir que os serviços que utilizam estão de acordo com requisitos regulatórios e de segurança.

<b>Principais Recursos do Portal de Confiança do Serviço:</b>

1. <b>Documentos de Conformidade:</b><br>
A Microsoft disponibiliza relatórios de auditorias, certificações e atestados de conformidade com padrões globais, como ISO, SOC, GDPR, entre outros. Esses documentos ajudam as empresas a entender como a Microsoft cumpre as obrigações regulatórias.
2. <b>Recursos de Segurança e Privacidade:</b><br>
Informações sobre as práticas de segurança e proteção de dados adotadas pela Microsoft, como criptografia de dados, gerenciamento de identidade e controle de acesso.
3. <b>Modelos e Ferramentas de Avaliação de Riscos:</b><br>
O portal oferece ferramentas e modelos para que as empresas avaliem o nível de risco de seus dados e sistemas ao utilizar os serviços de nuvem da Microsoft, auxiliando na tomada de decisão.
4. <b>Guia de Implementação de Conformidade:</b><br>
Fornece orientações sobre como utilizar os serviços de nuvem da Microsoft para atender a padrões de conformidade específicos, como HIPAA, GDPR e outros.
5. <b>Paineis de Conformidade e Segurança:</b><br>
Os clientes podem acessar dashboards que fornecem uma visão clara sobre o status de conformidade dos serviços de nuvem que estão usando, permitindo monitoramento contínuo.

Essas ferramentas garantem que as organizações que usam a nuvem Microsoft possam operar em conformidade com regulamentações rigorosas e manter um alto padrão de segurança e privacidade de dados.

## Azure Policy

![image](https://github.com/user-attachments/assets/f445be09-ad92-4137-b547-173207f4582b)

O Azure Policy é uma solução de governança no Azure que permite criar, atribuir e gerenciar políticas em sua infraestrutura de nuvem. Essas políticas garantem que seus recursos estejam em conformidade com regras e práticas estabelecidas, permitindo controle sobre o que pode ou não ser implementado, bem como a forma como os recursos são configurados. Ele ajuda a manter a governança em larga escala e evitar alterações indesejadas que possam afetar a segurança ou o desempenho dos sistemas.

Para exemplificar uma forma de uso do Policy, vá até um Grupo de Recursos e procure por 'Bloqueios' no menu da barra lateral esquerda. Este será um bloqueio a nível de Grupo de Recursos.

![image](https://github.com/user-attachments/assets/77178bac-55ef-4efc-a066-cf685af26d8c)

Clique em 'Adicionar', dê um nome para o seu bloquio e escolha no menu dropdown o tipo que deseja. Clique em 'OK'.

![image](https://github.com/user-attachments/assets/bcb1060f-6afe-4a1e-b16a-c7d727a3c0f5)

Volte para Visão Geral do seu Grupo de Recursos e escolha um dos recursos listados para testar. Clique no recurso e vá novamente em 'Bloqueios' no menu lateral. Dentro dessa opção aparecerá listado o bloqueio adicionado anteriormente ao Grupo de Recursos.

![image](https://github.com/user-attachments/assets/6ada3c01-371e-4e2f-a3cc-8e397a6e3411)

Ao realizar o teste de exclusão do recurso a seginte mensagem aparecerá:

![image](https://github.com/user-attachments/assets/eabce29b-cfb1-4c1c-90b1-9a05ec978690)

## Microsoft Purview

![image](https://github.com/user-attachments/assets/131a3055-45ce-4e20-84a8-f5f20e1926d6)

O Microsoft Purview é uma plataforma de governança unificada que auxilia as organizações na gestão e proteção de dados em diferentes ambientes, como nuvem, on-premises e sistemas híbridos. Ele combina ferramentas de governança, conformidade e segurança de dados, permitindo uma visão centralizada e de ponta a ponta dos dados.

Acesse o Purview no Portal Azure através da barra de pesquisa. Seu primeiro acesso será assim:

![image](https://github.com/user-attachments/assets/dc2dd475-1b8c-415f-8899-dea71cc69e49)

Clique em '+ Criar', preencha as informações do seu projeto, dê um nome para a conta Purview e coloqe sua localização. Clique em 'Examinar + Criar'.

![image](https://github.com/user-attachments/assets/ed34cff0-d464-41ea-bfe1-bd047234bdb3)

Volte para o painel do Purview, clique na conta que acabamos de criar e será aberto um novo painel com links e outras opções de monitoramento de dados.

![image](https://github.com/user-attachments/assets/d75fa97d-62fe-4758-ae8d-c69c7bd34016)
