# Requisitos Funcionais e Não Funcionais para "To Do List"

## 1. Requisitos Funcionais

A Tabela 1 a seguir contém os Requisitos Funcionais (RF) elicitados utilizando a técnica de Brainstorm.

| ID   | Requisito                                                                                  | Prioridade | Requisitos Relacionados |
| :--: | :----------------------------------------------------------------------------------------: | :--------: | :----------------------: |
| RF01 | O usuário deve poder adicionar uma nova tarefa.                                            | Alta       | -                       |
| RF02 | O usuário deve poder editar uma tarefa existente.                                          | Alta       | RF01                    |
| RF03 | O usuário deve poder excluir uma tarefa.                                                   | Alta       | RF01                    |
| RF04 | O usuário deve poder marcar uma tarefa como concluída.                                     | Média      | RF01, RF03              |
| RF05 | O usuário deve poder visualizar todas as tarefas em uma lista.                             | Alta       | -                       |
| RF06 | O usuário deve poder filtrar as tarefas por status (concluídas, pendentes).                | Média      | RF04, RF05              |
| RF07 | O usuário deve poder atribuir uma data de vencimento para cada tarefa.                     | Média      | RF01                    |
| RF08 | O usuário deve poder visualizar as tarefas em ordem de prioridade ou data de vencimento.   | Baixa      | RF07                    |
| RF09 | O usuário deve poder categorizar as tarefas por etiquetas (trabalho, pessoal, etc.).       | Baixa      | RF01                    |
| RF10 | O usuário deve poder receber notificações de lembrete para tarefas com data de vencimento. | Média      | RF07                    |

<p align="center">Tabela 1: Requisitos Funcionais</p>

---

## 2. Requisitos Não Funcionais

A Tabela 2 a seguir contém os Requisitos Não Funcionais (RNF) do sistema.

| ID    | Requisito                                                               | Prioridade | Descrição                                                                                         |
| :---: | :----------------------------------------------------------------------:| :--------: | :------------------------------------------------------------------------------------------------ |
| RNF01 | Disponibilidade                                                          | Alta       | O sistema deve estar disponível 99% do tempo.                                                     |
| RNF02 | Desempenho                                                               | Alta       | O tempo de resposta para carregar ou atualizar a lista de tarefas deve ser inferior a 2 segundos. |
| RNF03 | Usabilidade                                                              | Alta       | O sistema deve ser fácil de usar, com uma interface intuitiva.                                    |
| RNF04 | Compatibilidade                                                          | Média      | O sistema deve funcionar em dispositivos móveis e desktops.                                       |
| RNF05 | Segurança                                                                | Alta       | Os dados do usuário devem estar protegidos e criptografados.                                      |
| RNF06 | Escalabilidade                                                           | Baixa      | O sistema deve suportar o crescimento de usuários e dados sem perda de desempenho.               |
| RNF07 | Portabilidade                                                            | Média      | O sistema deve ser acessível por meio de navegadores populares (Chrome, Firefox, Safari).         |
| RNF08 | Manutenibilidade                                                         | Média      | O sistema deve ser fácil de atualizar e corrigir erros.                                          |

<p align="center">Tabela 2: Requisitos Não Funcionais</p>


# 2. Referências


<a href="../README.md">VOLTAR INÍCIO</a>
