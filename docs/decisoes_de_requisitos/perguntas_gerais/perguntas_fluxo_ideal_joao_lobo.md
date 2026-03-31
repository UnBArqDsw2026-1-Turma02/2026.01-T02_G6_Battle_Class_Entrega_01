# Perguntas para Definicao do Fluxo Ideal - Battle Class

> Contexto: A ideia original propunha batalhas PvP em tempo real com perguntas. Na reuniao, o grupo decidiu por um modelo de **duas fases**: responder perguntas para ganhar moedas, e depois jogar um tower defense. As perguntas abaixo buscam alinhar o fluxo completo.

---

## 1. Fase de Perguntas (Estudo)

1.1. O jogador responde perguntas **sozinho** (single-player) ou ainda existe algum componente multiplayer/competitivo nessa fase? 
Acredito que não, pensando que single player é suficiente, e a gente possa gastar mais energia em outras features do desenvolvimento.

1.2. As perguntas sao organizadas por **prova/disciplina** (ex: ENEM Matematica) ou o jogador escolhe livremente?
Poderia ser personalizado, por exemplo, ou só uma banca, ou selecionar as bancas, ou tudo misturado.

1.3. Existe um **limite de perguntas por sessao**? (ex: 10 perguntas por rodada, ou joga ate cansar?)
Poderia ser entre 5 a 15, e talvez o usuário possa personalizar a quantidade que ele deseja.

1.4. A recompensa em moedas depende de que? Apenas acerto? Tambem velocidade? Combo/streak de acertos consecutivos?
Acredito que apenas acerto e streak consecutivos, visto que o tema é algo delicado para a gente trabalhar.

1.5. Existe um **tempo limite por pergunta** ou o jogador responde no seu ritmo?
Poderia ser personalizado, pensando que o usuário possa querer alternar o "modo"

1.6. Apos errar, o jogador **ve a resposta correta / explicacao**, ou apenas segue em frente?
Poderia ser apenas o erro, e ele tenha a liberdade de pesquisar a resposta na internet.

---

## 2. Economia de Moedas

2.1. As moedas servem **apenas** para o tower defense (comprar torres, upgrades) ou tambem para cosmeticos/perfil?
Apenas no tower defense

2.2. Existe um **limite de moedas que se pode acumular** antes de jogar o tower defense?
Podemos colocar um limite.

2.3. As moedas sao **gastas permanentemente** no tower defense (a cada partida voce usa e perde), ou sao persistentes?
Apenas na partida

2.4. Existe alguma outra forma de ganhar moedas alem de responder perguntas? (ex: login diario, missoes)
Seria interessante o login diário.

---

## 3. Fase de Tower Defense

3.1. O tower defense eh **PvP** (jogador vs jogador, cada um com suas torres) ou **PvE** (jogador vs ondas de inimigos controlados pelo sistema)?
Pve

3.2. Se for PvP: eh em **tempo real simultaneo** (ambos jogam ao mesmo tempo) ou **assincrono** (voce ataca a base do outro que ja foi montada)?

3.3. As moedas ganhas nas perguntas sao usadas **dentro da partida** para comprar/posicionar torres? Ou sao usadas **antes** para montar um deck/loadout?
Anter

3.4. Quanto tempo dura uma partida de tower defense em media? (1-2 min? 5 min? 10+ min?)
1 a 3

3.5. O tower defense tem **tematica educacional** (ex: torres com nomes de disciplinas, inimigos representando "ignorancia") ou eh tematica separada?
Acredito que a temática pode ser separada

3.6. Inspiracao principal eh **Bloons TD 6** (referencia na ata). Quais elementos do BTD6 voces querem manter? (mapa fixo, tipos de torre variados, upgrades em arvore, ondas progressivas?)
Estilo dos mapas, ondas progressivas e tipos de torres variadas

3.7. Existe **matchmaking por nivel/elo** ou qualquer jogador joga contra qualquer um?
Pode ser qualquer um contra qualquer um 

---

## 4. Loop Geral e Progressao

4.1. O loop ideal seria: **Estudar → Ganhar moedas → Jogar TD → Repetir**. Existe algo mais nesse ciclo? (ex: abrir novos mapas, desbloquear torres?)
Talvez usar as moedas para liberar níveis antes, e na partida voce consegue upar até o nível que voce liberou

4.2. Existe um **sistema de nivel/XP do jogador** alem das moedas? O que ele desbloqueia?
Acho que apenas moedas

4.3. Existe **ranking/leaderboard**? Se sim, eh baseado em performance no TD, nas perguntas, ou ambos?
Ranking baseado nas perguntas

4.4. Existem **temporadas** ou a progressao eh continua?
Progressao contínua

4.5. Existem **conquistas/achievements**? (ex: "Acertou 50 questoes de matematica", "Venceu 10 partidas de TD")
Não

---

## 5. Escopo do MVP (disciplina)

5.1. Para o MVP da disciplina, quais funcionalidades sao **essenciais** vs "legal ter depois"?
   - [x] Login/cadastro
   - [x] Responder perguntas (qual area?)
   - [x] Ganhar moedas
   - [x] Tower defense basico funcional
   - [PvE] PvP ou apenas PvE?
   - [x] Ranking
   - [ ] Perfil com estatisticas
   - [ ] Painel admin para questoes

5.2. Para o MVP, o tower defense pode ser **simplificado** (ex: menos tipos de torre, mapa unico)? Qual o nivel minimo aceitavel?
Acho que podemos usar um tipo de mapa apenas para focar nessa animação única, devido a limitações técnicas nessa parte
---


