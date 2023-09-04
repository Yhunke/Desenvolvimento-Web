# Exercício - Introdução ao HTML5

Esse é um exercício de correção automática sobre o conteúdo da aula de Introdução ao HTML5 de Tecnologias Web da Faculdade Impacta de Tecnologia.

## O que fazer?

Você deve editar apenas no arquivo `ac1.html`.
Lá há quatro `<div>`s chamadas _exercicio1_, _exercicio2_, _exercicio3_ e _exercicio4_, que correspondem obviamente aos exercícios de 1 a 4.
Além dos 4 exercícios, há um JSON no começo do arquivo que também deve ser alterado (esse é o exercício 0).
Vocês não devem editar mais nada mais além disso dentro do arquivo para não quebrar os testes.

Comece pela função que fornece um JSON com o nome e o RA dos alunos (exercício 0).
Sem essa identificação feita corretamente, sua nota será zero independente de todo o resto .

Faça a AC em grupos de 1 até 5 pessoas.

## Como saber se o que fiz está certo?

O exercício funciona usando um framework de testes em JavaScript desenvolvido para a atividade.

Para executar e testar esta AC, basta abrir o arquivo `ac1.html` em um navegador moderno (Chrome, Firefox, Opera, Edge, Konqueror, Safari ou Samsung Internet), e o resultado do seu HTML já aparecerá.
Mas antes dos HTMLs dos seus exercícios, há um pequeno formulário com um botão de executar os testes.
Clique nesse botão e veja toda a mágica dos testes acontecer!

Este botão dispara a execução de um monte de testes (exatos 235, para ser mais preciso).
O relatório de testes é colocado logo após ao HTML do exercício 4.
Se houverem problemas, esses testes vão descrever o que foi que deu errado e fornecer uma dica sobre o resultado esperado.

Obviamente, o arquivo `ac1.html` dado aqui falhará em quase todos os testes e vai te dar uma nota próxima de zero.
Não só isso, já te dará de cara uma caixa de mensagem de erro amarela com letras grandes vermelhas piscando bem chamativas dizendo que você precisa configurar o JSON com os nome e os RAs dos alunos (esse é o exercício 0).

O seu objetivo é editar esse HTML de forma a fazer todos os testes passarem.
Você deverá alterar este arquivo até conseguir a nota 10 (ou até desistir de fazê-lo, mas espero que não seja o caso).
Não tem muito segredo, basta fazer EXATAMENTE o que o enunciado de cada exercício pede, nem mais e nem menos.
Se houver algum erro, os testes te dirão o que há de errado.

Se o seu script tiver algum erro grave (provavelmente JSON quebrado ou alguma lambança muito séria nas tags de `<script>`), uma caixa amarela com letras grandes vermelhas piscando vai aparecer para te avisar disso.

O último grupo de testes, que verifica se a estrutura da HTML está ok, pode depender de você ter que rodar o arquivo `getsrc.py` no Python para que ele funcione.
Para executá-lo, rode o comando `python getsrc.py` numa tela de console e deixe ele rodando lá indefinidamente enquanto você estiver trabalhando com este AC.
Talvez você também precise executar um comando `pip3 install flask` antes.

Se você estiver usando o Firefox, a execução do `getsrc.py` não é necessária.
Mas se você estiver usando o Chrome, o Edge ou o Opera.
A razão para esta diferença é que com exceção do Firefox, o navegador não permite à página acessar arquivos locais.
Logo, o script `getsrc.py` serve para contornar essa restrição nesses navegadores.
Outros navegadores diferentes desses quatro não foram testados, mas é de se esperar que tenham um comportamento semelhante ou ao firefox ou aos demais.

Ah, e obviamente, os testes só vão funcionar se você deixar as tags `<script>` que estão dentro do `<head>` intactas (a única alteração necessária é a do exercício 0).
Se você mexer nessas tags `<script>`, você corre o risco de tirar uma nota zero!

## E os demais arquivos?

Os testes estão no arquivo `ac1-teste.js`.
O código responsável por gerenciar os testes está no `lib/testefw.js` e no `lib/testefw.css`.
Há também os arquivos `ac1.css` e `tabela.png` que te dão uma ajudinha no layout dos exercícios 2 e 4.
Por fim, há este arquivo aqui (`LEIAME.md`) e o arquivo `LICENSE` com o qual você não precisa se preocupar.

É recomendável deixar estes arquivos como estão, pois o professsor sempre usará os originais na correção, logo não há porque alterá-los.
Depois de terminar a AC, você até pode mexer nesses arquivos para fazer algum experimento se quiser, colocar linhas de `console.log` para tentar entender como o código funciona, desmontar ou alterar pedaços para fazer debugging, etc.
No entanto, o funcionamento interno desses arquivos está em um nível bastante avançado e complexo e não é esperado que alunos que estejam recém-começando em HTML e menos ainda em CSS e JavaScript os entendam.
De toda forma, se quiser fuçar neles, fique a vontade.
Apenas sempre tenha em mãos os arquivos originais para poder se certificar de que não bagunçou nada e poder voltar atrás facilmente caso precise.

## Como fica a nota?

Os próprios testes já calculam a nota automaticamente, da seguinte forma:

- Faça o exercício 0 antes de qualquer coisa.
Ele se chama exercício 0 porque sem ele, a sua nota também será 0.

- Cada exercício do 1 ao 4 vale de 0 a 2.4, em função da quantidade de testes que passarram em cada um.
  Se passar em todos os testes soma 2.4, se não passar em nenhum soma 0, e se passar em metade, por exemplo, soma 1.2 à nota final.

- Bagunçar a estrutura do HTML mexendo onde não era pra mexer poderá acarretar uma penalidade de até -2 pontos.

- O último grupo de testes que verifica se o HTML está bem formado vale 0.4 pontos.
  Para que ele possa ser executado, você deve estar conectado na internet e se não estiver usando o Firefox, deverá ter o programa `getsrc.py` em execução no seu computador.

OObservações:

- Entrega incorreta poderá ser penalizado em -1 ponto.

- Entregue apenas o arquivo `ac1.html`.

- A inclusão de malware ou código malicioso no arquivo `ac1.html` resultará em nota zero.

- **Fique atento(a) a erros que aparecerem no console do navegador. Eles podem sinalizar um problema sério e ocasionar uma nota zero.**

- **Colocar scripts que travem ou não terminem de carregar nunca (por exemplo, `while (true) { /* fica preso no laço infinito. */ }`) também podem ocasionar uma nota zero.**
Lembrando que nesta AC não é pra fazer script nenhum!

## Como fazer a entrega?

A entrega deve ser feita pelo formulário na AC 1 do classroom.
