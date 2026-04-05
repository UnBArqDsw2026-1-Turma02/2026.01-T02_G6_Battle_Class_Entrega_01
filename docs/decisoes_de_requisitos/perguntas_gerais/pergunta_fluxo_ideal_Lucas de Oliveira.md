# Perguntas para Definição do Fluxo Ideal - Battle Class

> Contexto: A ideia evoluiu de batalhas PvP em tempo real para um modelo dividido em duas fases: responder perguntas para acumular moedas e, em seguida, utilizá-las em um jogo no estilo tower defense.

---

## 1. Fase de Perguntas (Estudo)

### 1.1. O jogador responde perguntas sozinho ou existe multiplayer?
Inicialmente, o foco será no modo individual, permitindo que o jogador estude no seu próprio ritmo. Como evolução, pode ser incluído um aspecto competitivo opcional, como comparação de pontuações com amigos ou participação em desafios semanais.

### 1.2. Organização das perguntas
As questões serão estruturadas por disciplinas ou provas (ex: Matemática ENEM), facilitando um estudo direcionado. Além disso, haverá um modo livre, permitindo ao jogador praticar de forma mais ampla, semelhante a um simulado.

### 1.3. Limite de perguntas por sessão
A ideia é sugerir um número padrão de questões por sessão (como 10 ou 20), ajudando a manter o foco. Ainda assim, o jogador poderá escolher encerrar quando quiser ou ajustar a quantidade de perguntas.

### 1.4. Sistema de recompensa em moedas
O ganho de moedas será baseado principalmente nos acertos. Para tornar a experiência mais dinâmica, também haverá bônus por respostas rápidas e um sistema de sequência (streak), aumentando a recompensa conforme o jogador mantém consistência.

### 1.5. Tempo limite por pergunta
Será adotado um tempo padrão por questão (por exemplo, 60 segundos), trazendo mais desafio. No entanto, haverá um modo alternativo sem limite de tempo, ideal para estudo mais tranquilo.

### 1.6. Feedback após erro
Após errar uma questão, o jogador terá acesso à resposta correta junto com uma explicação resumida. Também poderá existir um modo em que o feedback é apresentado apenas ao final da sessão, para quem preferir maior desafio.

---

## 2. Economia de Moedas

### 2.1. Uso das moedas
No MVP, as moedas serão utilizadas exclusivamente no modo tower defense. Em versões futuras, podem ser incorporados elementos adicionais, como personalizações de perfil ou itens cosméticos.

### 2.2. Limite de acúmulo de moedas
Não haverá restrição rígida de acúmulo inicialmente, permitindo que o jogador administre seus recursos livremente. Caso necessário, limites podem ser definidos posteriormente.

### 2.3. Consumo das moedas
As moedas serão consumidas a cada partida no tower defense, incentivando o jogador a retornar à fase de perguntas para continuar evoluindo.

### 2.4. Outras formas de ganhar moedas
Para simplificar o escopo inicial, a única forma de obtenção será por meio das questões. Futuramente, podem ser adicionadas mecânicas como recompensas diárias ou missões.

---

## 3. Fase de Tower Defense

### 3.1. Tipo de jogo (PvP ou PvE)
O modo inicial será PvE, com o jogador enfrentando ondas de inimigos controlados pelo sistema. Isso reduz a complexidade e facilita a implementação do MVP.

### 3.2. PvP (futuro)
Caso seja implementado posteriormente, o PvP poderá explorar tanto partidas em tempo real quanto modos assíncronos.

### 3.3. Uso das moedas no TD
As moedas serão utilizadas antes da partida para definir o conjunto de torres (loadout). Durante a partida, poderão existir recursos limitados adicionais para ajustes estratégicos.

### 3.4. Duração das partidas
As partidas terão curta duração, entre 1 e 3 minutos, garantindo uma experiência rápida e envolvente.

### 3.5. Temática do jogo
Inicialmente, será adotada uma temática neutra para facilitar o desenvolvimento. Elementos educacionais poderão ser incorporados em versões futuras.

### 3.6. Referência no Bloons TD 6
Alguns elementos inspirados incluem:
- Variedade de torres com funções distintas  
- Mapas com layouts diferentes  
- Sistema de evolução das torres  

### 3.7. Matchmaking
Não se aplica ao MVP, já que o foco é no modo PvE. Em um possível modo PvP, poderá ser considerado um sistema de pareamento por nível.

---

## 4. Loop Geral e Progressão

### 4.1. Loop principal
O ciclo central será: responder perguntas → acumular moedas → jogar tower defense → repetir. No futuro, podem ser adicionados elementos de progressão como desbloqueio de conteúdo.

### 4.2. Sistema de nível/XP
No MVP, a progressão será baseada apenas nas moedas. Um sistema de níveis pode ser introduzido posteriormente para liberar novos conteúdos.

### 4.3. Ranking
Inicialmente, o ranking será baseado no desempenho nas questões. Futuramente, pode haver rankings separados para o modo tower defense.

### 4.4. Temporadas
A progressão será contínua no início, sem divisão por temporadas.

### 4.5. Conquistas (achievements)
Não fazem parte do MVP, mas podem ser adicionadas depois para aumentar o engajamento.

---

## 5. Escopo do MVP

### 5.1. Funcionalidades essenciais
- Sistema de login e cadastro  
- Resolução de questões por disciplina  
- Sistema de moedas  
- Tower defense funcional (modo PvE)  
- Ranking baseado nas questões  
- Perfil do jogador com estatísticas  
- Painel administrativo para gerenciamento de questões  

### 5.2. Complexidade do Tower Defense
O TD será simplificado, com poucos tipos de torres (ex: 3) e um único mapa. O objetivo é garantir que a mecânica principal funcione bem, mesmo com escopo reduzido.

### 5.3. Origem das questões
Para o MVP, as questões podem ser geradas com auxílio de IA, garantindo rapidez na criação do banco inicial. Posteriormente, é possível incorporar questões reais para aumentar a qualidade do conteúdo.
