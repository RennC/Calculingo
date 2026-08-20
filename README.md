# Calculingo

* Tinha essa ideia há muito tempo, mas não sei programar então parecia um projeto distante. Matriculei-me então no curso de Antigravity do Senai SCS e fiz esse APP totalmente vibecodado

* Tenho noção que não sou chefe porque preparei um miojo (Valeu AKita) 

# Portal Gamificado de Exatas

* Um aplicativo de estudos focado em Ciências Exatas (Matemática e Física), concebido sob a filosofia do "App de Trem": focado em raciocínio lógico rápido, resolução mental e identificação de falácias, sem a necessidade de papel e caneta.

# Expectativas com esse projeto

* Pretendo utilizar esse projeto para:

1. Aprender mais sobre programação.
2.  Interagir com as pessoas que entendem mais e desejam levar a ideia para frente
3.   Melhorar minhas notas na UFABC (kkkrying) estudando mais no trem

# Funcionalidades
(Não entendo nenhuma linguagem ou tecnologia que está aqui, acho que dará para perceber, mas a princípio fiz para tirar a ideia da cabeça)

* **Arquitetura Offline-First (Local):** Não requer servidores, banco de dados em nuvem ou processos de build (Node.js/NPM). Funciona nativamente através do protocolo `file://` no navegador.
* **Design Renascentista e Imersivo:** Interface estilizada como manuscritos antigos, com cursores de pena de tinta, cores de pergaminho e tipografia clássica (Cormorant Garamond).
* **Gamificação Dinâmica:** Sistema de "Vidas" (velas) e ganho de XP (graus), que por agora não faz sentido, (progresso não é salvo) mas em futuras atualizações fará.
* Ao errar uma questão, ela é enviada para o final da fila de estudos da fase atual, forçando a repetição espaçada.
* **Acesso Livre (Open Map):** Todas as fases e trilhas (Cálculo e Física) estão desbloqueadas desde o início, permitindo total liberdade de escolha.
* **Renderização Matemática Nativa:** Utilização do KaTeX embarcado para renderização em tempo real de equações e fórmulas complexas.
* **Responsividade Fluida:** Otimizado com classes `dvh` para ser a melhor experiência possível em telas de celulares, mas perfeitamente adaptável para computadores e monitores largos (isso ainda tá feio).

# Tecnologias Utilizadas

Apesar de ser um único arquivo `index.html`, o portal utiliza o poder de bibliotecas modernas através de injeções via CDN:

* **React (v18) & ReactDOM:** Para o gerenciamento de estados gamificados e renderização condicional.
* **Babel Standalone:** Transpilação em tempo real de código JSX diretamente no navegador do usuário.
* **Tailwind CSS:** Injetado e configurado globalmente para estilização rápida e responsiva.
* **KaTeX:** Motor matemático de altíssimo desempenho.

# Como Jogar / Executar

Como este é um projeto sem dependências de servidor, usá-lo é extremamente simples:

1. Baixe o arquivo `index.html` deste repositório (você pode clicar no arquivo e usar o botão de *Download* ou *Raw*).
2. Salve o arquivo em qualquer pasta do seu computador ou na memória do seu celular.
3. Dê dois cliques no arquivo (ou toque nele) para abri-lo com o seu navegador padrão (Chrome, Safari, Firefox, Edge).
4. Pronto! O ambiente gamificado será carregado imediatamente, sem necessidade de internet.

# A Filosofia Pedagógica ("App de Trem")

Os exercícios deste portal fogem das listas de cálculos morosas tradicionais. As baterias de perguntas focam em:

* **O Próximo Passo Lógico:** Mostrar uma equação complexa e perguntar apenas qual seria a próxima regra a se aplicar.
* **Caça à Falácia:** Identificar quebras matemáticas (como divisões por zero) em deduções passo a passo.
* **Abstração Teórica:** Testes rápidos de Verdadeiro/Falso sobre leis fundamentais da física e do cálculo.

---
# Futuras melhorias:
* Aumentar o banco de dados das questões para que não se repitam (talvez gerar com IA ou buscar banco de dados na internet)
* Tirar as questões do HTML (quando o APP tiver bom, porque não quero hospedar enquanto não estiver legal)
* Inserir sistema para armazenamento de login, para que o XP faça sentido. (Não fiz isso para não vazar seus dados na rede querido estudante)

# Sugestões e melhorias são muito bem-vindas, valeu! =DDDD
