# 📦 LogiTrack – Sistema de Rastreio de Encomendas  
Aplicação web responsiva desenvolvida como projeto acadêmico.
---

## 👤 Identificação / Autor  
**Nome:** Alexia de Moraes Santos  
**Disciplina:** Framework e CSS 
**Instituição:** [UTFPR-GP]  

---

## 📖 Descrição do Projeto  
O **LogiTrack** é uma aplicação web responsiva inspirada no site da transportadora *Expresso São Miguel*.  
O objetivo do sistema é permitir que o usuário **rastreie suas encomendas**, podendo cadastrar novos pacotes, validar informações em formulários e consultar o status das entregas em tempo real a partir de uma **API fake (JSON Server)**.  

**Escopo mínimo da aplicação:**  
- 3 páginas principais: Home, Cadastro de Encomendas e Listagem de Encomendas.  
- Formulário com validações (HTML5 + JavaScript).  
- Persistência de dados no **Web Storage** e em uma **API fake**.  
- Listagem dinâmica de encomendas em tabela/cards.  
- Layout responsivo desenvolvido com Framework CSS.  

---

## 🎨 Prototipação no Figma  
🔗 https://www.figma.com/design/zPCyzrUIQOhU2Pi3rbNGm3/LogiTrack?m=auto&t=t1QnIFZeK2teinzg-1

---

## 🎨 Design System  
🔗 https://www.figma.com/design/qoDKFlNbdfDwaeqmrJdaXI/Design-System?m=auto&t=dZPuOGFUTzQUjtOV-6 

---

## 🎨 Framework CSS  
O framework utilizado para o desenvolvimento do layout responsivo é o **Tailwind CSS** (com suporte DaisyUI).  

---

## 📦 Dependências  
Bibliotecas e ferramentas utilizadas no projeto:  
- **JSON Server** – API fake para persistência e consulta de dados.  
- **jQuery** – Manipulação do DOM e interatividade.  
- **jQuery Mask Plugin** – Máscara de campos em formulários.  
- **ESLint + Prettier** – Padronização e qualidade do código.  

---

## 🌍 Link para o site em produção  
🔗 [Acesse aqui o ViaTrack no GitHub Pages](#)  

---

## ✅ Checklist de Funcionalidades  

### RA1 – Layout Responsivo e Framework CSS  
- [ ] Protótipo das telas no Figma (mobile + desktop).  
- [ ] Layout responsivo implementado com Tailwind CSS.  
- [ ] Uso de componentes prontos do framework (cards, botões, modais).  

### RA2 – Formulários e Validações  
- [ ] Validação HTML nativa (campos obrigatórios, limites).  
- [ ] Validações customizadas com REGEX (e-mail, telefone).  
- [ ] Persistência de dados no Web Storage.  

### RA3 – Ferramentas de Desenvolvimento  
- [ ] Ambiente Node.js + NPM configurado.  
- [ ] Versionamento Git/GitHub.  
- [ ] README.md padronizado.  

### RA4 – Interatividade com JavaScript  
- [ ] Manipulação do DOM com jQuery.  
- [ ] Integração de plugin jQuery (ex.: Mask Plugin).  

### RA5 – Integração com APIs  
- [ ] Persistência de dados no JSON Server.  
- [ ] Exibição de dados a partir da API fake.  
- [ ] Consumo de API pública (ex.: ViaCEP).  

---

## 🚀 Instruções de Execução  

### Pré-requisitos  
- Node.js instalado  
- NPM instalado  

### Passos  
1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/viatrack.git
