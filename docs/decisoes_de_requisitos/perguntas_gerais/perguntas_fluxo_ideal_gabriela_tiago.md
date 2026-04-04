# Perguntas para Definicao do Fluxo Ideal - Battle Class

> Contexto: A ideia original propunha batalhas PvP em tempo real com perguntas. Na reuniao, o grupo decidiu por um modelo de **duas fases**: responder perguntas para ganhar moedas, e depois jogar um tower defense. As perguntas abaixo buscam alinhar o fluxo completo.

---

## 1. Fase de Perguntas (Estudo)

1.1. O jogador responde perguntas **sozinho** (single-player) ou ainda existe algum componente multiplayer/competitivo nessa fase?

O jogador pode responder sozinho. Poderia ter um componente competitivo opcional, como comparar pontuações com amigos ou participar de desafios semanais, como features adiconais ao MVP.

1.2. As perguntas sao organizadas por **prova/disciplina** (ex: ENEM Matemática) ou o jogador escolhe livremente?

Seria interessante organizar por prova/disciplina para facilitar o estudo focado, mas também permitir uma opção de "modo livre" para quem quiser praticar de forma mais variada, tal como um simulado.

1.3. Existe um **limite de perguntas por sessao**? (ex: 10 perguntas por rodada, ou joga ate cansar?)

Poderia haver um limite de perguntas por sessão para manter o foco e evitar fadiga, como 10 ou 20 perguntas (base/default), mas também permitir que o jogador escolha quando encerrar a sessão e quantidade de perguntas.

1.4. A recompensa em moedas depende de que? Apenas acerto? Tambem velocidade? Combo/streak de acertos consecutivos?

A recompensa poderia ser baseada principalmente nos acertos, mas também incluir um bônus por velocidade e um sistema de streak para incentivar a consistência. Por exemplo, cada acerto vale 10 moedas, com um bônus de 5 moedas por resposta rápida (dentro de 30 segundos) e um multiplicador de streak que aumenta a cada acerto consecutivo.

1.5. Existe um **tempo limite por pergunta** ou o jogador responde no seu ritmo?

Poderia haver um tempo limite para adicionar um elemento de desafio, como 60 segundos por pergunta, mas também permitir que o jogador escolha jogar sem limite de tempo (modo ZEN) para praticar no seu ritmo.

1.6. Apos errar, o jogador **ve a resposta correta / explicacao**, ou apenas segue em frente?

Seria importante mostrar a resposta correta e uma explicação breve para promover o aprendizado, isso ajuda o jogador a entender seus erros e melhorar. Ter um modo de jogo onde isso é opcional, para quem quiser um desafio maior, mostrando apenas no final as respostas.

---

## 2. Economia de Moedas

2.1. As moedas servem **apenas** para o tower defense (comprar torres, upgrades) ou tambem para cosmeticos/perfil?

Inicialmente, as moedas poderiam ser usadas apenas para o tower defense para manter o foco, mas futuramente poderiam ser introduzidos itens cosméticos ou melhorias de perfil como opções adicionais para gastar as moedas.

2.2. Existe um **limite de moedas que se pode acumular** antes de jogar o tower defense?

Não vejo necessidade de um limite de moedas, isso permitiria que os jogadores acumulem e planejem melhor suas estratégias para o tower defense. Poderia haver um limite máximo para evitar acúmulo excessivo, mas não seria necessário para o MVP.

2.3. As moedas sao **gastas permanentemente** no tower defense (a cada partida você usa e perde), ou sao persistentes?

Gastar permanentemente faria mais sentido para criar um desafio e incentivar o estudo contínuo para ganhar mais moedas. Isso também adiciona um elemento de risco/recompensa ao jogar o tower defense, tornando as decisões de compra mais estratégicas.

2.4. Existe alguma outra forma de ganhar moedas alem de responder perguntas? (ex: login diario, missoes)

Para o MVP, focar apenas nas moedas ganhas por responder perguntas seria mais simples, mas futuramente poderiam ser introduzidos outros métodos de ganhar moedas, como login diário, missões diárias/semanais ou eventos especiais para manter os jogadores engajados.

---

## 3. Fase de Tower Defense

3.1. O tower defense é **PvP** (jogador vs jogador, cada um com suas torres) ou **PvE** (jogador vs ondas de inimigos controlados pelo sistema)?

Para o MVP, focar em um modo PvE seria mais simples e permitiria que os jogadores se acostumassem com a mecânica do tower defense antes de introduzir a complexidade do PvP.

3.2. Se for PvP: é em **tempo real simultaneo** (ambos jogam ao mesmo tempo) ou **assincrono** (você ataca a base do outro que ja foi montada)?

Não se aplica para o MVP, já que o foco inicial seria no modo PvE. Se um modo PvP for introduzido futuramente, poderia ser interessante explorar ambos os formatos (tempo real e assíncrono) para oferecer diferentes experiências de jogo.

3.3. As moedas ganhas nas perguntas sao usadas **dentro da partida** para comprar/posicionar torres? Ou sao usadas **antes** para montar um deck/loadout?

