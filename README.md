# APS - Análise e Aplicação do Framework Vue.js 3

Aplicação frontend desenvolvida para a Atividade Prática Supervisionada (APS) da disciplina de Desenvolvimento de Aplicações Corporativas (DAC) - Centro Universitário Unifametro.

## 🚀 Sobre o Projeto
Catálogo dinâmico de postagens que consome a API pública REST **JSONPlaceholder**, implementando renderização dinâmica, filtragem em tempo real e visualização de detalhes em janela modal.

## 🛠️ Tecnologias Utilizadas
* **Vue.js 3** (via CDN - Vue Global Build)
* **HTML5 Semântico**
* **CSS3** (CSS Grid e Flexbox)
* **JavaScript ES6+** (Fetch API assíncrono)

## ✨ Funcionalidades
* Consumo assíncrono de endpoint público (`GET /posts`).
* Tratamento visual de estados de requisição (carregamento e tratamento de erro de rede).
* Reatividade de dados com `ref()` e `computed()` da Composition API.
* Busca instantânea por termo digitado no cabeçalho.
* Modal interativo de detalhamento acionado ao clicar em qualquer card.

## 💻 Como Executar
Por utilizar a distribuição oficial do Vue.js 3 via CDN, a execução dispensa etapas de compilação ou instalação de pacotes locais:
1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/aps-dac-vuejs.git](https://github.com/SEU_USUARIO/aps-dac-vuejs.git)