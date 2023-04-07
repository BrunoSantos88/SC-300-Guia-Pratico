
#Guia pratico para certificação SC-300

# Retenção de dados do Azure Active Directory.

Quando o Azure AD começa a coletar dados?
Edição do Azure AD	Início da coleta
Azure AD Premium P1
Azure AD Premium P2	Quando você se inscreve para uma assinatura
Azure AD Gratuito	A primeira vez que você abrir o Azure Active Directory ou usar as APIs de relatórios
Se você já possui dados de atividades com sua licença gratuita, poderá vê-los imediatamente na atualização. Se você não tiver nenhum dado, levará até três dias para que os dados apareçam nos relatórios após a atualização para uma licença premium. Para sinais de segurança, o processo de coleta começa quando você aceita usar o Identity Protection Center .

Por quanto tempo o Azure AD armazena os dados?
Relatórios de atividades

Relatório	Azure AD Gratuito	Azure AD Premium P1	Azure AD Premium P2
Registros de auditoria	Sete dias	30 dias	30 dias
logins	Sete dias	30 dias	30 dias
Uso do Azure AD MFA	30 dias	30 dias	30 dias
Você pode reter os dados de atividade de auditoria e entrada por mais tempo do que o período de retenção padrão descrito na tabela anterior, roteando-os para uma conta de armazenamento do Azure usando o Azure Monitor. Para obter mais informações, consulte Arquivar logs do Azure AD em uma conta de armazenamento do Azure .

Sinais de segurança

Relatório	Azure AD Gratuito	Azure AD Premium P1	Azure AD Premium P2
Usuários arriscados	sem limite	sem limite	sem limite
Logins arriscados	7 dias	30 dias	90 dias


Link: https://learn.microsoft.com/en-us/azure/active-directory/reports-monitoring/reference-reports-data-retention#how-long-does-azure-ad-store-the-data

# Azure-fraud-notification

As notificações de fraude do Azure são limitadas à detecção de padrões de mineração de moeda cripto em recursos do Azure. As notificações de fraude do Azure não detectam todos os tipos de fraude e não têm garantia de detectar todos os tipos de mineração de moeda cripto. É fundamental que você use métodos adicionais de monitoramento para ajudar a detectar o uso anormal nas assinaturas do Azure do cliente, como orçamentos mensais de gastos do Azure. Para obter mais informações, consulte Gerenciando contas de clientes.

configuraçao 
</p>
<img src="https://user-images.githubusercontent.com/91704169/230609836-fef57a64-1c68-49bb-a829-9f58dd98f20e.png" max-width="100px" width="1000px" align="centter" alt="riscodeuser">

#Logs de auditoria no Azure Active Directory
Como posso acessá-lo?
O relatório de atividades de auditoria está disponível em todas as edições do Azure AD. Para acessar os logs de auditoria, você precisa ter uma das seguintes funções:


Leitor de Relatórios
Leitor de segurança
Administrador de Segurança
Leitor global
Administrador Global

configuraçao 
</p>
<img src="https://user-images.githubusercontent.com/91704169/230627260-94a9eb3c-d893-4d74-aaab-19c20f26e136.png" max-width="100px" width="1000px" align="centter" alt="riscodeuser">
