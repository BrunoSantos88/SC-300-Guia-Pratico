
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
