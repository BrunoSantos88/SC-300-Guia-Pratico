# Simulado SC-300

# Pergunta 1

Você tem um locatário do Azure Active Directory (Azure AD).
Você precisa revisar os logs de entrada do Azure AD para investigar as entradas que ocorreram no passado.
Por quanto tempo o Azure AD armazena eventos nos logs de entrada?

90 dias </p>
14 dias </p>
30 dias (correto) </p>
365 dias </p>

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

# Pergunta 7

Sua organização usa o Azure AD Entitlement Management há vários meses e você desenvolveu uma grande lista de vários pacotes de acesso. Devido ao número de pacotes de acesso que você possui, você precisa de uma maneira de organizar melhor os pacotes de acesso relacionados. O que você pode usar para agrupar recursos relacionados e acessar pacotes?

R: Catalogo

Explicaçao: Um catálogo é usado para agrupar recursos de gerenciamento de direitos e políticas de acesso. Esta escolha atende às suas necessidades.

# Pergunta 8

Sua organização deseja implementar os Termos de Uso do Azure Active Directory para exibir informações adequadamente aos usuários e exigir aceitação antes do uso de aplicativos corporativos. Selecione as licenças abaixo que fornecem acesso aos Termos de Uso do Azure Active Directory

R: E5 E3 P1 e P2

# Pergunta 9

Devido a uma aquisição recente da empresa, você herdou um novo locatário do Azure com 1 assinatura associada que você gerencia. A segurança foi negligenciada e você está procurando uma maneira rápida e fácil de habilitar várias configurações de segurança, como exigir que os usuários se registrem para autenticação multifator, bloquear protocolos de autenticação herdados e proteger atividades privilegiadas, como acesso ao portal do Azure. Qual é a melhor maneira de impor essas configurações com o mínimo de esforço administrativo?

R: Ativar padroes de segurança

# Pergunta 10

Qual dos seguintes comandos do PowerShell é usado para fornecer aos usuários uma inscrição de autoatendimento para o Azure Active Directory?

R: Set-MsolCompanySettings

# Pergunta 11

Sua empresa está pensando em implementar o Windows Hello como parte de suas iniciativas de segurança para eliminar as senhas de usuário. Onde estão armazenados os dados biométricos usados ​​para o Windows Hello?

R: Dispositivo Local

# Pergunta 12

Você precisa atender aos requisitos de autenticação para credenciais vazadas.
O que você deveria fazer?

R: Habilite Sicronizaçao de Hash de senha do Azure AD.

Explicaçao: Habilite a sincronização de hash de senha no Azure AD Connect.
Detecções de risco, como credenciais vazadas, exigem a presença de hashes de senha para que ocorra a detecção

Links: https://learn.microsoft.com/pt-br/azure/active-directory/identity-protection/overview-identity-protection

https://learn.microsoft.com/pt-br/azure/security/fundamentals/steps-secure-identity

# Pergunta 13

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

# Pergunta 14

Você tem um locatário do Azure Active Directory (Azure AD) que usa políticas de acesso condicional.
Você planeja usar informações de segurança e gerenciamento de eventos (SIEM) de terceiros para analisar o uso de acesso condicional.
Você precisa baixar o log do Azure AD usando o portal administrativo. O arquivo de log deve conter alterações nas políticas de acesso condicional.
O que você deve exportar do Azure AD?

R: Logs de auditoria no formato Json

Explicaçao: Os logs de auditoria mostram que as políticas de fato foram alteradas (testadas no locatário), apenas os logins mostram que o acesso foi concedido/negado

Link: https://learn.microsoft.com/pt-br/azure/active-directory/reports-monitoring/concept-audit-logs

# Pergunta 15

Sua organização tem trabalhado em várias novas políticas de acesso condicional em um esforço para melhorar sua postura de segurança atual. Como administrador da nuvem, você está preocupado em habilitar várias políticas, pois não quer correr o risco de bloquear o acesso dos usuários errados aos aplicativos. Qual é a maneira mais fácil de ver o impacto de suas políticas sem afetar os usuários reais? Sua resposta deve exigir um esforço administrativo mínimo.

R: User politica de What If de Acesso Condicional

Explocação: A Política What If de Acesso Condicional gera um relatório que detalha o impacto da política de acesso condicional caso ela esteja em execução. Esta é uma maneira de baixo esforço administrativo para testar suas políticas de acesso condicional.

</p>
<img src="https://user-images.githubusercontent.com/91704169/230628216-e6306eae-58eb-4489-8a05-2386651ff54a.png" max-width="100px" width="1000px" align="centter" alt="Lab04">

# Pergunta 16

A Zebra Corp tem a obrigação de realizar revisões de acesso trimestrais para todos os seus 100 funcionários na Organização. Desses 100 funcionários, 3 deles são administradores de nuvem com a função de administrador global e configurarão todas as revisões de acesso. Como um dos administradores de nuvem, você precisa garantir que a Zebra Corp tenha as licenças adequadas para dar suporte a essas revisões de acesso trimestrais. Sua organização deseja que apenas o Cloud Admin execute as revisões de acesso? Quantas licenças P2 premium do Azure você deve ter?

Selecionar: 1 - 100 - 97 - 3  - 0

R: 0 

Explicação
Como o Cloud Admin, que tem a função de administrador global, realizará todas as revisões de acesso, você não precisará de nenhuma licença do Azure AD Premium P2. O administrador global e o administrador do usuário não precisam ter uma licença P2 premium do Azure AD para configurar as revisões de acesso, fazer alterações de configuração ou aplicar decisões das revisões de acesso

