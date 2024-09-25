------------------------------------------------------------------------------------------------------------------
#dio_lab AZ-900

Repo para testes e resumos dos LABs da DIO.</br >
Triha <...> Microsoft Azure (AZ-900).

------------------------------------------------------------------------------------------------------------------

Durante o curso foi abordado os seguintes temas:
#
1 - Definições de serviços em Cloud:</br >
1.1 - Tipos de cloud:</br >
1.1.1 - Cloud Privada (On-Premise).</br >
1.1.2 - Cloud Publica (Azure, AWS, OCI, GCP).</br >
1.1.3 - Cloud Hibrida (On-premise + Pública).</br >
1.1.4 - Multi-Cloud (Azure + AWS + OCI).</br >

1.2 - Modelos de responsabilide:</br > 
1.2.1 - Resposabilidade compartilhada.</br >
1.2.1.1 - link DOCs: https://learn.microsoft.com/pt-br/azure/security/fundamentals/shared-responsibility</br >

------------------------------------------------------------------------------------------------------------------

2 - Conceitos da Cloud Azure:</br >
 2.1 - Regiões.</br >
 
 2.2 - Zonas de disponibilidade.</br >
 
 2.3 - Pares de Regiões.</br >
  2.3.1 - link sites (DCs) do Microsoft Azure: https://datacenters.microsoft.com/globe/</br >
  
 2.4 - Regiões soberanas.</br >
 
 2.5 - Recursos e Grupos de Recursos.</br >
 
 2.6 - Assinaturas.</br >
 
 2.7 - Grupos de gerenciamento.</br >

------------------------------------------------------------------------------------------------------------------

3 - Computação e Rede do Azure:</br >
 3.1 - Tipos de Computação:</br >
  3.1.1 - Maquinas Virtuais (VMs).</br >
  3.1.2 - Area de trabalho virtual do Azure.</br >
  3.1.3 - Conjunto de dimenionamento de VMs.</br >
  
  3.2 - Conjunto de disponibilidade de VMs</br >
   3.2.1 - Dominio de falha (racks <..> vertical).</br >
   3.2.2 - Dominio de atualização (VMs <..> horizontal).</br >

------------------------------------------------------------------------------------------------------------------

4 - Redes virtuais do Azure (vNet):</br >
 4.1 - Comunicação entre recursos do Azure, com internet e rede local (On-premise).</br >
 
 4.2 - Gateway de VPN.</br >
 
 4.3 - Express-Route.</br >
 
 4.4 - DNS do Azure.</br >

------------------------------------------------------------------------------------------------------------------

5 - Armazenamento do Azure:</br >
 5.1 - Serviços de Armazenamento:</br >
  5.1.2 - Contas de Armazenamnto:</br >
   5.1.2.1 - Nome globalmente exclusivo.</br >
   5.1.2.2 - Acesso a internet em todo mundo.</br >
   5.1.2.3 - Opções de redundancia.</br >
    5.1.2.3.1 - LRS (redundancia local) > 11 noves.</br >
    5.1.2.3.2 - ZRS (redundancia de zona) > 12 noves.</br >
    5.1.2.3.3 - GRS (redundancia geografica) > 16 noves</br >
    5.1.2.3.4 GZRS (redundancia de zona geografica) > 16 noves.</br > 
    
 5.2 - Blob do Azure:</br >
  5.2.1 - Armazenamento de quantidades massiva de dados não estruturados (texto ou dados binários).</br > 
  
 5.3 - Disco do Azure:</br >
  5.3.1 - Maquinas virtuais, apps, etc.</br >		
  
 5.4 - Fila do Azure:</br >
  5.4.1 - Armazenamento de mensagens.</br >
  
 5.5 - Arquivos do Azure:</br >
  5.5.1 - Compartilhamento de arquivos de rede.</br >
  
 5.6 - Tabelas do Azure:</br >
  5.6.1 - fornece opção de chave/atributo para armazenamento de dados estruturados não relacionais.</br >

------------------------------------------------------------------------------------------------------------------

6 - Acesso, Identidade e Segurança:</br> 
 6.1 - MS Entra-ID:</br>
  6.1.1 - Serviço de gerenciamento de identidade.</br>
  
 6.2 - Domain Server:</br>
  6.2.1 - Sincronização das permissões do ambiente local para nuvem.</br>
  
 6.3 -Autenticação:</br>
  6.3.1 - Identifica pessoa ou serviço;</br>
  
  6.3.2 - Solicita credenciais;</br>
  6.3.3 - Cria principios de identidade e controle de acesso seguro.</br>
  
 6.4 - Autorização:</br>
  6.4.1 - Nível de acesso;</br>
  6.4.2 - Quais dados podem acessar.</br>
  
 6.5 - MFA (multifactor autentication):</br>
  6.5.1 - Algo que vc sabe;</br>
  6.5.2 - Algo que vc possui;</br>
  6.5.3 - Algo que vc é.</br>
  
 6.6 - Acesso Condicional:</br>
  6.6.1 - Associação de user ou grupo;</br>
  6.6.2 - Local do IP;</br>
  6.6.3 - Dispositivo;</br>
  6.6.4 - Aplicativo;</br>
  6.6.5 - Detecção de risco.</br>
  
 6.7 - Proteção Completa:</br>
  6.7.1 - Segurança Física;</br>
  6.7.2 - Identidade de acesso;</br>
  6.7.3 - Perimetro;</br>
  6.7.4 - Rede;</br>
  6.7.5 - Computação;</br>
  6.7.6 - Aplicativo;</br>
  6.7.7 - Dados.</br>
  
 6.8 - MS Defender for Cloud:</br>
  6.8.1 - Monitoramento e proteção contra ameaças;</br>
  6.8.2 - Multicloud.</br>

------------------------------------------------------------------------------------------------------------------

7 - Gerenciamento de custos Azure:</br> 
7.1 - Fatores que afetam os custos:</br>
7.1.1 - Tipo de recurso;</br>
7.1.2 - Consumo;</br>
7.1.3 - Manutenção;</br>
7.1.4 - Área geográfica;</br>
7.1.5 - Tráfego de rede;</br>
7.1.6 - Assinatura;</br>
  
7.2 - Marketplace:</br>
7.2.1 - Apliativos de terceiros;</br>
  
7.2.3 - Suporte com fornecedor do aplicativo.</br>
7.3 - Calculdora de preços:</br>

7.3.1 - Estimativa de preço;</br>
7.3.2 TCO:</br>
  
7.4 - Estima os valores pra migrar para Nuvem;</br>
7.4.1 - Comparação de custos;</br>
  
7.5 - Relatorio de cobrança:</br>
7.5.1 - Configure alertas.</br>

------------------------------------------------------------------------------------------------------------------

OBS: este doc será atualizado constantemente durante o curso!</br >

#
