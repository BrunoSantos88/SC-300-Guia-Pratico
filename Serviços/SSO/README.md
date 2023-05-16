# Introdução

Neste módulo, você aprenderá a implementar personalizações de token e implementar e definir configurações de consentimento. Você também aprenderá a integrar aplicativos locais usando o AD (Azure Active Directory), parte do proxy de aplicativo Entra, além de integrar aplicativos de SaaS (software como serviço) personalizados para SSO (logon único). Você aprenderá a implementar o provisionamento de usuário de aplicativo e monitorar e auditar acesso para os aplicativos empresariais integrados do Azure AD.

Objetivos de aprendizagem
Neste módulo, você vai:

Implementar personalizações de token
Implementar e definir configurações de consentimento
Integrar aplicativos locais usando o proxy de aplicativo do Azure AD
Integrar aplicativos de SaaS personalizados para SSO
Implementar provisionamento de usuário de aplicativo
Criar e gerenciar coleções de aplicativos
Monitorar e auditar acesso aos aplicativos empresariais integrados do Azure AD

# Integrar aplicativos SaaS personalizados para logon único

- Você pode usar o Azure AD como seu sistema de identidade para praticamente qualquer aplicativo. Muitos aplicativos já estão pré-configurados e podem ser configurados com esforço mínimo. Esses aplicativos pré-configurados são publicados na Galeria de Aplicativos do Azure AD.
Você poderá configurar manualmente a maioria dos aplicativos para logon único se eles ainda não estiverem na galeria. O Azure AD fornece várias opções de SSO. SSO baseado em SAML e SSO baseado em OIDC.
- Os aplicativos podem delegar a manutenção das próprias informações de nome de usuário e senha a um provedor de identidade centralizado, como o Azure AD. Delegar a autenticação e a autorização a ele permite cenários como políticas de Acesso Condicional, que exigem que um usuário esteja em um local específico ou exigem autenticação multifator. O uso de SSO (logon único) permite que um usuário entre uma vez e depois seja conectado automaticamente a todos os aplicativos Web que compartilham o mesmo diretório centralizado.

- A plataforma de identidade da Microsoft simplifica a autorização e a autenticação para os desenvolvedores de aplicativos, fornecendo a identidade como serviço, com suporte para protocolos padrão do setor, como OAuth 2.0 e OpenID Connect, bem como bibliotecas de software livre para diferentes plataformas para ajudar você a começar a codificação rapidamente. Ela permite que os desenvolvedores criem aplicativos que se conectam a todas as identidades da Microsoft e obtenham tokens para chamar o Microsoft Graph, outras APIs da Microsoft ou APIs que os desenvolvedores criaram.

# A lista a seguir é uma breve comparação dos vários protocolos usados pela plataforma de identidade da Microsoft.
- OAuth versus OpenID Connect: 
O OAuth é usado para autorização, e o OIDC (OpenID Connect) é usado para autenticação. O OpenID Connect é desenvolvido com base no OAuth 2.0, o que significa que a terminologia e o fluxo são semelhantes entre os dois. Você pode até mesmo autenticar um usuário usando o OpenID Connect e obter autorização para acessar um recurso protegido que o usuário possui usando o OAuth 2.0 em uma solicitação.

- OAuth versus SAML: 
O OAuth é usado para autorização e o SAML (Security Assertion Markup Language) é usado para autenticação.

- OpenID Connect versus SAML: 
O OpenID Connect e o SAML são usados para autenticar um usuário e para habilitar o logon único. A autenticação SAML é comumente usada com provedores de identidade, como os Serviços de Federação do Active Directory (AD FS), federados ao Azure AD e, portanto, é usada com frequência em aplicativos corporativos. O OpenID Connect é comumente usado para aplicativos puramente na nuvem, como aplicativos móveis, sites e APIs Web.
