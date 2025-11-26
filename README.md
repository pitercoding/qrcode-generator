# 📱 QRCode Generator  
Um gerador de QR Code simples, rápido e responsivo desenvolvido com **VueJS** e **QRious**, ideal para praticar fundamentos do framework e manipulação reativa no front-end.

O projeto permite gerar QR Codes dinamicamente conforme o usuário digita no campo de texto. Não utiliza bundlers ou ferramentas de build — tudo funciona apenas com **HTML, CSS e JavaScript**, tornando o projeto leve e fácil de entender.

---

## 🚀 Objetivos do Projeto

- Criar um gerador de QR Code totalmente funcional com VueJS.
- Praticar:
  - Bindings reativos (`v-model`)
  - Uso de *computed properties*
  - Manipulação de bibliotecas externas (QRious)
- Desenvolver um layout simples, limpo e responsivo.
- Publicar o projeto como site estático no Vercel.
- Estruturar um projeto Vue “sem build”, usando apenas arquivo `.js`.

## 🖥️ Funcionalidades Implementadas

### 🔹 Geração dinâmica de QR Code
- O QR é atualizado automaticamente conforme o usuário digita.
- Compatível com qualquer tipo de texto, URL ou informação.

### 🔹 VueJS sem build
- Uso direto com CDN (`vue.min.js`).
- Instância Vue simples e clara para aprendizado.

### 🔹 Layout responsivo
- Interface centralizada e fácil de usar.
- Campo de input e QR Code ajustados para telas pequenas.

### 🔹 Identidade visual leve
- Fonte personalizada (Roboto Mono).
- Gradiente no background.
- Container estilizado para o output.

## 🗂️ Estrutura do Projeto
```bash
qrcode-generator/
├─ css/
│  └─ style.css
│
├─ fonts/
│  └─ RobotoMono-Thin.ttf
│
├─ js/
│  ├─ qrious.min.js
│  └─ vue.min.js
│
├─ favicon.ico
├─ index.html
├─ LICENSE
└─ README.md
```

## 📦 Tecnologias Utilizadas

- **VueJS 2** (via CDN)
- **QRious**
- **CSS puro**
- **HTML5**
- **Vercel**

## 🔧 Como rodar o projeto

Este projeto **não precisa de npm, build ou dependências**.

### ▶️ Execute com:

1. Clone o repositório:  
   ```sh
   git clone https://github.com/pitercoding/qrcode-generator.git
   ```

2. Entre na pasta::  
   ```sh
   cd qrcode-generator
   ```

3. Abra o arquivo `index.html`:  
   * Dê dois cliques, ou
   * Use o **Live Server** no VS Code.

## 🌐 Deploy na Vercel

Como o projeto é **100% estático**, use estas configurações:
- **Framework Preset**: `Other`
- **Build Command**: _(deixe vazio)_
- **Output Directory**: `/`
- **Root Directory**: `.`

A Vercel detecta e publica automaticamente o `index.html`.

## 🤝 Contribuições

Contribuições são bem-vindas!

1. Faça um fork
2. Crie uma branch:
  ```sh
  git checkout -b minha-feature
  ```

3. Commit suas alterações:
  ```sh
  git commit -am "feat: nova feature adicionada"
  ```

4. Faça push:
  ```sh
  git push origin minha-feature
  ```

5. Abra um Pull Request


## 👨‍💻 Autor

Desenvolvido por 🔗 [**pitercoding**](https://github.com/pitercoding)

Projeto criado para estudo e prática de VueJS e manipulação de QR Codes.

## 📄 Licença

Este projeto está licenciado sob a **MIT License**.
