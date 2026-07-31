# Alura-Agente-ONE-AI-Tech-Builder

![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-Notebook-orange?style=for-the-badge&logo=googlecolab&logoColor=white)
![Gemini 1.5 Flash](https://img.shields.io/badge/Gemini-1.5%20Flash-purple?style=for-the-badge&logo=googlegemini&logoColor=white)
![PyPDF2 3.0](https://img.shields.io/badge/PyPDF2-3.0-blue?style=for-the-badge&logo=python&logoColor=white)
![Agente](https://img.shields.io/badge/Agente-Respondendo-brightgreen?style=for-the-badge)

Agente de IA desenvolvido como parte do desafio **ONE AI Tech Builder**. 
Ele foi criado para atuar como um assistente virtual especializado na análise e consulta de 
documentos técnicos da Santo Pegasus Soluciones, uma empresa de tecnologia do setor de saúde

## 📌 Sobre o Projeto

O agente utiliza o **Google Gemini (Flash)** para processamento de linguagem natural e tem como 
objetivo facilitar o acesso à informação técnica, acelerando o onboarding de novos colaboradores 
e auxiliando times de engenharia na consulta rápida de documentação.

## 🎯 Funcionalidades

- Extração e processamento de texto de múltiplos PDFs
- Respostas baseadas exclusivamente no conteúdo dos documentos fornecidos
- Interface interativa no Google Colab para perguntas e respostas
- Busca inteligente por trechos relevantes dos documentos
- Respostas rápidas e diretas com citação das fontes

## 🛠️ Tecnologias Utilizadas

- **Google Gemini (Flash)** - Modelo de linguagem para respostas rápidas
- **PyPDF2** - Extração de texto de arquivos PDF
- **Google Colab** - Ambiente de desenvolvimento e execução
- **Python** - Linguagem de programação

## 📂 Documentos Analisados

- Arquitetura de Microsserviços e Mapa de Domínios
- Guia Oficial de Engenharia Back-end
- Guia Oficial de Engenharia Front-end
- Manual de Onboarding
- Protocolo de Resposta a Incidentes (SRE)

## 🚀 Como Executar

1. Abra o notebook no Google Colab
2. Configure a chave da API Gemini no gerenciador de secrets (`Alura_Agente`)
3. Execute todas as células
4. Faça upload dos PDFs quando solicitado
5. Comece a fazer perguntas sobre os documentos!

## 📝 Exemplo de Perguntas

- "Qual é o princípio arquitetônico que proíbe o acesso direto ao banco de dados de outro microsserviço?"
- "Quais são os pilares da cultura Engineering Excellence da Santo Pegasus?"
- "Como funciona o fluxo de resposta a incidentes SEV-1?"
- "Quais tecnologias são utilizadas no ecossistema back-end?"

## ✅ Status do Agente

O agente está **funcionando perfeitamente**, processando consultas sobre a documentação técnica da Santo Pegasus Soluciones com **tempo médio de resposta inferior a 2 segundos**.

- ✅ Extração de PDFs: OK
- ✅ Processamento de texto: OK
- ✅ API Gemini: OK
- ✅ Respostas baseadas em contexto: OK