# Pergunta 17

Sua empresa tem um locatário do Azure AD. Há vários usuários definidos no locatário. Há um determinado grupo de usuários que precisam ser registrados para autenticação multifator. Abaixo estão as restrições que eles têm

A maioria dos usuários compartilha computadores e pode entrar em diferentes sistemas diariamente
Os sistemas do cliente não estão habilitados para lidar com dados biométricos
Não podem fazer uso de dispositivos móveis para autenticação
Qual das opções a seguir pode ser usada para fins de autenticação multifator?

SMS </p>
MFA </p>
Token FIDO2  (correto) </p>
Windows hello </p>

Explicação
Aqui, como os dados biométricos não podem ser usados, não podemos usar o Windows Hello for Business.
Como os dispositivos móveis não são permitidos, não podemos usar o Microsoft Authenticator App ou SMS
Os usuários podem então fazer uso de tokens FIDO2 para fins de autenticação multifator

# Pergunta 18

Sua organização deseja usar as unidades administrativas do Azure AD para restringir o acesso de seus administradores de suporte técnico para garantir que eles só possam fornecer opções de suporte para usuários em suas regiões dedicadas. Que tipo de licença é necessário para usar as unidades de administração do Azure AD. Seu objetivo é minimizar o custo ao adquirir licenças.

Nivel Gratuito </p>
Azure AD P2  </p>
AZURE AD P1 (correto) </p>
MS365 E3 </p>

Explicação
A licença Azure AD P1 ou P2 é necessária para usar unidades administrativas. Para minimizar o custo, o Azure AD P1 seria a melhor solução.

# Pergunta 19

Sua empresa tem um locatário do Azure AD. O Azure AD Connect está sendo usado para sincronizar os usuários da instância do Active Directory local para o Azure AD.
A empresa possui um servidor VPN local. O servidor VPN não oferece suporte à autenticação multifator. Qual das opções a seguir pode ser usada para garantir que a autenticação multifator do Azure possa ser usada para conexões VPN?

R: NPS Servidores politica de Redes

Explicação
Aqui, o servidor de política de rede pode ser usado junto com o servidor VPN para oferecer autenticação multifator.

Link: https://learn.microsoft.com/pt-br/windows-server/networking/technologies/nps/nps-top

# Pergunta 20

Você tem um locatário do Azure Active Directory (Azure AD) que contém um usuário chamado SecAdmin1. SecAdmin1 é atribuído à função de administrador de segurança.
SecAdmin1 relata que ela não pode redefinir senhas do portal de proteção de identidade do Azure AD.
Você precisa garantir que SecAdmin1 possa gerenciar senhas e invalidar sessões em nome de usuários não administrativos. A solução deve usar o princípio do menor privilégio.
Qual função você deve atribuir a SecAdmin1?

Operador de Segurança  </p>
Autenticador de Indentificaçação Privilegiada  </p>
Administrador de Autenticaçao (correta)   </p>
Administrador de Helpdesk  </p>

Explicação
O Administrador de Autenticação pode acessar para visualizar, definir e redefinir informações do método de autenticação para qualquer usuário não administrador, enquanto o Administrador de Autenticação Privilegiada pode acessar para visualizar, definir e redefinir informações do método de autenticação para qualquer usuário (administrador ou não administrador).

Link: https://learn.microsoft.com/pt-br/azure/active-directory/roles/permissions-reference#helpdesk-administrator


# Pergunta 21

Você precisa realizar um convite em massa de usuários B2B do Azure. Qual das opções a seguir precisa ser mencionada para os usuários como parte do convite em massa? Escolha 2 respostas entre as opções abaixo

Url convidado (correta) </p>
Senha  </p>
mensagem de convite  </p>
Convite de calendario </p>
Endereço de email (correta) </p>

Explicação
Ao convidar usuários em massa, você deve mencionar o endereço de e-mail e o URL do convite.

Link: https://learn.microsoft.com/pt-br/azure/active-directory/external-identities/redemption-experience -->

# Pergunta 22

Sua empresa deseja usar os Termos do Azure AD para fornecer aos usuários suas responsabilidades antes de utilizar aplicativos corporativos. Como administrador do Cloud, você foi encarregado de implementar os termos de uso. Qual das funções abaixo não fornece as permissões adequadas para implementar os Termos de Uso?

Administrador globaç </p>
Administrador de segurança </p>
administrador de acesso condicional </p>
administrador de Helpdesk (correta)

Explicação
Como administrador do Helpdesk, não inclui as permissões necessárias para implementar os Termos de Uso do Azure AD.

Link: https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-users-assign-role-azure-portal


# Pergunta 23
Você tem um locatário do Azure Active Directory (Azure AD) que contém os seguintes objetos:
Um dispositivo chamado Device1
Usuários chamados User1, User2, User3, User4 e User5
Grupos chamados Group1, Group2, Group3, Group4 e Group5
Os grupos são configurados conforme mostrado na tabela a seguir.

</p>
<img src="https://user-images.githubusercontent.com/91704169/230692829-e01094f1-2a44-405e-807c-00ec254bb046.png" max-width="100px" width="1000px" align="centter" alt="Lab04">

A. Grupo1 e Grupo4 apenas </p>
B. Grupo1, Grupo2, Grupo3, Grupo4 e Grupo5 </p>
C. Grupo 1 e Grupo 2 apenas </p> (correto)
D. Grupo 1 apenas </p>
E. Grupo1, Grupo2, Grupo4 e Grupo5 apenas </p>