As moedas seriam usadas antes da partida para montar um deck ou loadout de torres, o que adiciona um elemento de estratégia e planejamento antes de enfrentar as ondas de inimigos. Durante a partida, os jogadores poderiam ganhar recursos adicionais para fazer compras limitadas, mas o grosso do investimento seria feito na preparação.

3.4. Quanto tempo dura uma partida de tower defense em media? (1-2 min? 5 min? 10+ min?)

Para manter o jogo dinâmico, as partidas poderiam durar entre 1 a 3 minutos em média, dependendo da dificuldade e do número de ondas. Isso permite que os jogadores tenham uma experiência satisfatória sem se sentir sobrecarregados.

3.5. O tower defense tem **tematica educacional** (ex: torres com nomes de disciplinas, inimigos representando "ignorancia") ou é tematica separada?

A temática educacional poderia ser interessante para reforçar a conexão entre as perguntas e o tower defense, como torres representando diferentes disciplinas (Matemática, História, etc.) e inimigos representando "ignorância" ou "dúvidas". No entanto, para o MVP, uma temática mais neutra poderia ser mais fácil de implementar, com a possibilidade de adicionar elementos educacionais futuramente.

3.6. Inspiracao principal é **Bloons TD 6** (referencia na ata). Quais elementos do BTD6 vocês querem manter? (mapa fixo, tipos de torre variados, upgrades em arvore, ondas progressivas?)

A inspiração no Bloons TD 6 é ótima, e alguns elementos que poderiam ser mantidos incluem:

- Mapas variados com diferentes layouts.
- Tipos de torres variadas com diferentes habilidades e funções.
- Sistema de upgrades em árvore para personalizar as torres.

    3.7. Existe **matchmaking por nivel/elo** ou qualquer jogador joga contra qualquer um?

Em um modo PvE, o matchmaking não se aplica, já que os jogadores enfrentariam ondas de inimigos controlados pelo sistema. Se um modo PvP for introduzido futuramente, poderia ser interessante implementar matchmaking por nível ou elo para garantir partidas equilibradas e desafiadoras para os jogadores.

---

## 4. Loop Geral e Progressao

4.1. O loop ideal seria: **Estudar → Ganhar moedas → Jogar TD → Repetir**. Existe algo mais nesse ciclo? (ex: abrir novos mapas, desbloquear torres?)

Acredito que esse loop básico é sólido para o MVP, mas futuramente poderiam ser adicionados elementos como desbloqueio de novos mapas, torres ou modos de jogo para manter os jogadores engajados e oferecer uma sensação de progressão contínua.

4.2. Existe um **sistema de nivel/XP do jogador** alem das moedas? O que ele desbloqueia?

Para o MVP, focar apenas nas moedas como forma de progressão seria mais simples, mas futuramente poderia ser interessante introduzir um sistema de nível ou XP que desbloqueie novos conteúdos, como torres especiais, mapas adicionais ou modos de jogo exclusivos.

4.3. Existe **ranking/leaderboard**? Se sim, é baseado em performance no TD, nas perguntas, ou ambos?

Para o MVP, um ranking baseado nas perguntas respondidas poderia ser uma boa forma de incentivar a competição saudável entre os jogadores. Futuramente, um ranking específico para o tower defense também poderia ser introduzido para aqueles que se destacam nessa fase do jogo.

4.4. Existem **temporadas** ou a progressao é continua?

Para o MVP, uma progressão contínua seria mais simples de implementar.

4.5. Existem **conquistas/achievements**? (ex: "Acertou 50 questoes de matemática", "Venceu 10 partidas de TD")

Para o MVP, focar nas funcionalidades principais seria mais importante, mas futuramente poderiam ser introduzidos achievements para incentivar os jogadores a explorar diferentes aspectos do jogo e celebrar suas conquistas.

---

## 5. Escopo do MVP (disciplina)

5.1. Para o MVP da disciplina, quais funcionalidades sao **essenciais** vs "legal ter depois"?

- [x] Login/cadastro
- [x] Responder perguntas (qual area?)
- [x] Ganhar moedas
- [x] Tower defense básico funcional
- [x] PvP ou apenas PvE?  PvE funcional
- [x] Ranking -> Apenas das questões
- [x] Perfil com estatisticas
- [x] Painel admin para questoes

5.2. Para o MVP, o tower defense pode ser **simplificado** (ex: menos tipos de torre, mapa único)? Qual o nivel minimo aceitavel?

Para o MVP, o tower defense simplificado com um número limitado de tipos de torres (por exemplo, 3 tipos básicos) e um mapa único para focar na implementação da mecânica principal. O nível mínimo aceitável seria ter uma experiência de jogo funcional onde os jogadores possam usar as moedas ganhas para comprar torres e enfrentar ondas de inimigos, mesmo que seja em um cenário mais simples.

5.3. O banco de questoes inicial vem de onde? Questoes criadas pelo grupo? Importadas de provas reais?

Para o MVP, usar questões geradas por IA pode ser mais rápido e flexível, mas futuramente poderia ser interessante incorporar questões de provas reais para aumentar a relevância e autenticidade do conteúdo educacional.

---
