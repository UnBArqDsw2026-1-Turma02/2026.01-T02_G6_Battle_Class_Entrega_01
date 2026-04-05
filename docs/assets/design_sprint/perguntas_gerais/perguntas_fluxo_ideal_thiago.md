# Perguntas para Definicao do Fluxo Ideal - Battle Class

> Contexto: A ideia original propunha batalhas PvP em tempo real com perguntas. Na reuniao, o grupo decidiu por um modelo de **duas fases**: responder perguntas para ganhar moedas, e depois jogar um tower defense. As perguntas abaixo buscam alinhar o fluxo completo.

---

## 1. Fase de Perguntas (Estudo)

1.1. O jogador responde perguntas **sozinho** (single-player) ou ainda existe algum componente multiplayer/competitivo nessa fase?

Acredito que nessa parte seria melhor focar apenas em single-player pois além de ajudar no desenvolvimento daria uma oportunidade melhor de colocar perguntas mais complicadas

1.2. As perguntas sao organizadas por **prova/disciplina** (ex: ENEM Matematica) ou o jogador escolhe livremente?

Seria legal separar por tópicos mesmo, as vezes a pessoa usa o software já com um propósito de estudo, acredito que ficar respondendo perguntas fora do escopo que ela procura seria desinteressante.

1.3. Existe um **limite de perguntas por sessao**? (ex: 10 perguntas por rodada, ou joga ate cansar?)

Até cansar

1.4. A recompensa em moedas depende de que? Apenas acerto? Tambem velocidade? Combo/streak de acertos consecutivos?

O streak pra mim é indispensável pra manter a atenção e vontade do usuário, não sei se velocidade cabe na ideia geral.

1.5. Existe um **tempo limite por pergunta** ou o jogador responde no seu ritmo?

No seu ritmo.

1.6. Apos errar, o jogador **ve a resposta correta / explicacao**, ou apenas segue em frente?

Com certeza deveria ver, afinal a ideia do software em sua base é o estudo.

---

## 2. Economia de Moedas

2.1. As moedas servem **apenas** para o tower defense (comprar torres, upgrades) ou tambem para cosmeticos/perfil?

Seria interessante a ideia de perfil principalmente pra ter como adicionar pessoas próximas aumentando a distribuição do software

2.2. Existe um **limite de moedas que se pode acumular** antes de jogar o tower defense?

Acho interessante essa ideia, mas ainda não sei como balancear isso.

2.3. As moedas sao **gastas permanentemente** no tower defense (a cada partida voce usa e perde), ou sao persistentes?

São gastas, mas tem que valer a pena o investimento.

2.4. Existe alguma outra forma de ganhar moedas alem de responder perguntas? (ex: login diario, missoes)

Outra forma interessante de prender o usuário, ficaria legal.

---

## 3. Fase de Tower Defense

3.1. O tower defense eh **PvP** (jogador vs jogador, cada um com suas torres) ou **PvE** (jogador vs ondas de inimigos controlados pelo sistema)?


PvE (com talvez uma futura atualização PvP)
3.2. Se for PvP: eh em **tempo real simultaneo** (ambos jogam ao mesmo tempo) ou **assincrono** (voce ataca a base do outro que ja foi montada)?

Ao mesmo tempo.

3.3. As moedas ganhas nas perguntas sao usadas **dentro da partida** para comprar/posicionar torres? Ou sao usadas **antes** para montar um deck/loadout?

Acredito que seja legal aproveitar os dois mundos.

3.4. Quanto tempo dura uma partida de tower defense em media? (1-2 min? 5 min? 10+ min?)

Depende do quão forte o jogador esteja, se tiver muito forte fica bastante tempo, se estiver fraco provavelmente perderá muito rápido

3.5. O tower defense tem **tematica educacional** (ex: torres com nomes de disciplinas, inimigos representando "ignorancia") ou eh tematica separada?

Acredito que seja sim uma boa ideia manter o tema.

3.6. Inspiracao principal eh **Bloons TD 6** (referencia na ata). Quais elementos do BTD6 voces querem manter? (mapa fixo, tipos de torre variados, upgrades em arvore, ondas progressivas?)

Mapa fixo é muito útil e também upgrades de torres, o resto ainda teria que testar se caberia.

3.7. Existe **matchmaking por nivel/elo** ou qualquer jogador joga contra qualquer um?

Acredito que por nível ficaria bom.

---

## 4. Loop Geral e Progressao

4.1. O loop ideal seria: **Estudar → Ganhar moedas → Jogar TD → Repetir**. Existe algo mais nesse ciclo? (ex: abrir novos mapas, desbloquear torres?)

Sim, abrir novos mapas, desbloquear torres e upgrades.

4.2. Existe um **sistema de nivel/XP do jogador** alem das moedas? O que ele desbloqueia?

Sim, acredito que seria bom xp ao eliminar inimigos e ao passar rodadas.

4.3. Existe **ranking/leaderboard**? Se sim, eh baseado em performance no TD, nas perguntas, ou ambos?

Seria interessante em ambos.

4.4. Existem **temporadas** ou a progressao eh continua?

No momento acredito que contínua

4.5. Existem **conquistas/achievements**? (ex: "Acertou 50 questoes de matematica", "Venceu 10 partidas de TD")

Sim, ficaria bom.

---

## 5. Escopo do MVP (disciplina)

5.1. Para o MVP da disciplina, quais funcionalidades sao **essenciais** vs "legal ter depois"?
   - [x] Login/cadastro
   - [x] Responder perguntas (qual area?)
   - [x] Ganhar moedas
   - [x] Tower defense basico funcional
   - [ ] PvP ou apenas PvE?
   PvE funcional
   - [ ] Ranking
   - [x] Perfil com estatisticas
   - [ ] Painel admin para questoes

5.2. Para o MVP, o tower defense pode ser **simplificado** (ex: menos tipos de torre, mapa unico)? Qual o nivel minimo aceitavel?

Acredito que se por exemplo tivessemos 10 torres para se defender no PvE, no PvP distribuir 4 torres de forma aleatória para ambos (as mesmas torres), ficaria balanceado.
---


