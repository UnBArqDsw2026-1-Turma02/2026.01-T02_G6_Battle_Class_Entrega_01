# Perguntas para Definicao do Fluxo Ideal - Battle Class

> Contexto: A ideia original propunha batalhas PvP em tempo real com perguntas. Na reuniao, o grupo decidiu por um modelo de **duas fases**: responder perguntas para ganhar moedas, e depois jogar um tower defense. As perguntas abaixo buscam alinhar o fluxo completo.

---

## 1. Fase de Perguntas (Estudo)

1.1. O jogador responde perguntas **sozinho** (single-player) ou ainda existe algum componente multiplayer/competitivo nessa fase?

Resposta: O jogador responde perguntas sozinho

1.2. As perguntas sao organizadas por **prova/disciplina** (ex: ENEM Matematica) ou o jogador escolhe livremente?

As perguntas são organizadas por prova e quando seleciona a prova é mostrado uma roleta em que o usuário gira para ver qual a matéria dentro da prova que a questão vai ser. Quando a questão é mostrada, também é mostrado a quantidade de moedas que essa pergunta vale, (questões mais difíceis valem mais) e quando ela vai redizindo o valor (quanto mais tempo passa, até um limite de 5 minutos, a questão perde valor, valorizando usuários que respondem mais rápidas)

1.3. Existe um **limite de perguntas por sessao**? (ex: 10 perguntas por rodada, ou joga ate cansar?)

O jogador pode jogar até cansar

1.4. A recompensa em moedas depende de que? Apenas acerto? Tambem velocidade? Combo/streak de acertos consecutivos?

Respondido em 1.2

1.5. Existe um **tempo limite por pergunta** ou o jogador responde no seu ritmo?

O jogador responde no seu ritmo

1.6. Apos errar, o jogador **ve a resposta correta / explicacao**, ou apenas segue em frente?

Ele vê a resposta certa e explicação

---

## 2. Economia de Moedas

2.1. As moedas servem **apenas** para o tower defense (comprar torres, upgrades) ou tambem para cosmeticos/perfil?

Servem também para cosméticos e perfil

2.2. Existe um **limite de moedas que se pode acumular** antes de jogar o tower defense?

existe um limite por nível do tower defense

2.3. As moedas sao **gastas permanentemente** no tower defense (a cada partida voce usa e perde), ou sao persistentes?

As moedas que se usa no tower defense são gastas permanentemente

2.4. Existe alguma outra forma de ganhar moedas alem de responder perguntas? (ex: login diario, missoes)

Inicialmente não

---

## 3. Fase de Tower Defense

3.1. O tower defense eh **PvP** (jogador vs jogador, cada um com suas torres) ou **PvE** (jogador vs ondas de inimigos controlados pelo sistema)?

O tower defense é PvE inicialmente

3.2. Se for PvP: eh em **tempo real simultaneo** (ambos jogam ao mesmo tempo) ou **assincrono** (voce ataca a base do outro que ja foi montada)?

Ideia interessante deixar assíncrono

3.3. As moedas ganhas nas perguntas sao usadas **dentro da partida** para comprar/posicionar torres? Ou sao usadas **antes** para montar um deck/loadout?

As moedas ganhas podem ser usadas dentro da partida para ganhar powerups ou usar torres especiais. Moedas também podem ser usadas para evoluir "heróis" como em clash of clans

3.4. Quanto tempo dura uma partida de tower defense em media? (1-2 min? 5 min? 10+ min?)

Acho que podem ter níveis com durações diferentes, mas em média 5 min

3.5. O tower defense tem **tematica educacional** (ex: torres com nomes de disciplinas, inimigos representando "ignorancia") ou eh tematica separada?

Temática separada

3.6. Inspiracao principal eh **Bloons TD 6** (referencia na ata). Quais elementos do BTD6 voces querem manter? (mapa fixo, tipos de torre variados, upgrades em arvore, ondas progressivas?)

Mapa fixo, tipos de torre variados, upgrades em árvore e ondas progressivas. O usuário tem dois tipos de moedas, as moedas das questões, usados para torres especiais e upgrade delas e powerups (como aumentar a velocidade de ataque de uma torre durante X tempo e etc) e moedas dentro da partida, usadas para melhorar as torres comuns

3.7. Existe **matchmaking por nivel/elo** ou qualquer jogador joga contra qualquer um?

Por enquanto não, pois será apenas contra o computador
---

## 4. Loop Geral e Progressao

4.1. O loop ideal seria: **Estudar → Ganhar moedas → Jogar TD → Repetir**. Existe algo mais nesse ciclo? (ex: abrir novos mapas, desbloquear torres?)

Inicialmente não

4.2. Existe um **sistema de nivel/XP do jogador** alem das moedas? O que ele desbloqueia?

Inicialment enão

4.3. Existe **ranking/leaderboard**? Se sim, eh baseado em performance no TD, nas perguntas, ou ambos?

Inicialmente, apenas um ranking baseado nas perguntas respondidas (cada moeda ganha por responder a pergunta é um ponto -> perguntas mais difíceis valem mais e etc).

4.4. Existem **temporadas** ou a progressao eh continua?

A progressão é contínua

4.5. Existem **conquistas/achievements**? (ex: "Acertou 50 questoes de matematica", "Venceu 10 partidas de TD")

Inicialmente não

---

## 5. Escopo do MVP (disciplina)

5.1. Para o MVP da disciplina, quais funcionalidades sao **essenciais** vs "legal ter depois"?
   - [X] Login/cadastro
   - [X] Responder perguntas (qual area?)
   - [X] Ganhar moedas
   - [X] Tower defense basico funcional
   - [X] PvP ou apenas PvE? -> PvE
   - [X] Ranking -> Apenas das questões
   - [X] Perfil com estatisticas
   - [X] Painel admin para questoes

5.2. Para o MVP, o tower defense pode ser **simplificado** (ex: menos tipos de torre, mapa unico)? Qual o nivel minimo aceitavel?

Menos tipos de torres. inicialmente 3 mapas com dificuldades diferentes

5.3. O banco de questoes inicial vem de onde? Questoes criadas pelo grupo? Importadas de provas reais?

Criadas por IA

---

---

