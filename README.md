# Desafio Criativo DIO - Prompt Engineering: App "Catar Feijão com IA" 🫘📱

Este repositório contém a entrega do **Desafio Criativo** proposto na plataforma **DIO (Digital Innovation One)**, com o objetivo de demonstrar a construção estruturada de um prompt de Inteligência Artificial para a especificação de um aplicativo inovador de detecção e triagem de grãos de feijão em tempo real.

---

## 📌 Visão Geral do Projeto

O objetivo do aplicativo é resolver um problema do cotidiano doméstico: **a triagem manual de feijão antes do cozimento**. 

Através da câmera do smartphone, o usuário aponta para os grãos espalhados em uma superfície (mesa ou tábua) e o aplicativo utiliza visão computacional/IA para identificar e destacar visualmente (via *AR Overlay*) os grãos defeituosos, brocados, sujidades ou pedras que devem ser descartados.

---

## 🧩 Construção do Prompt Passo a Passo

A metodologia aplicada divide o desenvolvimento do prompt em três partes essenciais: **Intenção**, **Contexto/Restrições** e a **Conexão Final**.

### 🧱 Passo 1: Definição da Intenção
* **O que gerar:** Arquitetura e requisitos funcionais de um aplicativo mobile.
* **Para quem:** Cozinheiros domésticos, entusiastas da culinária e pessoas que preparam refeições no dia a dia.
* **Resultado esperado:** Orientar desenvolvedores no design de uma solução de visão computacional que identifique e sinalize grãos de feijão impróprios para consumo antes do cozimento.

### 🧱 Passo 2: Contexto e Restrições
* **Contexto:** O usuário espalhará os grãos em uma superfície plana e utilizará a câmera do smartphone; o app deve processar a imagem e sobrepor marcadores visuais (overlays) nos grãos a serem removidos.
* **Formato:** Guia técnico de especificação para desenvolvedores.
* **A evitar:** Termos acadêmicos excessivamente complexos de processamento de imagem e dependência de hardwares externos além do próprio celular.

---

## 🚀 Prompt Final

```text
Quero que a IA gere a arquitetura e os requisitos funcionais de um aplicativo mobile para cozinheiros domésticos e pessoas que preparam refeições no dia a dia, com o objetivo de identificar e sinalizar grãos de feijão estragados ou impróprios para consumo antes do cozimento usando a câmera do celular. Considere o seguinte contexto: o usuário espalhará os grãos de feijão em uma superfície plana e apontará a câmera do celular; o aplicativo deve processar a imagem e destacar visualmente na tela (com sobreposição/overlay) quais grãos devem ser removidos. O conteúdo deve ter o formato de um guia técnico de especificação para desenvolvedores. Evite termos excessivamente acadêmicos de processamento de imagem e evite soluções de hardware complexas fora do próprio smartphone.
