# Quiz - Design de Interação

[![Licença](https://img.shields.io/badge/licença-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-ativo-brightgreen.svg)]()
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5\&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3\&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript\&logoColor=black)]()

## 📖 Sobre o Projeto

Este é um **quiz interativo** desenvolvido para auxiliar no estudo da disciplina **Design de Interação**. O projeto foi criado com base no material de estudo da **Uninter** (aulas 1 a 6), oferecendo uma ferramenta prática para autoavaliação e revisão dos conceitos fundamentais de design de interfaces, usabilidade e experiência do usuário.

## 🎯 Finalidade

* **Uso Acadêmico:** complemento aos estudos da disciplina, permitindo que alunos testem seus conhecimentos de forma interativa.
* **Uso Pessoal:** ferramenta para revisão de conteúdos antes de provas e avaliações.
* **Recurso Didático:** material de apoio para professores e tutores da disciplina.

## ✨ Funcionalidades

* ✅ Questões objetivas baseadas nos conteúdos de Design de Interação
* ✅ Questões discursivas para aprofundamento teórico
* ✅ Navegação intuitiva por números
* ✅ Feedback imediato com resolução passo a passo
* ✅ Barra de progresso
* ✅ Sistema de pontuação
* ✅ Design responsivo
* ✅ Interface moderna
* ✅ Botão de reiniciar o quiz
* ✅ Seção de comentários discursivos com gabarito

## 📚 Conteúdo Abordado

| Ordem | Tema Principal |
| ----- | -------------- |
| 1 | Fundamentos de Design de Interação e Experiência do Usuário (UX/UI) |
| 2 | Modelo do Processador Humano (Card, Moran e Newell) e Psicologia Cognitiva |
| 3 | Heurísticas de Nielsen e Design de Interfaces Móveis |
| 4 | Design Responsivo (RWD), Design Adaptativo (AWD) e Mobile First |
| 5 | Componentes e Diretrizes do Material Design |
| 6 | Ferramentas de Prototipação (Balsamiq, Justinmind, Proto.io, UXPin, Figma, Adobe XD, Quant UX) |
| 7 | Wireframes, Esboços e Layouts |
| 8 | Prototipação (baixa e alta fidelidade) |
| 9 | Checkbox, Botões e Componentes de Interface |
| 10 | Evolução do HTML e Padrões Web |
| 11 | Gestalt aplicada ao Design de Interfaces |

## 🧠 Temas Discursivos

1. **Design Responsivo vs Design Adaptativo** – diferenças, aplicações e técnicas (media queries, grid fluído, imagens flexíveis)
2. **Heurísticas de Nielsen aplicadas ao Design Móvel** – visibilidade do sistema, prevenção de erros, reconhecimento vs memorização
3. **Ferramentas de Prototipação e suas funcionalidades** – Balsamiq, Justinmind, Proto.io, UXPin, Figma, Adobe XD, Quant UX
4. **Componentes e Diretrizes do Material Design** – barras de aplicativo, botões, listas, campos de entrada, checkbox
5. **Mobile First e Design Centrado no Usuário** – abordagem de projeto priorizando dispositivos móveis, conteúdo essencial e eliminação de excessos

## 🚀 Como Usar

### Acesse Online

O quiz está disponível através do GitHub Pages:

🔗 **[[ Acesse Online ](https://jonathastrevezani.github.io/Quiz_Design_Interacao/)]**

### Executar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/JonathasTrevezani/Quiz_Design_Interacao.git

2. Entre na pasta do projeto:

```bash
cd Quiz_Design_Interacao
```

3. Abra o arquivo `index.html` em seu navegador.

## 📁 Estrutura do Projeto

```text
Quiz-Design-Interacao/
├── index.html      # Estrutura principal do quiz
├── style.css       # Estilos e layout responsivo
├── script.js       # Lógica do quiz
├── README.md       # Documentação do projeto
└── LICENSE         # Licença MIT
```

🛠️ Tecnologias Utilizadas
HTML5 – Estrutura da aplicação

CSS3 – Estilização e responsividade

JavaScript – Lógica do quiz e manipulação do DOM

📊 Sistema de Pontuação
Cada questão vale aproximadamente 6,7 pontos.

São 15 questões, totalizando 100,5 pontos.

O resultado é calculado automaticamente ao final do quiz.

## 🔧 Personalização

Para adicionar ou modificar questões, edite o array `questions` no arquivo `script.js`:

```javascript
{
  text: "Enunciado da questão",
  alternatives: [
    "Alternativa A",
    "Alternativa B",
    "Alternativa C",
    "Alternativa D"
  ],
  correct: "B",
  explanation: "Resolução detalhada da questão..."
}
```

## 📝 Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais informações.

## 👨‍💻 Autor

**Jonathas Trevezani**

Projeto desenvolvido para fins acadêmicos e educacionais.

⭐ Caso este projeto seja útil para você, considere deixar uma estrela no repositório.

---

**Bons estudos! 🎓**
