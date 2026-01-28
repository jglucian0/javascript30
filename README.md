# JavaScript30 - Log de Aprendizado

Este repositório foi criado para documentar meu progresso no desafio **JavaScript30**, criado por Wes Bos. O objetivo é concluir 30 projetos em 30 dias, utilizando exclusivamente JavaScript puro (Vanilla JS), sem bibliotecas ou frameworks.

## 🎯 O Desafio

O foco aqui não é apenas reproduzir o código das aulas, mas entender profundamente os conceitos de manipulação de DOM, eventos de teclado, APIs do navegador e lógica de programação que muitas vezes ficam omitidos por frameworks modernos.

### Minhas Expectativas

- **Domínio do DOM:** Consolidar a manipulação de elementos e atributos sem depender de abstrações.
- **Fundamentos Sólidos:** Entender a fundo conceitos como Event Delegation, Array Methods (map, filter, reduce) e a sincronia entre JS e transições de CSS.
- **Consistência:** Estabelecer uma rotina diária de resolução de problemas lógicos.
- **Exploração de APIs Nativas:** Aprender a lidar com recursos nativos de áudio, vídeo, canvas e sensores do navegador.

---

## 🛠️ Tecnologias Utilizadas

- **JavaScript (ES6+):** O motor principal de todos os projetos.
- **HTML5/CSS3:** Estruturação e estilização avançada (variáveis CSS, Flexbox e Grid).
- **Dependências:** Nenhuma. O desafio segue a regra de "no framework, no compiler, no libraries".

---

## 📅 Progresso dos Projetos

Abaixo, a lista de cada desafio concluído e os principais aprendizados técnicos de cada um:

| Dia | Projeto                              | Principais Conceitos Aplicados                                                          |
| :-- | :----------------------------------- | :-------------------------------------------------------------------------------------- |
| 01  | [JavaScript Drum Kit](./01-drum-kit) | Event Listeners (`keydown`), `transitionend`, manipulação de áudio e `data-attributes`. |

_(Atualizado conforme o progresso no curso)_

---

## 💡 Notas de Estudo e "Sacoladas"

Durante os projetos, anoto aqui descobertas que ainda não eram do meu conhecimento e foram fundamentais para o entendimento do código:

- **Manipulação de Áudio:** O uso do `audio.currentTime = 0` é essencial para permitir que sons sejam reiniciados instantaneamente sem delay.
- **Sincronia JS/CSS:** O evento `transitionend` é mais performático e seguro para remover classes de animação do que utilizar `setTimeout`, pois ele se comunica diretamente com o fim da transição definida no CSS.
- **Looping de Elementos:** O uso do `.forEach()` para adicionar ouvintes de eventos em múltiplos elementos selecionados via `querySelectorAll`.

---

## 🚀 Como rodar os projetos

Como os projetos são em JavaScript puro, não é necessário configurar ambientes complexos ou rodar gerenciadores de pacotes.

1. Clone o repositório:

   ```bash
   git clone [https://github.com/jglucian0/javascript30.git](https://github.com/jglucian0/javascript30.git)
   ```

2. Abra a pasta do dia específico.

3. Execute cada arquivo 'index-START.html' diretamente no navegador ou utilize a extensão Live Server no VS Code para hot-reload.
