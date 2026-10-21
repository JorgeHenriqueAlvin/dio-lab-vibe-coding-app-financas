# 💡 ZenFin AI — Gestão Financeira Sem Fricção com Inteligência Artificial

> Projeto desenvolvido como parte do desafio **"Criando o Conceito do Seu App de Finanças Pessoais com Vibe Coding"** da [Digital Innovation One (DIO)](https://www.dio.me/).

---

## 📌 Sumário
- [1. Resumo do Conceito do App](#1-resumo-do-conceito-do-app)
  - [1.1. O Problema](#11-o-problema)
  - [1.2. A Solução: ZenFin AI](#12-a-solução-zenfin-ai)
  - [1.3. Público-Alvo & Diferenciais](#13-público-alvo--diferenciais)
- [2. O Prompt Final (PRD Completo para Lovable / Copilot)](#2-o-prompt-final-prd-completo-para-lovable--copilot)
- [3. Interações & Demonstrações Visuais](#3-interações--demonstrações-visuais)
- [4. Reflexão & Aprendizados com o Vibe Coding](#4-reflexão--aprendizados-com-o-vibe-coding)
- [5. Autor & Agradecimentos](#5-autor--agradecimentos)

---

## 1. Resumo do Conceito do App

### 1.1. O Problema
A maioria das pessoas falha em manter o controle financeiro não por falta de vontade, mas pelo **excesso de fricção**:
- Aplicativos tradicionais exigem o preenchimento de formulários lentos e burocráticos para cada café comprado.
- Planilhas tornam-se confusas e difíceis de preencher no dia a dia.
- Falta de aconselhamento proativo: os dados ficam parados em tabelas sem orientar se o usuário pode ou não gastar em determinado momento do mês.

### 1.2. A Solução: ZenFin AI
O **ZenFin AI** reinventa a gestão financeira aplicando o método de **Vibe Coding** e **IA Conversacional**:
- **Zero Formulários:** Registre receitas e despesas simplesmente enviando mensagens naturais:
  > *"Gastei R$ 48 no almoço do restaurante hoje com Pix"*  
  > *"Recebi meu adiantamento de R$ 1.500"*  
  > *"Uber pro trabalho R$ 23,90 no cartão"*
- **Classificação com NLP:** A IA interpreta o texto, extrai o valor, a data, o meio de pagamento e categoriza automaticamente (Alimentação, Transporte, Moradia, etc.).
- **Consultor Financeiro "Posso Comprar?":** Antes de fazer uma compra por impulso, pergunte ao ZenFin (*"Posso comprar um tênis de R$ 380 agora?"*). A IA analisa seu saldo líquido e previsões do mês e entrega uma recomendação sem julgamentos.

### 1.3. Público-Alvo & Diferenciais
- **Público-Alvo:** Jovens adultos, universitários, freelancers e profissionais que querem simplicidade e odeiam preencher tabelas.
- **Diferenciais:**
  - Interface *Mobile-First* com modo escuro e visual moderno (*Glassmorphism*).
  - Feedback empático e acolhedor em tom de conversa de WhatsApp.
  - Painel com indicadores em tempo real (Receitas, Despesas, Saldo e Taxa de Economia).

---

## 2. O Prompt Final (PRD Completo para Lovable / Copilot)

Abaixo está o **Product Requirements Document (PRD)** estruturado utilizado para gerar o conceito e a interface da aplicação:

```text
# PRODUCT REQUIREMENTS DOCUMENT (PRD) — ZENFIN AI MVP

## 🎯 OBJETIVO DO PRODUTO
Criar uma aplicação web responsiva (Mobile-First) de finanças pessoais com interface moderna e abordagem conversacional baseada em IA, eliminando formulários burocráticos e fornecendo insights instantâneos para o usuário.

## 👥 PERSONA E TOM DE VOZ
- Persona: Gabriel, 24 anos, quer poupar dinheiro de forma descomplicada para viagens.
- Tom de Voz do Agente: Empático, motivador, direto e descontraído.

## 🚀 FUNCIONALIDADES PRINCIPAIS (MVP)
1. Entrada de Gastos Conversacional (Vibe Input):
   - Campo de chat que aceita entradas livres como: "Gastei 35 reais na farmácia hoje", "Salário 3800 caiu".
   - Reconhece e categoriza automaticamente (Alimentação, Transporte, Moradia, etc.) e o método de pagamento.
2. Dashboard Dinâmico:
   - Cards de KPIs: Saldo Atual, Receitas, Despesas e Taxa de Economia (%).
   - Gráfico de Rosca/Donut de distribuição de despesas por categoria.
3. Simulador "Posso Comprar?" (AI Advisor):
   - O usuário informa o item e valor; a IA avalia o saldo disponível e indica se a compra é segura, se deve parcelar ou aguardar.
4. Histórico de Transações:
   - Lista detalhada com badges visuais de categoria e botão para excluir.

## 🎨 DESIGN SYSTEM & UI/UX
- Tema: Dark Mode premium (#090D16) com efeito Glassmorphism.
- Cores: Emerald (#10B981) para receitas e saldos positivos, Rose (#F43F5E) para despesas, Violet (#8B5CF6) para IA.
- Componentes: Tailwind CSS + Lucide Icons + Chart.js / Recharts.
