# Moto Cidade - Concessionária de Motos Usadas

**Disciplina:** Aplicações para Internet  
**Professor:** Daniel Brandão  
**Período:** 2024.1

## 📌 Descrição Geral

O projeto **Moto Cidade** é um sistema web desenvolvido com o objetivo de simular o site de uma **concessionária de motos usadas**, com páginas informativas, vitrine de motos, formulário de contato, agendamento de test drives e área de envio de currículos. Foi criado como parte da disciplina de Aplicações para Internet, utilizando tecnologias como **HTML5, CSS3, Bootstrap** e manipulação de dados via **JSON**.

## 🚀 Funcionalidades

- Página inicial com apresentação da empresa e 3 motos em destaque aleatórias
- Endereços de 3 lojas (João Pessoa - Centro e Bancários, Campina Grande - Centro)
- Página de Estoque com exibição dinâmica de dezenas de motos a partir de `motos.json`
- Destaque da loja de origem de cada moto
- Página de Detalhes + Agendamento de Test Drive
  - Preenchimento dinâmico da moto selecionada
  - Validação de campos obrigatórios
  - Mensagem de confirmação e redirecionamento
- Página de Contato com formulário
- Página “Trabalhe Conosco”
  - Lista de vagas por loja
  - Formulário com envio de currículo (PDF)
  - Mensagem de sucesso e redirecionamento

## 🎨 Identidade Visual

Layout limpo e responsivo com Bootstrap 5, logomarca própria, cores institucionais (vermelho, preto e branco), e organização visual intuitiva. A navegação é feita por uma **navbar comum a todas as páginas**, carregada dinamicamente.

## 🧩 Estrutura do Projeto

```text
motoCidade/
├── MotoCidade.html         # Página principal
├── estoque.html            # Galeria de motos (dinâmico)
├── agendamento.html        # Detalhes da moto e agendamento
├── trabalhe-conosco.html   # Lista de vagas e envio de currículo
├── navbar.html             # Menu compartilhado via JavaScript
├── motos.json              # Base de dados simulada das motos
├── img/
│   ├── logo.png
│   ├── xre300.png
│   ├── fazer250.png
│   ├── cg160.png
│   └── moto4.png ... moto20.png
└── README.md               # Documento atual
```

## 👨‍💻 Equipe de Desenvolvimento

| Nome                            | Função                 |
|---------------------------------|------------------------|
| Marcus Vinícius Maracajá Pires | Desenvolvedor Front-end |

## 📅 Cronograma

| Data       | Entrega                                     |
|------------|---------------------------------------------|
| 08/05/2025 | Definição do projeto e repositório          |
| 15/05/2025 | Checkpoint do projeto                       |
| 22/05/2025 | Entrega parcial do projeto                  |
| 29/05/2025 | Apresentação e entrega final                |

## 📎 Link do Repositório

[https://github.com/MarcusMaracaja/motoCidade.git](https://github.com/MarcusMaracaja/motoCidade.git)

## ✅ Tecnologias Utilizadas

- HTML5
- CSS3
- Bootstrap 5
- JavaScript (DOM + fetch API)
- JSON (dados das motos)
- Git e GitHub

## 💡 Requisitos Atendidos

- [x] Layout responsivo e visual limpo
- [x] Múltiplas páginas com navegação integrada
- [x] Exibição dinâmica de dados via JSON
- [x] Formulários com validação e feedback ao usuário
- [x] Identidade visual personalizada com logomarca
- [x] Estrutura modular com reaproveitamento de código
- [x] Documentação clara e organizada no GitHub

## 🧾 Observações

O sistema é 100% estático, mas simula funcionalidades de uma aplicação real. Os dados das motos são carregados dinamicamente de um arquivo `motos.json`, como se fossem fornecidos por uma API de um sistema interno da empresa. Ideal para prototipagem e apresentação em sala de aula.
