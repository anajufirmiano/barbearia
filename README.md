# 💈 Barbearia Vintage | Estilo, Tradição & Agendamento Online

> **Modelo conceitual e responsivo de Landing Page para barbearias, salões masculinos e estética, desenvolvido para portfólio profissional de desenvolvimento Web.**

---

## 📌 Sobre o Projeto

Este projeto é uma **Landing Page moderna e autoral** desenvolvida para simular a presença online de uma barbearia clássica e contemporânea. O objetivo principal da página é atrair novos clientes, destacar os diferenciais do atendimento e facilitar a conversão rápida através do agendamento direto por WhatsApp.

O visual adota a estética *Dark & Gold* (#121212 e dourado nobre #d4af37), com tipografia limpa (*Montserrat*), contrastes nítidos e transições suaves, transmitindo sofisticação e profissionalismo.

> [!NOTE]
> Este projeto foi desenvolvido como **modelo genérico para portfólio**, podendo ser facilmente personalizado e adaptado para barbearias, salões de beleza, estúdios de tatuagem ou negócios que prestem serviços com hora marcada.

---

## ✨ Funcionalidades e Seções

- **Hero Header de Alto Impacto:**
  - Imagem de fundo imersiva com overlay gradiente escuro.
  - Badge em destaque ("Estilo & Tradição"), chamada comercial forte e botão de ação imediato para agendamento.
- **Seção de Diferenciais ("Por Que Nos Escolher?"):**
  - Cards visuais com ícones vetoriais destacando profissionais experientes, espaço climatizado com café cortesia e atendimento sem filas de espera.
- **Tabela de Serviços & Preços:**
  - Lista clara de serviços (Corte, Barba com Toalha Quente, Acabamento Express).
  - Destaque visual estilizado para o pacote de maior saída (**Combo Cabelo + Barba**).
- **Chamada de Conversão (CTA) & Agendamento:**
  - Botão de contato integrado com API do WhatsApp, já preenchendo a mensagem inicial de agendamento.
  - Informações práticas de endereço físico e horário de funcionamento.
- **Botão Flutuante do WhatsApp:**
  - Fixo no canto inferior direito para acesso rápido em qualquer rolagem de tela.
- **Design 100% Responsivo:**
  - Layout otimizado para celulares, tablets e telas de computador com uso de `clamp()` para tipografia fluida.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Estruturação otimizada para SEO e acessibilidade (`<header>`, `<section>`, `<footer>`, `<nav>`).
- **CSS3 Moderno:**
  - Flexbox e CSS Grid para alinhamento e distribuição equilibrada dos cards.
  - Tipografia fluida com `clamp()` e sombras suaves.
  - Efeitos de `hover` nos botões e transições animadas.
- **Google Fonts:** Tipografia *Montserrat* para alta legibilidade e estilo contemporâneo.
- **Ícones Vetoriais (SVG):** Ícones inline leves e nítidos em qualquer resolução.

---

## 📂 Estrutura de Arquivos

```bash
barbearia/
│
├── index.html        # Estrutura semântica e conteúdo da landing page
├── style.css         # Estilização completa, tema escuro e responsividade
└── README.md         # Documentação completa do projeto
```

---

## 🚀 Como Executar Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/anajufirmiano/barbearia.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd barbearia
   ```
3. Abra o arquivo `index.html` em seu navegador:
   - Dê um duplo clique no arquivo `index.html`; ou
   - Use a extensão **Live Server** no VS Code.

---

## 🎨 Como Personalizar para o seu Negócio

1. **Número e Mensagem do WhatsApp:**
   - No arquivo `index.html`, procure por `https://wa.me/55...` e substitua pelo número oficial do estabelecimento com DDD.
2. **Serviços e Valores:**
   - Na seção `#servicos`, personalize os títulos (`<h4>`), descrições (`<small>`) e preços (`<span class="valor">`).
3. **Endereço e Horários:**
   - Na seção `#agendamento`, altere o endereço e horário comercial na div `.info-local`.
4. **Paleta de Cores:**
   - No arquivo `style.css`, altere a cor de destaque (atualmente dourada `#d4af37`) e o fundo (`#121212`) para refletir a marca desejada.

---

## 👩‍💻 Autora

Desenvolvido por **Ana Júlia Ferreira Firmiano**  
- **GitHub:** [@anajufirmiano](https://github.com/anajufirmiano)  
- **Portfólio:** [anajufirmiano.github.io](https://anajufirmiano.github.io/)

---

## 📄 Licença

Este projeto é livre para estudos, referência e personalização para projetos pessoais ou comerciais.
