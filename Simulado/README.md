# Simulado SC-300

# Pergunta 1

Você tem um locatário do Azure Active Directory (Azure AD).
Você precisa revisar os logs de entrada do Azure AD para investigar as entradas que ocorreram no passado.
Por quanto tempo o Azure AD armazena eventos nos logs de entrada?

90 dias
14 dias 
30 dias
365 dias

R: 30 dias

Link: https://learn.microsoft.com/en-us/azure/active-directory/reports-monitoring/reference-reports-data-retention#how-long-does-azure-ad-store-the-data

# Pergunta 2

Sua empresa está planejando configurar a política de risco de entrada no Azure AD Identity Protection. Qual das opções a seguir deve ser implementada primeiro para garantir que os usuários obtenham acesso após a configuração da política de risco de entrada?

R: garanta que os usuarios configurem o MFA

explicaçao: Para o risco de entrada, os usuários devem configurar a autenticação multifator

</p>
<img src="https://user-images.githubusercontent.com/91704169/230601001-f1682831-e1b7-4c9f-8c24-42969379aa0e.jpg" max-width="100px" width="1000px" align="centter" alt="Lab04">

# Pergunta 3

Sua empresa está interessada em implementar um ambiente de segurança sem senha. Como arquiteto principal, você foi encarregado de pesquisar os métodos de autenticação sem senha que se integram ao Azure Active Directory. Qual das opções abaixo não é um método de autenticação válido para integração com o Azure Active Directory?



R: Aplicativos microsoft azure para IOS e Android

Explicação: O Aplicativo do Microsoft Azure para iOS e Android não é uma ferramenta válida para usar na integração de segurança sem senha com o Azure Active Directory. Esta escolha não atende aos seus requisitos.

# Pergunta 4

Sua organização está considerando permitir que os funcionários trabalhem remotamente e usem seus próprios dispositivos para acessar muitos dos recursos da organização. No entanto, para ajudar a proteger contra possíveis perdas de dados, sua organização precisa garantir que apenas aplicativos aprovados possam ser usados ​​para acessar os dados da empresa. O que você pode configurar para atender a esse requisito?

R: Politica de acesso condicional

link: https://learn.microsoft.com/pt-br/azure/active-directory/conditional-access/overview

# Pergunta 5

Sua organização está trabalhando com uma nova empresa de consultoria para ajudar no projeto, desenvolvimento e implantação de um novo serviço de TI. Os consultores ingressarão em sua organização em vários pontos ao longo do projeto e não saberão de quais permissões precisam ou de quem solicitar acesso. Como administrador de nuvem, o que você pode implementar para garantir que os consultores possam solicitar facilmente e obter todo o acesso de que precisam para realizar seu trabalho?

R: Gerenciamento de direitos do azure AD

Explicaçao: O Azure AD Entitlement Management é uma solução que permitirá aos administradores de nuvem criar pacotes de acesso que incluirão todas as permissões e funções necessárias para um determinado trabalho. Os consultores poderiam simplesmente solicitar acesso a esses pacotes para obter tudo o que é necessário para concluir suas tarefas diárias. Esta solução atende às suas necessidades.

link: https://learn.microsoft.com/pt-br/azure/active-directory/governance/entitlement-management-overview

# Pergunta 6

Atualmente, sua empresa tem usuários definidos como parte de seu locatário do Azure AD. Eles desejam bloquear os usuários automaticamente sempre que relatarem solicitações de MFA que não foram iniciadas por eles. Qual das opções a seguir pode ser configurada para esse requisito?

R: ALerta de fraude

Explicaçao: Isso pode ser configurado com o uso de alertas de fraude conforme mostrado abaixo

</p>
<img src="https://user-images.githubusercontent.com/91704169/230608219-a02e11e3-1293-4e97-9fa6-6143979be272.jpg" max-width="100px" width="1000px" align="centter" alt="alertadefraude">


Link: https://learn.microsoft.com/pt-br/azure/active-directory/authentication/howto-mfa-mfasettings </p>
Link: https://learn.microsoft.com/pt-br/partner-center/azure-fraud-notification

# Pergunta 6

Sua organização usa o Azure AD Entitlement Management há vários meses e você desenvolveu uma grande lista de vários pacotes de acesso. Devido ao número de pacotes de acesso que você possui, você precisa de uma maneira de organizar melhor os pacotes de acesso relacionados. O que você pode usar para agrupar recursos relacionados e acessar pacotes?

R: Catalogo

Explicaçao: Um catálogo é usado para agrupar recursos de gerenciamento de direitos e políticas de acesso. Esta escolha atende às suas necessidades.

# Pergunta 7

