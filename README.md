# -desafio-aws-.drawio
Documento prático da DIO com foco em consolidar o uso da AWS Step Functions
## 🧠 Descrição
Este projeto foi desenvolvido como parte do desafio da DIO, com o objetivo de consolidar conhecimentos sobre *AWS Step Functions, **Lambda* e *integração de serviços na AWS*.  
O foco é demonstrar a criação e documentação de workflows automatizados em nuvem.

## 🎯 Objetivos de Aprendizagem
- Aplicar conceitos aprendidos em ambiente prático.  
- Documentar processos técnicos de forma clara e estruturada.  
- Utilizar o GitHub para compartilhar documentação técnica.

## ⚙️ Tecnologias Utilizadas
- AWS Step Functions  
- AWS Lambda  
- Amazon S3  
- CloudWatch (para logs e monitoramento)

## 🔄 Fluxo de Trabalho (Workflow)
1. Um arquivo é enviado para um bucket no *Amazon S3*.  
2. Esse evento aciona uma *função Lambda* que processa o arquivo.  
3. A *Step Function* orquestra o fluxo de execução (por exemplo: validação → processamento → notificação).  
4. O resultado final é armazenado novamente no S3 ou enviado por notificação.
