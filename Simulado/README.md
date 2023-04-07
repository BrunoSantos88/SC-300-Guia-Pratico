# Simulado SC-300

#Pergunta 1

Você tem um locatário do Azure Active Directory (Azure AD).
Você precisa revisar os logs de entrada do Azure AD para investigar as entradas que ocorreram no passado.
Por quanto tempo o Azure AD armazena eventos nos logs de entrada?

90 dias
14 dias 
30 dias
365 dias

R: 30 dias

Link: https://learn.microsoft.com/en-us/azure/active-directory/reports-monitoring/reference-reports-data-retention#how-long-does-azure-ad-store-the-data

#Pergunta 2

Sua empresa está planejando configurar a política de risco de entrada no Azure AD Identity Protection. Qual das opções a seguir deve ser implementada primeiro para garantir que os usuários obtenham acesso após a configuração da política de risco de entrada?

R: garanta que os usuarios congigurem o MFA

explicaçao: Para o risco de entrada, os usuários devem configurar a autenticação multifator

</p>
<img src="https://user-images.githubusercontent.com/91704169/230601001-f1682831-e1b7-4c9f-8c24-42969379aa0e.jpg" max-width="100px" width="1000px" align="centter" alt="Lab04">

#Pergunta 3

Sua empresa está interessada em implementar um ambiente de segurança sem senha. Como arquiteto principal, você foi encarregado de pesquisar os métodos de autenticação sem senha que se integram ao Azure Active Directory. Qual das opções abaixo não é um método de autenticação válido para integração com o Azure Active Directory?



R: Aplicativos microsoft azure para IOS e Android

Explicação: O Aplicativo do Microsoft Azure para iOS e Android não é uma ferramenta válida para usar na integração de segurança sem senha com o Azure Active Directory. Esta escolha não atende aos seus requisitos.

#Pergunta 4

Sua organização está considerando permitir que os funcionários trabalhem remotamente e usem seus próprios dispositivos para acessar muitos dos recursos da organização. No entanto, para ajudar a proteger contra possíveis perdas de dados, sua organização precisa garantir que apenas aplicativos aprovados possam ser usados ​​para acessar os dados da empresa. O que você pode configurar para atender a esse requisito?

R: Politica de acesso condicional

link: https://learn.microsoft.com/pt-br/azure/active-directory/conditional-access/overview

#Pergunta 5

Sua organização está trabalhando com uma nova empresa de consultoria para ajudar no projeto, desenvolvimento e implantação de um novo serviço de TI. Os consultores ingressarão em sua organização em vários pontos ao longo do projeto e não saberão de quais permissões precisam ou de quem solicitar acesso. Como administrador de nuvem, o que você pode implementar para garantir que os consultores possam solicitar facilmente e obter todo o acesso de que precisam para realizar seu trabalho?

R: Gerenciamento de direitos do azure AD

Explicaçao: O Azure AD Entitlement Management é uma solução que permitirá aos administradores de nuvem criar pacotes de acesso que incluirão todas as permissões e funções necessárias para um determinado trabalho. Os consultores poderiam simplesmente solicitar acesso a esses pacotes para obter tudo o que é necessário para concluir suas tarefas diárias. Esta solução atende às suas necessidades.

link: https://learn.microsoft.com/pt-br/azure/active-directory/governance/entitlement-management-overview

#Pergunta 6

Atualmente, sua empresa tem usuários definidos como parte de seu locatário do Azure AD. Eles desejam bloquear os usuários automaticamente sempre que relatarem solicitações de MFA que não foram iniciadas por eles. Qual das opções a seguir pode ser configurada para esse requisito?

R: ALerta de fraude

Explicaçao: Isso pode ser configurado com o uso de alertas de fraude conforme mostrado abaixo

</p>
<img src="https://user-images.githubusercontent.com/91704169/230608219-a02e11e3-1293-4e97-9fa6-6143979be272.jpg" max-width="100px" width="1000px" align="centter" alt="alertadefraude">


Link: https://learn.microsoft.com/pt-br/azure/active-directory/authentication/howto-mfa-mfasettings </p>
Link: https://learn.microsoft.com/pt-br/partner-center/azure-fraud-notification
