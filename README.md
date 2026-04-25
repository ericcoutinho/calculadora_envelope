# 🦒📐 Calculadora de Envelopes & Caixas

Uma calculadora precisa e mobile-first para criação de **envelopes e caixas** utilizando a *Envelope Punch Board*.

👉 Desenvolvido com base em **tabelas reais de referência**, garantindo resultados confiáveis.

---

## ✨ Funcionalidades

- 📦 Cálculo de **envelopes**
- 🎁 Cálculo de **caixas (3D)**
- 📏 Suporte a **cm e polegadas**
- 📊 Baseado em **tabelas oficiais**
- 📱 Interface otimizada para **celular**
- ⚡ Funciona **offline (PWA)**
- 🧠 Ajuste automático (usa próximo valor válido da tabela)
- 🔒 Modo **objeto quadrado**
- 🎯 UX estilo app (teclado, vibração, animações)

---

## 🚀 Como usar

### 🔗 Online
Acesse via GitHub Pages:

https://SEU-USUARIO.github.io/SEU-REPO/

---

### 📱 Instalar como App (iPhone / Android)

1. Abra no navegador  
2. Toque em **Compartilhar**  
3. Selecione **"Adicionar à Tela de Início"**

✔️ Abre como app  
✔️ Funciona offline  
✔️ Sem barra do navegador  

---

## 🧠 Como funciona o cálculo

### Envelope
- Baseado em **tabela de medidas reais**
- Se não houver correspondência exata:
→ usa o **próximo tamanho maior**

### Caixa
- Usa tabela com:
- 📄 Tamanho do papel  
- 📍 Linha inicial (S, M, L, XL)  
- 📐 Linha diagonal  

---

## 🛠️ Tecnologias

- HTML puro  
- CSS (mobile-first)  
- JavaScript vanilla  
- Service Worker (offline)  
- PWA (Progressive Web App)  

---

## 📁 Estrutura

/
├── index.html  
├── sw.js  
├── site.webmanifest  
├── favicon.ico  
├── icon-192.png  
├── icon-512.png  
├── splash.png  

---

## 🔄 Atualizações (importante)

Se você modificar o app:

👉 altere a versão do cache em `sw.js`

```js
const CACHE_NAME = "calculadora-vX";
```

Senão o app instalado não atualiza.

---

## 🎨 Design

- Tema: verde + amarelo (girafa 🦒)  
- UX inspirado em apps mobile  
- Feedback com animações + vibração  

---

## 📌 Observações

- Resultados seguem **tabela física real**  
- Pode haver pequenas diferenças de arredondamento  
- Ideal para uso em artesanato e papelaria  

---

## 📄 Licença

Uso livre para fins pessoais e comerciais.
