# 1.2 Léxico do Sistema — BattleClass

## 1. Introdução

O presente léxico tem como objetivo padronizar os termos utilizados no sistema _BattleClass_, garantindo consistência semântica entre os artefatos do projeto e facilitando a comunicação entre os membros da equipe.

O sistema combina elementos de **quizzes educacionais** com **gamificação**, o que introduz termos de diferentes domínios (educacional, sistema e jogo), justificando a necessidade de um léxico estruturado.

---

## 2. Estrutura do Léxico

Cada termo é descrito com os seguintes atributos:

- **Nome**
- **Tipo (Ator, Conceito, Objeto, Processo)**
- **Descrição**
- **Impacto no Sistema**
- **Relacionamentos**

---

## 3. Léxico do Sistema

### 3.1 Atores

| Nome                | Tipo | Descrição                           | Impacto no Sistema                    | Relacionamentos                              |
| ------------------- | ---- | ----------------------------------- | ------------------------------------- | -------------------------------------------- |
| Usuário             | Ator | Indivíduo que utiliza o sistema     | Interage com todas as funcionalidades | Pode ser visitante ou autenticado            |
| Usuário Visitante   | Ator | Usuário que acessa sem autenticação | Acesso limitado às funcionalidades    | Não salva progresso; não cria quizzes        |
| Usuário Autenticado | Ator | Usuário com login ativo             | Acesso completo ao sistema            | Pode criar quizzes, acessar ranking completo |

---

### 3.2 Domínio Educacional

| Nome             | Tipo     | Descrição                                 | Impacto no Sistema           | Relacionamentos      |
| ---------------- | -------- | ----------------------------------------- | ---------------------------- | -------------------- |
| Quiz             | Conceito | Conjunto de perguntas de múltipla escolha | Elemento central do sistema  | Contém perguntas     |
| Pergunta         | Objeto   | Enunciado apresentado ao usuário          | Avalia conhecimento          | Possui alternativas  |
| Alternativa      | Objeto   | Opções de resposta de uma pergunta        | Permite interação do usuário | Uma é a correta      |
| Resposta Correta | Conceito | Alternativa considerada correta           | Gera pontuação               | Associada à pergunta |
| Sessão de Quiz   | Processo | Execução de um quiz por um usuário        | Gera resultados e feedback   | Contém perguntas     |

---

### 3.3 Domínio de Gamificação

| Nome           | Tipo     | Descrição                               | Impacto no Sistema             | Relacionamentos          |
| -------------- | -------- | --------------------------------------- | ------------------------------ | ------------------------ |
| Pontuação      | Conceito | Valor acumulado com base no desempenho  | Mede desempenho do usuário     | Influencia ranking       |
| Moedas (Lumes) | Conceito | Recurso virtual obtido por acertos      | Incentiva engajamento          | Derivado da pontuação    |
| Gamificação    | Conceito | Uso de elementos de jogo                | Aumenta retenção e engajamento | Relacionada à progressão |
| Batalha        | Conceito | Elemento de jogo associado ao progresso | Representa avanço no sistema   | Relacionada à pontuação  |
| Progressão     | Conceito | Evolução do usuário ao longo do uso     | Mantém engajamento             | Baseada em desempenho    |

---

### 3.4 Domínio do Sistema

| Nome                    | Tipo     | Descrição                           | Impacto no Sistema     | Relacionamentos               |
| ----------------------- | -------- | ----------------------------------- | ---------------------- | ----------------------------- |
| Login                   | Processo | Autenticação do usuário             | Libera acesso completo | Necessário para persistência  |
| Cadastro                | Processo | Criação de conta no sistema         | Permite autenticação   | Relacionado ao login          |
| Ranking                 | Conceito | Classificação dos usuários          | Incentiva competição   | Baseado na pontuação          |
| Feedback                | Processo | Retorno ao usuário após resposta    | Auxilia aprendizado    | Ocorre após cada pergunta     |
| Funcionalidade Limitada | Conceito | Restrições para usuários visitantes | Incentiva cadastro     | Afeta usuário visitante       |
| Interface do Usuário    | Conceito | Camada visual do sistema            | Permite interação      | Relacionada a todos os fluxos |

---

## 4. Regras de Negócio

| Regra                  | Descrição                                                                                             |
| ---------------------- | ----------------------------------------------------------------------------------------------------- |
| Restrição de Visitante | Usuários não autenticados não salvam progresso, não criam quizzes e possuem acesso parcial ao ranking |
| Pontuação              | Cada resposta correta gera pontos                                                                     |
| Recompensa             | Pontuação acumulada gera moedas (lumes)                                                               |

---

## 5. Relações entre Termos

- Usuário → realiza → Sessão de Quiz
- Quiz → contém → Perguntas
- Pergunta → possui → Alternativas
- Sessão de Quiz → gera → Pontuação
- Pontuação → gera → Moedas (Lumes)
- Usuário → aparece → Ranking
- Usuário Visitante → possui → Funcionalidade Limitada

---

## 6. Observações de Domínio

- O sistema integra dois domínios principais:
- Educacional (quizzes)
- Gamificação (elementos de jogo)

- A separação entre **criação de conteúdo** e **consumo do quiz** deve ser mantida

- A limitação de usuários visitantes é uma decisão estratégica para incentivar autenticação

---

## 7. Versionamento e Participação

| Autor          | Contribuição                                                                                                                                |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Gabriela Tiago | Elaboração do Léxico completo do sistema, incluindo definição de termos, organização por domínios e estabelecimento de relações conceituais |

---

## 8. Referências

- SOMMERVILLE, Ian. Engenharia de Software
- PRESSMAN, Roger. Engenharia de Software
- Materiais da disciplina de Arquitetura e Desenho de Software (UnB)
