# O que é a Autenticação Multifator do Azure AD?

- Proteger seus ativos de nuvem é uma das principais metas dos grupos de segurança. Uma das principais maneiras pelas quais os usuários não autorizados obtêm acesso a sistemas é obter uma combinação válida de nome de usuário/senha. O Azure pode ajudar a atenuar isso com vários recursos do Azure Active Directory, incluindo:

- Regras de complexidade de senha: forçam os usuários a gerar senhas difíceis de adivinhar.

- Regras de expiração de senha: você pode forçar os usuários a alterar suas senhas periodicamente (e evitar usar senhas usadas anteriormente).

- SSPR (redefinição de senha self-service): permite que os usuários realizem autoatendimento e redefinam sua senha caso tenham a tenham esquecido sem envolver um departamento de TI.

- Azure AD Identity Protection: Para ajudar a proteger as identidades da organização, você pode configurar políticas de risco que respondem automaticamente a comportamentos de risco. Essas políticas podem bloquear os comportamentos ou iniciar a correção automaticamente, incluindo a exigência de alterações de senha.

- Proteção de senha do Azure AD: você pode bloquear senhas comumente usadas e comprometidas por meio de uma lista de senhas proibidas globalmente.

- Bloqueio inteligente do Azure AD: O bloqueio inteligente ajuda a bloquear hackers mal-intencionados que estão tentando adivinhar as senhas dos seus usuários ou usam métodos de força bruta para entrar. Ele reconhece entradas provenientes de usuários válidos e as trata diferente daquelas de hackers mal-intencionados e outras fontes desconhecidas.

- Proxy de Aplicativo do Azure AD: Você pode provisionar o acesso remoto com segurança avançada para aplicativos Web locais.

- SSO (logon único): você pode habilitar o acesso SSO aos seus aplicativos. Isso inclui milhares de aplicativos SaaS previamente integrados.

- Azure AD Connect: Crie e gerencie uma identidade única para cada usuário em sua empresa híbrida, mantendo usuários, grupos e dispositivos em sincronia.

# O que é o MFA do Azure AD?
O MFA (Autenticação Multifator) do Azure AD fornece maior segurança para as suas identidades exigindo dois ou mais elementos para autenticação completa.

Esses elementos se enquadram em três categorias:

- Algo que você sabe, que pode ser uma senha ou a resposta a uma pergunta de segurança.
- Algo que você tem, que pode ser um aplicativo móvel que recebe uma notificação ou um dispositivo de geração de token.
- Algo que você é – que normalmente é uma propriedade biométrica, como uma impressão digital ou verificação de detecção facial usada em muitos dispositivos móveis.


# Como obter a Autenticação Multifator?
A Autenticação Multifator é fornecida como parte das seguintes ofertas:

- Azure Active Directory Premium ou Microsoft 365 Business: essas duas ofertas dão suporte à Autenticação Multifator do Azure AD usando padrões de segurança para exigir a autenticação multifator.

- Licenças do Azure AD Gratuito ou do Microsoft 365 autônomo: ambos usam padrões de segurança que exigem a autenticação multifator para seus usuários e administradores.

- Administradores Globais do Azure Active Directory: um subconjunto das funcionalidades de Autenticação Multifator do Azure AD está disponível como um meio para proteger as contas de administrador global.

# Planeje a implantação de sua autenticação multifator

Antes de iniciar uma implantação da Autenticação Multifator do Azure AD, há vários itens que você deve decidir.

Primeiro, considere implementar o MFA em fases. Comece com um pequeno grupo de usuários piloto para avaliar a complexidade do seu ambiente e identificar problemas de configuração ou aplicativos ou dispositivos sem suporte. Em seguida, amplie esse grupo ao longo do tempo e avalie os resultados com cada passagem até que toda a empresa seja inscrita.

