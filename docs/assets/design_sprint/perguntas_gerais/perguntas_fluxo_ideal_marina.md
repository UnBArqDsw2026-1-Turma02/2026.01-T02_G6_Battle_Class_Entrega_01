# Perguntas para Definicao do Fluxo Ideal - Battle Class

> Contexto: A ideia original propunha batalhas PvP em tempo real com perguntas. Na reuniao, o grupo decidiu por um modelo de **duas fases**: responder perguntas para ganhar moedas, e depois jogar um tower defense. As perguntas abaixo buscam alinhar o fluxo completo.

---

## 1. Fase de Perguntas (Estudo)

1.1. O jogador responde perguntas **sozinho** (single-player) ou ainda existe algum componente multiplayer/competitivo nessa fase?

Acredito que dentro do escopo que entregaremos na disciplina, melhor manter sozinho. Futuramente poderia ser adicionado como um modo de jogo.

1.2. As perguntas sao organizadas por **prova/disciplina** (ex: ENEM Matematica) ou o jogador escolhe livremente?

Eu colocaria organizada por concurso/vestibular...

1.3. Existe um **limite de perguntas por sessao**? (ex: 10 perguntas por rodada, ou joga ate cansar?)

Colcoaria com limite sim, mas podemso considerar fazer sem limite como um modo de jogo

1.4. A recompensa em moedas depende de que? Apenas acerto? Tambem velocidade? Combo/streak de acertos consecutivos?

Diria Acerto, Dificuldade, Velocidade

1.5. Existe um **tempo limite por pergunta** ou o jogador responde no seu ritmo?

Colcoaria sem limite de tempo, mas podemso considerar fazer com limite de tempo como um modo de jogo, para as pessoas poderem testar o tempo delas de resposta

1.6. Apos errar, o jogador **ve a resposta correta / explicacao**, ou apenas segue em frente?

Acho isso bem importante

---

## 2. Economia de Moedas

2.1. As moedas servem **apenas** para o tower defense (comprar torres, upgrades) ou tambem para cosmeticos/perfil?

Apenas tower defense

2.2. Existe um **limite de moedas que se pode acumular** antes de jogar o tower defense?

Não vejo porquê

2.3. As moedas sao **gastas permanentemente** no tower defense (a cada partida voce usa e perde), ou sao persistentes?

Gasta permanentemente

2.4. Existe alguma outra forma de ganhar moedas alem de responder perguntas? (ex: login diario, missoes)

A prinícpio não, só colocaria se fossemos adicionar outros modos de jogo

---

## 3. Fase de Tower Defense

3.1. O tower defense eh **PvP** (jogador vs jogador, cada um com suas torres) ou **PvE** (jogador vs ondas de inimigos controlados pelo sistema)?

PvE

3.2. Se for PvP: eh em **tempo real simultaneo** (ambos jogam ao mesmo tempo) ou **assincrono** (voce ataca a base do outro que ja foi montada)?

(colocaria como um opção de jogo, mas fora do escopo da disciplina)

3.3. As moedas ganhas nas perguntas sao usadas **dentro da partida** para comprar/posicionar torres? Ou sao usadas **antes** para montar um deck/loadout?

Eu acho que é mais justo antes

3.4. Quanto tempo dura uma partida de tower defense em media? (1-2 min? 5 min? 10+ min?)

No mín 3:00 no máx 5:00

3.5. O tower defense tem **tematica educacional** (ex: torres com nomes de disciplinas, inimigos representando "ignorancia") ou eh tematica separada?

Acho legal mantermos a temática 

3.6. Inspiracao principal eh **Bloons TD 6** (referencia na ata). Quais elementos do BTD6 voces querem manter? (mapa fixo, tipos de torre variados, upgrades em arvore, ondas progressivas?)

Sei pouco sobre o jogo para opinar sobre isso.

3.7. Existe **matchmaking por nivel/elo** ou qualquer jogador joga contra qualquer um?

Acho que existem níveis diferentes de rodada, rodadas masi difíceis, rodadas masi fáceis. E cada uma que o jogador gnaha, ele passa pra próxima. Sendo PvP, mudaria o formato

---

## 4. Loop Geral e Progressao

4.1. O loop ideal seria: **Estudar → Ganhar moedas → Jogar TD → Repetir**. Existe algo mais nesse ciclo? (ex: abrir novos mapas, desbloquear torres?)

A princípio, faria apenas assim. Depois, fora do escopo da disciplina, poderia ser adicionado mais

4.2. Existe um **sistema de nivel/XP do jogador** alem das moedas? O que ele desbloqueia?

Acho que não, pelo menos no começo

4.3. Existe **ranking/leaderboard**? Se sim, eh baseado em performance no TD, nas perguntas, ou ambos?

Podemos ter mais de um, quem ganha mais batalha, quem ganhou mais moedas, quem acertou mias questões

4.4. Existem **temporadas** ou a progressao eh continua?

Acho que continuo

4.5. Existem **conquistas/achievements**? (ex: "Acertou 50 questoes de matematica", "Venceu 10 partidas de TD")

Gosto bastante da ideia.

---

## 5. Escopo do MVP (disciplina)

5.1. Para o MVP da disciplina, quais funcionalidades sao **essenciais** vs "legal ter depois"?
   - [X] Login/cadastro
   - [X] Responder perguntas (qual area?)
   - [X] Ganhar moedas
   - [X] Tower defense basico funcional
   - [X] PvP ou apenas PvE?
   - [X] Ranking
   - [X] Perfil com estatisticas
   - [X] Painel admin para questoes

5.2. Para o MVP, o tower defense pode ser **simplificado** (ex: menos tipos de torre, mapa unico)? Qual o nivel minimo aceitavel?

Acredito qeu sim, importante simplificar, o nível mínimo eu diria que seria ter 3 mapas, e ao menos 5 tipos de "defesa com 3 atualizações cada

---


