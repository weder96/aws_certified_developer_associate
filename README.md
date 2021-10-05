# aws_certified_developer_associate

## Introdução
O exame AWS Certified Developer – Associate (DVA-C01) destina-se a pessoas que desempenham a
função de desenvolvedor. O exame valida a capacidade de um candidato de:<br/>
Demonstrar um entendimento dos principais produtos e usos da AWS, bem como as práticas
recomendadas básicas de arquitetura da AWS<br/>
Demonstrar proficiência em desenvolvimento, implantação e depuração de aplicações baseadas
na nuvem usando a AWS<br/>

## Descrição do candidato
O candidato deve ter um ano ou mais de experiência prática no desenvolvimento e na manutenção de uma aplicação baseada na AWS.<br/>

# Conhecimento geral de TI recomendado
O candidato deve ter:
    1. Conhecimento aprofundado em pelo menos uma linguagem de programação de alto nível
    2. Compreensão do gerenciamento do ciclo de vida da aplicação
    3. Capacidade de escrever código para aplicações sem servidor
    4. Compreensão do uso de contêineres no processo de desenvolvimento
   
# Conhecimento recomendado da AWS
O candidato deve ser capaz de:<br/>

1. Usar as APIs de produtos da AWS, a CLI e os kits de desenvolvimento de software (SDKs) para escrever aplicações
2. Identificar os principais recursos dos produtos da AWS
3. Compreender o modelo de responsabilidade compartilhada da AWS
4. Usar um pipeline de integração e entrega contínuas (CI/CD) para implantar aplicações na AWS
5. Usar e interagir com os produtos da AWS
6. Aplicar o entendimento básico de aplicações nativas da nuvem para escrever código
7. Escrever código usando as práticas recomendadas de segurança da AWS (por exemplo, usar funções do IAM em vez de chaves de acesso e chaves secretas no código)
8. Criar, manter e depurar módulos de código na AWS

## O que é considerado fora do escopo do candidato?
Veja a seguir uma lista (não completa) de tarefas de trabalho relacionadas as quais não se espera que o
candidato seja capaz de executar. Estes itens são considerados fora do escopo do exame <br/>
 1. Projetar arquiteturas (por exemplo, sistema distribuído, microsserviços)
 2. Projetar e implementar pipelines de CI/CD
 3. Administrar usuários e grupos do IAM
 4. Administrar o Amazon Elastic Container Service (Amazon ECS)
 5. Projetar a infraestrutura de redes da AWS (por exemplo, Amazon VPC, AWS Direct Connect)
 6. Compreender a compatibilidade e o licenciamento

# Guia do Exame
## AWS Certified Developer – Associate (DVA-C01) Guia do exame 
https://d1.awsstatic.com/pt_BR/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf <br/>
Acessado em: 05/10/2021 as 12:10


## Descrição do conteúdo
Este guia de exame inclui os pesos, os domínios do teste e os objetivos do exame. <br/>
Não é uma lista abrangente do conteúdo do exame. <br/>
No entanto, disponibilizamos um contexto adicional para cada um dos objetivos visando ajudar a orientar sua preparação para o exame. <br/>
A tabela a seguir lista os principais domínios de conteúdo e seus pesos. <br/>
A tabela precede a descrição completa do conteúdo do exame, que inclui o contexto adicional. A porcentagem de cada domínio representa apenas o conteúdo pontuado.<br/>


| Domínio                                            |       % do exame    | 
| -------------------------------------------------- | ------------------- |
| Domínio 1: Implantação                             |         22%         |
| Domínio 2: Segurança                               |         26%         |
| Domínio 3: Desenvolvimento com os produtos da AWS  |         30%         |
| Domínio 4: Refatoração                             |         10%         |
| Domínio 5: Monitoramento e resolução de problemas  |         12%         |
| TOTAL                                              |        100%         |


## Domínio 1: Implantação
1.1 Implantar código escrito na AWS usando pipelines, processos e padrões de CI/CD existentes <br/>
    1.1.1 Confirmar o código em um repositório e invocar ações de construção, teste e/ou implantação<br/>
    1.1.2 Usar rótulos e ramificações para o gerenciamento de versões e releases <br/>
    1.1.3 Usar o AWS CodePipeline para orquestrar fluxos de trabalho em diferentes ambientes<br/>
    1.1.4 Aplicar os serviços AWS CodeCommit, AWS CodeBuild, AWS CodePipeline, AWS CodeStar e AWS CodeDeploy para fins de CI/CD <br/>
    1.1.5 Executar um plano de reversão com base na política de implantação de aplicações<br/>

1.2 Implantar aplicações usando o AWS Elastic Beanstalk. <br/>
    1.2.1 Utilizar ambientes compatíveis existentes para definir uma nova pilha de aplicações
    1.2.2 Empacotar a aplicação
    1.2.3 Apresentar uma nova versão da aplicação no ambiente do Elastic Beanstalk
    1.2.4 Utilizar uma política de implantação para uma versão da aplicação (ou seja, implantação “todas de uma vez”, contínua, contínua com lotes, imutável)
    1.2.5 Validar a integridade da aplicação usando o painel do Elastic Beanstalk
    1.2.6 Usar o Amazon CloudWatch Logs para instrumentar o registro em log de aplicações

1.3 Preparar o pacote de implantação de aplicações a ser implantado na AWS. <br/>
    1.3.1 Gerenciar as dependências do módulo de código (como variáveis de ambiente, arquivos de configuração e arquivos de imagem estática) dentro do pacote <br/>
    1.3.2 Descrever a estrutura de diretórios de pacote/contêiner e organizar os arquivos   adequadamente <br/>
    1.3.3 Traduzir os requisitos de recursos de aplicação para os parâmetros de infraestrutura da AWS (por exemplo, memória, núcleos) <br/>

