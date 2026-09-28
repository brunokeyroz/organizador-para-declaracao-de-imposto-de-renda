# 🦁 A Hora do Leão — Agregador de Dados para Imposto de Renda no Excel

Projeto desenvolvido para o desafio prático de projeto do bootcamp **Reclame AQUI - Dados e IA na Prática**, oferecido pela **Digital Innovation One (DIO)**.

---

## 📝 Visão Geral do Projeto

**A Hora do Leão** é uma ferramenta desenvolvida em **Microsoft Excel** com o objetivo de centralizar, organizar e validar as informações financeiras e cadastrais necessárias para a Declaração do Imposto de Renda Pessoa Física (IRPF).

A planilha foi estruturada para evitar inconsistências nos dados, facilitar o acompanhamento de bens/saldos bancários e consolidar o histórico de receitas e anexos de comprovação.

---

## 🛠️ Arquitetura e Estrutura da Planilha

A solução está dividida nas seguintes abas especializadas:

1. **`TITULAR` (Cadastro Geral):**
   * Coleta e organização de dados pessoais do contribuinte, endereço, contatos e status de dependentes/cônjuge.
2. **`INFORMES` (Controle Bancário e Saldos):**
   * Registro de saldos em instituições financeiras com somatório automático de patrimônio em bancos (`=SOMA()`).
   * Vínculo e rastreabilidade de arquivos de informes de rendimentos anexos (ex: PDFs de informe).
3. **`NOTAS` (Entradas e Receitas):**
   * Tabela cronológica de entradas financeiras para controle e categorização de receitas mês a mês.
4. **`TABELAS` (Base de Dados e Suporte):**
   * Listagem padronizada das principais instituições bancárias do Brasil para validação de dados e criação de listas suspensas.
5. **`CORES` (Design System):**
   * Guia de estilos com códigos Hexadecimais para padronização da identidade visual e interface da planilha.

---

## 🌟 Recursos do Excel Utilizados

* **Fórmulas de Agregação:** Somatórios automáticos de saldos e rendimentos.
* **Validação de Dados:** Menus suspensos vinculados à tabela de bancos para evitar erros de digitação.
* **Gestão de Anexos:** Organização de nomes de arquivos comprobatórios para rápida localização.
* **Modelagem e UX:** Divisão clara por contextos e padronização visual por paleta de cores.

---

## 🚀 Como Utilizar

1. Faça o download do arquivo `A HORA DO LEÃO .xlsx` neste repositório.
2. Abra o arquivo no **Microsoft Excel**.
3. Preencha seus dados cadastrais na aba `TITULAR`.
4. Atualize os saldos das suas contas bancárias na aba `INFORMES`.
5. Registre suas receitas e proventos na aba `NOTAS`.

---

## 👤 Autor

Desenvolvido por **Bruno Queiroz de Souza**  
🔗 [LinkedIn](https://www.linkedin.com/in/obrunoqueiroz)


Projeto feito com fins educacionais. Não substitui orientação contábil ou as instruções oficiais da Receita Federal para a declaração do Imposto de Renda.