Em seguida, crie um plano de comunicação completo. A Autenticação Multifator do Azure AD tem vários requisitos de interação do usuário, incluindo um processo de registro. Mantenha seus usuários informados em todas as etapas e deixe que eles saibam o que precisarão fazer, datas importantes e como obter respostas a perguntas caso tenham dúvidas. A Microsoft fornece modelos de comunicação, incluindo pôsteres e modelos de email para ajudar a rascunhar suas comunicações.

# Políticas de MFA do Azure AD
A Autenticação Multifator do Azure AD é imposta com políticas de Acesso Condicional. As políticas de Acesso Condicional são instruções IF-THEN. SE um usuário desejar acessar um recurso, ENTÃO ele deverá concluir uma ação. Por exemplo, um gerente de folha de pagamento deseja acessar o aplicativo de folha de pagamento e deve executar a autenticação multifator para acessá-lo. Outras solicitações de acesso comuns que podem exigir o MFA incluem:

- SE um aplicativo de nuvem específico for acessado
- SE um usuário estiver acessando uma rede específica
- SE um usuário estiver acessando um aplicativo cliente específico
- SE um usuário estiver registrando um novo dispositivo

# Decidir métodos de autenticação com suporte

- Quando você ativa o MFA do Azure AD, pode escolher os métodos de autenticação que você deseja disponibilizar. Você sempre deve dar suporte a mais de um método para que os usuários tenham uma opção de backup caso seu método principal não esteja disponível. Você pode escolher entre os métodos a seguir:

# Código de verificação do aplicativo móvel	

- Um aplicativo de autenticação móvel, como o aplicativo Microsoft Authenticator, pode ser usado para recuperar um código de verificação OATH que é inserido na interface de entrada. Esse código é alterado a cada 30 segundos e o aplicativo funcionará mesmo se a conectividade for limitada. Observe que essa abordagem não funciona na China em dispositivos Android.

#  Notificação de aplicativo móvel	
- O Azure pode enviar uma notificação por push para um aplicativo de autenticação móvel, como o Microsoft Authenticator. O usuário pode selecionar a notificação por push e verificar a entrada.
- 
 # Ligue para um telefone	
 
- O Azure pode ligar para um número de telefone fornecido. O usuário aprova a autenticação usando o teclado. Esse é um método de backup preferencial.
Chave de segurança FIDO2	As chaves de segurança FIDO2 são um método de autenticação sem senha inviolável, baseado em padrões, que normalmente são dispositivos USB, mas também podem usar Bluetooth ou NFC.

# Windows Hello for Business	

- O Windows Hello para Empresas substitui senhas com autenticação forte de dois fatores nos dispositivos. Essa autenticação consiste em um tipo de credencial de usuário que está associada a um dispositivo e usa um PIN ou biometria.
Tokens OATH	Os tokens OATH podem ser aplicativos de software, como o aplicativo Microsoft Authenticator e outros aplicativos autenticadores ou tokens baseados em hardware que os clientes podem comprar de diferentes fornecedores.

# Selecionar um método de autenticação

Por fim, você deve decidir como os usuários registrarão seus métodos selecionados. A abordagem mais fácil é usar o Azure Active Directory Identity Protection. Se a sua organização tiver uma licença para o Identity Protection, você poderá configurá-lo para solicitar que os usuários se registrem no MFA na próxima vez em que entrarem.

Você também pode solicitar que os usuários se registrem na MFA quando tentarem usar um aplicativo ou serviço que requeira a autenticação multifator. Por fim, você pode impor um registro usando a política de Acesso Condicional aplicada a um grupo do Azure que contém todos os usuários em sua organização. Essa abordagem requer algum trabalho manual para examinar periodicamente o grupo para remover usuários registrados. Há alguns scripts úteis na documentação para automatizar alguns desses processos.

Exercicio MFA: </p>
Link: https://learn.microsoft.com/pt-br/training/modules/secure-aad-users-with-mfa/4-exercise-mfa
