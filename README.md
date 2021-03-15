# Comandos-Basicos-Robots-OpenComputers
Uma pequena lista com os comandos básicos dos Robots do OpenComputers Minecraft mod

# Comandos Robots:

|        Comando        | Explicação                                                                     | Observação                                                                                                                                        |
|:---------------------:|--------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| robot.swing(n)        | Quebra o bloco (função do mouse esquerdo)                                      | "n" sendo o número de vezes que o comando será executado Caso não haja parâmetro o comando será execuldado uma vez                                |
| robot.use()           | Usa o que estiver em sua mão ou um bloco interativo (função do mouse esquerdo) |                                                                                                                                                   |
| robot.select(n)       | Seleciona um dos slots do inventário demarcando-o                              | "n" sendo o número do slot                                                                                                                        |
| robot.place**LADO**() | Usa o item que está demarcado no inventário                                    | Troque **LADO** por right/left/up/down Caso não haja **LADO** o intem será usando à frente                                                        |
| robot.drop**LADO**()  | "Dropa" o item demarcado no inventário                                         | Troque **LADO** por right/left/up/down Caso não haja **LADO** o intem será dropado no inventário à frente                                         |
| robot.suck**LADO**()  | Retira um item do inventário no **LADO** para o seu lugar demarcado            | Troque **LADO** por right/left/up/down Caso não haja **LADO** o inventário padrão será à frente                                                   |
| robot.turn**LADO**(n) | Manda o lado que o robô deve olhar                                             | Troque **LADO** por right/left "n" sendo o número de vezes que o comando será executado Caso não haja parâmetro o comando será execuldado uma vez |
| robot.**LADO**(n)     | Manda o robô subir ou descer                                                   | Troque **LADO** por up/down "n" sendo o número de vezes que o comando será executado Caso não haja parâmetro o comando será execuldado uma vez    |
| robot.forward(n)      | Manda o robô andar um bloco para frente n vezes                                | "n" sendo o número de vezes que o comando será executado Caso não haja parâmetro o comando será execuldado uma vez                                |