# 🏯 Busca CEP com Demon Slayer

Projeto desenvolvido com **HTML, CSS e JavaScript** que permite consultar informações de endereço a partir de um CEP utilizando a API ViaCEP. A interface foi personalizada com temática inspirada em **Demon Slayer**, proporcionando uma experiência visual diferenciada.

## 📸 Preview

O usuário informa um CEP e o sistema busca automaticamente:

- Estado
- Cidade
- Bairro
- Logradouro

Após a busca, os campos de número e complemento são liberados para preenchimento manual.

---

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- API ViaCEP

---

## 📂 Estrutura do Projeto

```bash
📦 busca-cep-demon-slayer
├── index.html
├── css
│   └── style.css
├── js
│   └── script.js
└── img
    ├── bg.png
    ├── banner.svg
    ├── eu.svg
    └── logo.svg
```

---

## ⚙️ Funcionalidades

✅ Busca automática de endereço por CEP

✅ Preenchimento automático dos campos:

- Estado
- Cidade
- Bairro
- Logradouro

✅ Liberação dos campos de Número e Complemento após a consulta

✅ Máscara automática para CEP

✅ Tratamento de CEP inválido

✅ Interface temática inspirada em Demon Slayer

✅ Design moderno com efeito Glassmorphism

---

## 🔗 API Utilizada

Este projeto utiliza a API pública ViaCEP para consulta de endereços.

Endpoint utilizado:

```url
https://viacep.com.br/ws/CEP/json/
```

Exemplo:

```url
https://viacep.com.br/ws/01001000/json/
```

---

## ▶️ Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/busca-cep-demon-slayer.git
```

2. Entre na pasta do projeto:

```bash
cd busca-cep-demon-slayer
```

3. Abra o arquivo:

```bash
index.html
```

ou utilize a extensão **Live Server** no VS Code.

---

## 🧠 Como Funciona

1. O usuário digita um CEP.
2. Ao clicar em **Buscar**, o sistema envia uma requisição para a API ViaCEP.
3. Os dados retornados são inseridos automaticamente nos campos do formulário.
4. Caso o CEP seja inválido, uma mensagem de erro é exibida.
5. Após uma busca válida, os campos de Número e Complemento são habilitados para preenchimento.

---

## 🎨 Destaques Visuais

- Fundo temático inspirado em Demon Slayer
- Layout responsivo
- Efeito de vidro (Glassmorphism)
- Formulário organizado e intuitivo
- Personagem ilustrado integrado à interface

---

## 🎯 Melhorias Futuras

- Busca automática ao terminar de digitar o CEP
- Validação mais robusta
- Integração com mapa
- Armazenamento de consultas recentes
- Tema claro e escuro
- Responsividade para dispositivos móveis

---

## 👨‍💻 Autor

Desenvolvido por **Gustavo Santos**.

Estudante e desenvolvedor apaixonado por tecnologia, programação e design de interfaces, sempre buscando aprimorar suas habilidades através da criação de projetos práticos.

⭐ Se este projeto te ajudou ou serviu de inspiração, deixe uma estrela no repositório!
