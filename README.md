# phishing-analysis
Análise de email de phishing como parte de um desafio SOC

## Descrição
Este repositório contém a análise de um email de phishing, incluindo a investigação de anexos e cabeçalhos de email, realizada como parte de um desafio SOC.

## Cenário
Um utilizador recebeu um email de phishing e encaminhou-o para o SOC. O objetivo era investigar o email e o anexo, recolhendo artefatos úteis, como o IP de origem, URLs suspeitos e detalhes do cabeçalho do email.

## Objetivos
- Identificar o destinatário primário.
- Extrair o assunto e a data do envio.
- Determinar o IP de origem e realizar reverse DNS.
- Analisar o anexo e encontrar URLs de phishing.
- Identificar o serviço de hospedagem usado.

## Ferramentas Utilizadas
- Text Editor (para visualizar o cabeçalho do email)
- Mozilla Thunderbird (para análise do email)
- WHOis (para consulta de IP)
- URL2PNG (para análise de página web)
  
## Resultados
1. **Destinatário Primário**: `kinnar1975@yahoo.co.uk`
2. **Assunto**: `Undeliverable: Website contact form submission`
3. **Data do Envio**: `18 March 2021 04:14`
4. **IP de Origem**: `103.9.171.10`
5. **Reverse DNS**: `c5s2-1e-syd.hosting-services.net.au`
6. **Nome do Anexo**: `Website contact form submission`
7. **URL dentro do anexo**: `https://35000usdperwwekpodf.blogspot.sg?p=9swg`
8. **Serviço Hospedado**: `Blogspot`
9. **Título da Página Web**: `Blog has been removed`

## Como Executar a Análise
1. **Análise do Cabeçalho do Email**: Utilize um editor de texto para extrair informações sobre o remetente, destinatário e IP de origem.
2. **Análise do Anexo**: Verificar o anexo para identificar URLs ou outros dados suspeitos.
3. **Consulta WHOis**: Realizar consultas no WHOis para identificar informações sobre o IP.
4. **Visualização de URL**: Usar o URL2PNG para verificar a página web e confirmar o phishing.

## Conclusão
Este exercício foi útil para entender a análise de emails de phishing, incluindo a investigação de cabeçalhos, uso de ferramentas de consulta de IP e análise de URLs em serviços de hospedagem como Blogspot.