Sua organização deseja implementar os Termos de Uso do Azure Active Directory para exibir informações adequadamente aos usuários e exigir aceitação antes do uso de aplicativos corporativos. Selecione as licenças abaixo que fornecem acesso aos Termos de Uso do Azure Active Directory

R: E5 E3 P1 e P2

# Pergunta 8

Devido a uma aquisição recente da empresa, você herdou um novo locatário do Azure com 1 assinatura associada que você gerencia. A segurança foi negligenciada e você está procurando uma maneira rápida e fácil de habilitar várias configurações de segurança, como exigir que os usuários se registrem para autenticação multifator, bloquear protocolos de autenticação herdados e proteger atividades privilegiadas, como acesso ao portal do Azure. Qual é a melhor maneira de impor essas configurações com o mínimo de esforço administrativo?

R: Ativar padroes de segurança

# Pergunta 9

Qual dos seguintes comandos do PowerShell é usado para fornecer aos usuários uma inscrição de autoatendimento para o Azure Active Directory?

R: Set-MsolCompanySettings

# Pergunta 10

Sua empresa está pensando em implementar o Windows Hello como parte de suas iniciativas de segurança para eliminar as senhas de usuário. Onde estão armazenados os dados biométricos usados ​​para o Windows Hello?

R: Dispositivo Local

# Pergunta 11

Você precisa atender aos requisitos de autenticação para credenciais vazadas.
O que você deveria fazer?

R: Habilite Sicronizaçao de Hash de senha do Azure AD.

Explicaçao: Habilite a sincronização de hash de senha no Azure AD Connect.
Detecções de risco, como credenciais vazadas, exigem a presença de hashes de senha para que ocorra a detecção

Links: https://learn.microsoft.com/pt-br/azure/active-directory/identity-protection/overview-identity-protection
https://learn.microsoft.com/pt-br/azure/security/fundamentals/steps-secure-identity

# Pergunta 12

Sua rede contém um domínio do Active Directory local que sincroniza com um locatário do Azure Active Directory (Azure AD).
Os usuários entram em computadores que executam o Windows 10 e estão associados ao domínio.
Você planeja implementar o logon único contínuo do Azure AD (SSO contínuo do Azure AD).
Você precisa configurar os computadores com Windows 10 para dar suporte ao Azure AD Contínuo SSO.
O que você deveria fazer?

R: Modifique opçoes de zonda da Intranet

Explicaçao: Você pode distribuir gradualmente o SSO Contínuo para seus usuários usando as instruções fornecidas abaixo. Você começa adicionando a seguinte URL do Azure AD a todas as configurações de zona de intranet ou usuários selecionados usando a política de grupo no Active Directory:

https://learn.microsoft.com/pt-br/azure/active-directory/hybrid/how-to-connect-sso-quick-start

Além disso, você precisa habilitar uma configuração de diretiva de zona da intranet chamada Permitir atualizações na barra de status via script por meio da diretiva de grupo.

https://learn.microsoft.com/pt-br/azure/active-directory/saas-apps/iris-intranet-tutorial

# Pergunta 13

Você tem um locatário do Azure Active Directory (Azure AD) que usa políticas de acesso condicional.
Você planeja usar informações de segurança e gerenciamento de eventos (SIEM) de terceiros para analisar o uso de acesso condicional.
Você precisa baixar o log do Azure AD usando o portal administrativo. O arquivo de log deve conter alterações nas políticas de acesso condicional.
O que você deve exportar do Azure AD?

R: Logs de auditoria no formato Json

Explicaçao: Os logs de auditoria mostram que as políticas de fato foram alteradas (testadas no locatário), apenas os logins mostram que o acesso foi concedido/negado

Link: https://learn.microsoft.com/pt-br/azure/active-directory/reports-monitoring/concept-audit-logs

# Pergunta 14

Sua organização tem trabalhado em várias novas políticas de acesso condicional em um esforço para melhorar sua postura de segurança atual. Como administrador da nuvem, você está preocupado em habilitar várias políticas, pois não quer correr o risco de bloquear o acesso dos usuários errados aos aplicativos. Qual é a maneira mais fácil de ver o impacto de suas políticas sem afetar os usuários reais? Sua resposta deve exigir um esforço administrativo mínimo.

R: User politica de What If de Acesso Condicional

Explocação: A Política What If de Acesso Condicional gera um relatório que detalha o impacto da política de acesso condicional caso ela esteja em execução. Esta é uma maneira de baixo esforço administrativo para testar suas políticas de acesso condicional.

</p>
<img src="https://user-images.githubusercontent.com/91704169/230628216-e6306eae-58eb-4489-8a05-2386651ff54a.png" max-width="100px" width="1000px" align="centter" alt="Lab04">
