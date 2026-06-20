# 🎓 EduAssist CENG

Sistema de assistente virtual escolar inteligente desenvolvido para o Centro Educacional Nova Geração (CENG), integrado ao Telegram, capaz de consultar boletins, médias, situação final e normas institucionais utilizando automação e inteligência artificial.

---

## 🚀 Visão Geral

O **EduAssist CENG** é um sistema de automação educacional que permite aos alunos consultarem suas informações acadêmicas em tempo real por meio de um chatbot no Telegram.

O sistema integra banco de dados, IA e automação de fluxos para fornecer respostas estruturadas e consistentes.

---

## ⚙️ Funcionalidades

- 📊 Consulta de boletim escolar por ID do aluno  
- 📈 Exibição de notas por disciplina e bimestre  
- 🧮 Média geral automática (via banco de dados)  
- 🎯 Situação final do aluno (Aprovado / Recuperação)  
- 📚 Consulta às normas institucionais do CENG  
- 🤖 Respostas automatizadas via IA  
- 💬 Integração com Telegram Bot  

---

## 🧠 Arquitetura do Sistema

```text
Telegram Bot
     ↓
n8n (orquestração de fluxos)
     ↓
Cohere AI (interpretação e formatação de resposta)
     ↓
MySQL (dados acadêmicos)
     ↓
Railway (infraestrutura / deploy)
