# # Comparador de Cartas de Cidades

Este é um programa em C que permite comparar atributos entre duas cartas de cidades para determinar qual é a melhor. Ele utiliza categorias como população, área, PIB, densidade populacional e número de pontos turísticos.

## 🛠️ Como compilar o programa
1. Certifique-se de que você tem um compilador C (ex: GCC).
2. Para compilar o programa, execute o seguinte comando no terminal:
   ```bash
   gcc -o comparador cartas_cidades.c

   Para rodar o programa, execute:
bash
./comparador

📋 Instruções de uso
Digite os dados para duas cartas de cidades.

Escolha dois atributos diferentes para comparar.

O programa exibirá os resultados da comparação para cada atributo, somará os valores e determinará a carta vencedora.

📖 Exemplo de uso
Entrada de dados:
Ao iniciar, o programa pedirá para você inserir os dados das duas cartas. Exemplo:
Digite os dados da primeira carta:
Estado (letra de 'A' a 'H'): A
Código da carta (ex: A01): A01
Nome da cidade: São_Paulo
População: 12000000
Área da cidade (em km²): 1500
PIB: 700000000
Número de pontos turísticos: 15

Menus interativos:
Após entrar com os dados, você verá um menu assim:
Escolha dois atributos para a comparação:
1: População
2: Área
3: PIB
4: Densidade Demográfica
5: Número de Pontos Turísticos

Escolha dois atributos diferentes, como "1" (População) e "3" (PIB). O programa exibirá os resultados da comparação.

Resultado exibido:
Após a comparação, o programa mostrará:

O valor dos atributos para cada carta.

A soma dos dois atributos para cada carta.

O vencedor baseado na soma total.

Exemplo de resultado:
Comparação dos atributos escolhidos:
Atributo 1 (População):
Valor da Carta 1: 12000000
Valor da Carta 2: 6700000
São_Paulo venceu pelo maior valor no atributo 1.

Atributo 2 (PIB):
Valor da Carta 1: 700000000
Valor da Carta 2: 400000000
São_Paulo venceu pelo maior valor no atributo 2.

Soma dos atributos:
Carta 1: 707000000
Carta 2: 406700000
A Carta 1 vence pela maior soma dos atributos!

🏆 Atributos disponíveis para comparação
População

Área (km²)

PIB (em R$)

Densidade Demográfica (habitantes/km²)

Número de Pontos Turísticos

💡 Dicas
Certifique-se de digitar valores válidos ao preencher os dados das cartas.

Escolha atributos diferentes no menu interativo.

🤝 Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

📜 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

