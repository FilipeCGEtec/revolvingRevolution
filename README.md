# Reolving Revolution

<img src="https://i.ytimg.com/vi/UWnE9sCJEgw/maxresdefault.jpg">
Oque é o projeto?
Este projeto feito na linguagem de C# é um jogo feito com base nas músicas "Providence" e "give and Take" da banda Poor Man's Poison.

# Tecnologias-usadas
C#

# Estado
Em progresso

Processo de desenvolvimento

# Documentação:

## Casos de Uso:

  <img src="imagens/cdu.png">
  <img src="imagens/dcdu.png">
  
## UML:

  <img src="imagens/uml.png">
  
  ### Definições das classes:
  
  #### Jogador
  
| Métodos  | Definição |
| ------------- | ------------- |
| Morrer()  | Método que apaga o jogador da tela da tela e notifica o jogo para terminar - ativado se passar do limite do perseguidor ou de tempo  |
| Andar()  | Método que move o personagem pelo aixo X  |
| AtacarVitima() | Método que leva a uma Vitima a perecer |

  #### Jogo
  
| Métodos  | Definição |
| ------------- | ------------- |
| IniciarTemporizador()  | Define um temporizador de 1 minuto  |
| PararTemporizador()  | Reinicia e desativa o temporizador |
| SairDoJogo() | Finaliza a execução do jogo |

  #### Fase
  
| Métodos  | Definição |
| ------------- | ------------- |
| FinalizarFase()  | Termina a fase  |
| PassarDeFase(pontos)  | Termina a fase e a marca como concluida |
| SairDaFase() | finaliza a execução da fase |

  #### Vitimas
  
| Métodos  | Definição |
| ------------- | ------------- |
| DefinirExistencia()  | Verifica se esta classe existe na fase |
| Girar()  | Rotaciona no eixo X |
| Marcar() | Ganha a definição de "Marcado" |
| Perecer() | Destroi o corpo |
| AcharJogador() | verifica a posição do jogador |

| Métodos  | Definição |
| ------------- | ------------- |
| DefinirExistencia()  | Verifica se esta classe existe na fase |
| REdefinirNumero() | Retorna um novo valor de angulo limite |

  #### Alma
  
| Métodos  | Definição |
| ------------- | ------------- |
| GerarAlma()  | Gera uma alma na posição de uma vitima que tenha perecido |
| ColetarAlma()  | Verifica se à  contato com o jogador e retira a alma da tela  |
| GerarPontuacao()  | Retorna uma pontuacao quando coletada |

