# Perguntas para Definição do Fluxo Ideal - Battle Class

> Contexto: A ideia original propunha batalhas PvP em tempo real com perguntas. Na reunião, o grupo decidiu por um modelo de **duas fases**: responder perguntas para ganhar moedas, e depois jogar um tower defense. As perguntas abaixo buscam alinhar o fluxo completo.

---

## 1. Fase de Perguntas (Estudo)

1.1. O jogador responde perguntas **sozinho** (single-player) ou ainda existe algum componente multiplayer/competitivo nessa fase? 
O foco deve ser totalmente single-player. Isso elimina a complexidade técnica de sincronizar jogadores em tempo real e nos permite direcionar os esforços de desenvolvimento para as mecânicas principais.

1.2. As perguntas são organizadas por **prova/disciplina** (ex: ENEM Matemática) ou o jogador escolhe livremente?
A flexibilidade é o ideal. O jogador pode montar seu próprio filtro, escolhendo bancas específicas, matérias separadas ou até gerando um simulado misto.

1.3. Existe um **limite de perguntas por sessão**? (ex: 10 perguntas por rodada, ou joga até cansar?)
Sessões curtas e configuráveis. Algo entre 5 e 15 questões, onde o próprio usuário define o tamanho do bloco que quer responder.

1.4. A recompensa em moedas depende de quê? Apenas acerto? Também velocidade? Combo/streak de acertos consecutivos?
Vamos focar apenas em acertos e multiplicadores de sequência (streaks). Colocar pressão de tempo para responder pode gerar frustração, já que o estudo em si já é um tema delicado.

1.5. Existe um **tempo limite por pergunta** ou o jogador responde no seu ritmo?
O usuário deve ditar o ritmo. Podemos deixar isso como uma configuração, permitindo que ele alterne o modo de jogo caso queira treinar sob pressão.

1.6. Após errar, o jogador **vê a resposta correta / explicação**, ou apenas segue em frente?
A plataforma apenas acusa o erro. Se o jogador quiser entender o motivo, ele tem a autonomia para pesquisar a resolução na internet.

---

## 2. Economia de Moedas

2.1. As moedas servem **apenas** para o tower defense (comprar torres, upgrades) ou também para cosméticos/perfil?
Uso exclusivo para as mecânicas do tower defense.

2.2. Existe um **limite de moedas que se pode acumular** antes de jogar o tower defense?
Sim, impor um "cap" (limite máximo) é uma boa estratégia para forçar o jogador a gastar e transicionar para a fase do jogo.

2.3. As moedas são **gastas permanentemente** no tower defense (a cada partida você usa e perde), ou são persistentes?
Elas são consumíveis. O que for gasto durante aquela partida do TD é consumido permanentemente.

2.4. Existe alguma outra forma de ganhar moedas além de responder perguntas? (ex: login diário, missões)
Implementar bônus de login diário seria excelente para a retenção de usuários.

---

## 3. Fase de Tower Defense

3.1. O tower defense é **PvP** (jogador vs jogador, cada um com suas torres) ou **PvE** (jogador vs ondas de inimigos controlados pelo sistema)?
Foco 100% em PvE.

3.2. Se for PvP: é em **tempo real simultâneo** (ambos jogam ao mesmo tempo) ou **assíncrono** (você ataca a base do outro que já foi montada)?
(Não se aplica, já que definimos como PvE).

3.3. As moedas ganhas nas perguntas são usadas **dentro da partida** para comprar/posicionar torres? Ou são usadas **antes** para montar um deck/loadout?
O gasto principal acontece antes, na preparação e montagem da estratégia/deck.

3.4. Quanto tempo dura uma partida de tower defense em média? (1-2 min? 5 min? 10+ min?)
Partidas bem dinâmicas, com duração média de 1 a 3 minutos.

3.5. O tower defense tem **temática educacional** (ex: torres com nomes de disciplinas, inimigos representando "ignorância") ou é temática separada?
A temática do TD pode ser totalmente separada e independente do contexto educacional.

3.6. Inspiração principal é **Bloons TD 6** (referência na ata). Quais elementos do BTD6 vocês querem manter? (mapa fixo, tipos de torre variados, upgrades em árvore, ondas progressivas?)
Queremos resgatar o design dos mapas, a variedade de funções de cada torre e o sistema de ondas (waves) progressivas.

3.7. Existe **matchmaking por nível/elo** ou qualquer jogador joga contra qualquer um?
Como é PvE, não há restrições complexas de matchmaking. Qualquer um pode jogar de forma livre.

---

## 4. Loop Geral e Progressão

4.1. O loop ideal seria: **Estudar → Ganhar moedas → Jogar TD → Repetir**. Existe algo mais nesse ciclo? (ex: abrir novos mapas, desbloquear torres?)
O ciclo é esse. As moedas servem para "desbloquear" o nível máximo que uma torre pode alcançar no menu. Durante a partida, você só consegue evoluir aquela torre até o nível que já foi liberado previamente com as moedas.

4.2. Existe um **sistema de nível/XP do jogador** além das moedas? O que ele desbloqueia?
Vamos manter o sistema simples focado apenas nas moedas, sem XP de jogador.

4.3. Existe **ranking/leaderboard**? Se sim, é baseado em performance no TD, nas perguntas, ou ambos?
Ranking baseado puramente no desempenho dos estudos (acertos na fase de perguntas).

4.4. Existem **temporadas** ou a progressão é contínua?
A progressão será contínua.

4.5. Existem **conquistas/achievements**? (ex: "Acertou 50 questões de matemática", "Venceu 10 partidas de TD")
Não teremos sistema de conquistas no momento.

---

## 5. Escopo do MVP (disciplina)

5.1. Para o MVP da disciplina, quais funcionalidades são **essenciais** vs "legal ter depois"?
Concordo com a lista atual:
   - [x] Login/cadastro
   - [x] Responder perguntas 
   - [x] Ganhar moedas
   - [x] Tower defense básico funcional
   - [x] PvE 
   - [x] Ranking
   - [ ] Perfil com estatísticas (Fica para depois)
   - [ ] Painel admin para questões (Fica para depois)

5.2. Para o MVP, o tower defense pode ser **simplificado** (ex: menos tipos de torre, mapa único)? Qual o nível mínimo aceitável?
Ter apenas um mapa já é o suficiente. Considerando nossas restrições técnicas, é mais inteligente ter um único mapa bem polido e com boas animações do que tentar abraçar um escopo maior.