1.4 Implantar aplicações sem servidor <br/>
    1.4.1  Com base em um caso de uso, implementar e iniciar um modelo do AWS Serverless Application Model (AWS SAM) <br/>
    1.4.2 Gerenciar ambientes em produtos individuais da AWS (por exemplo, diferenciar entre desenvolvimento, teste e produção no Amazon API Gateway)<br/>

## Domínio 2: Segurança
2.1 Fazer chamadas autenticadas para produtos da AWS. <br/>
2.2 Implementar criptografia usando os produtos da AWS.  <br/>
2.3 Implementar a autenticação e a autorização de aplicações.<br/>


## Domínio 3: Desenvolvimento com os produtos da AWS
3.1 Escrever código para aplicações sem servidor. <br/>
3.2 Traduzir requisitos funcionais para o design de aplicações. <br/>
3.3 Implementar o design da aplicação em seu próprio código. <br/>
3.4 Escrever código capaz de interagir com os produtos da AWS usando APIs, SDKs e a AWS CLI <br/>


## Domínio 4: Refatoração
4.1 Otimizar a aplicação para usar melhor os recursos e produtos da AWS <br/>
4.2 Migrar o código de aplicação existente para executar na AWS. <br/>


## Domínio 5: Monitoramento e resolução de problemas
5.1 Escrever código passível de monitoramento. <br/>
5.2 Executar análise de causa raiz em falhas encontradas em testes ou na produção. <br/>



# Apêndice
Quais são as principais ferramentas, tecnologias e conceitos que podem ser abordados no exame?
Veja a seguir uma lista (não completa) de ferramentas e tecnologias que podem aparecer no exame.
Essa lista está sujeita a alterações e é fornecida para ajudar a entender o escopo geral de serviços,
recursos ou tecnologias no exame. As ferramentas e tecnologias gerais dessa lista não aparecem em
nenhuma ordem específica. Os produtos da AWS são agrupados de acordo com suas funções principais.
Embora algumas dessas tecnologias provavelmente sejam abordadas mais do que outras no exame, a
ordem e colocação delas na lista não são indicativos de importância nem de peso relativo:

-  Análise
-  Integração de aplicações
-  Contêineres
-  Gerenciamento de custos e capacidade
-  Movimentação de dados
-  Ferramentas do desenvolvedor
-  Instâncias (máquinas virtuais)
-  Gerenciamento e governança
-  Redes e entrega de conteúdo
-  Segurança
-  Ambientes sem servidor

# Recursos e produtos da AWS Análise:
-  Amazon Elasticsearch Service (Amazon ES)
-  Amazon Kinesis 

# Integração de aplicações:
-  Amazon EventBridge (Amazon CloudWatch Events)
-  Amazon Simple Notification Service (Amazon SNS)
-  Amazon Simple Queue Service (Amazon SQS)
-  AWS Step Functions

# Computação:
-  Amazon EC2
-  AWS Elastic Beanstalk
-  AWS Lambda

# Contêineres:
-  Amazon Elastic Container Registry (Amazon ECR)
-  Amazon Elastic Container Service (Amazon ECS)
-  Amazon Elastic Kubernetes Services (Amazon EKS)

# Banco de dados:
-  Amazon DynamoDB
-  Amazon ElastiCache
-  Amazon RDS

# Ferramentas do desenvolvedor:
-  AWS CodeArtifact
-  AWS CodeBuild
-  AWS CodeCommit
-  AWS CodeDeploy
-  Amazon CodeGuru
-  AWS CodePipeline
-  AWS CodeStar
-  AWS Fault Injection Simulator
-  AWS X-Ray

# Gerenciamento e governança:
-  AWS CloudFormation
-  Amazon CloudWatch

# Redes e entrega de conteúdo:
-  Amazon API Gateway
-  Amazon CloudFront
-  Elastic Load Balancing

# Segurança, identidade e compatibilidade:
-  Amazon Cognito
-  AWS Identity and Access Management (IAM)
-  AWS Key Management Service (AWS KMS)

# Armazenamento:
-  Amazon S3

# Recursos e produtos da AWS fora do escopo
Veja a seguir uma lista (não completa) de recursos e produtos da AWS que não são abordados no
exame. Estes recursos e produtos não representam todos os serviços da AWS que foram excluídos do
conteúdo do exame. Os recursos ou produtos que não têm nenhuma relação com as funções de trabalho
às quais o exame se destina não estão nessa lista porque são considerados irrelevantes.
Os recursos e produtos da AWS fora do escopo são:
-  AWS Application Discovery Service
-  Amazon AppStream 2.0
-  Amazon Chime
-  Amazon Connect
-  AWS Database Migration Service (AWS DMS)
-  AWS Device Farm
-  Amazon Elastic Transcoder
-  Amazon GameLift
-  Amazon Lex
-  Amazon Machine Learning (Amazon ML)
-  AWS Managed Services
-  Amazon Mobile Analytics
-  Amazon Polly
-  Amazon QuickSight
-  Amazon Rekognition
-  AWS Server Migration Service (AWS SMS)
-  AWS Service Catalog
-  AWS Shield Advanced
-  AWS Shield Standard
-  AWS Snow Family
-  AWS Storage Gateway
-  AWS WAF
-  Amazon WorkMail
-  Amazon WorkSpaces