
## PRINCÍPIOS E ESTRUTURAS ESSENCIAIS

#### Variáveis e tipos de dados
   Variáveis são utilizadas para armazenar resultados gerados pelo código.  
   Cada variável obrigatoriamente terá um tipo de dado.  
   Precisam ser declaradas de forma prévia ao bloco do código (palavra reservada "var"). <br> 
   Os tipos de dado existentes são:<br>   
      - Float ou Real - exemplo: 3.4  <br> 
      - Integer ou Inteiro - exemplo: 3  <br> 
      - Boolean ou Booleano - exemplo: True ou Verdadeiro

#### Constantes e parâmetros
   Constantes e parâmetros são valores que não se alteram enquanto o código roda. A diferença entre ambos é que o usuário consegue interagir fora do editor com os parâmetros. Ambos precisam ser declarados de forma prévia ao bloco do código (palavras reservadas "const" e "input").

#### Séries de dados
   São palavras reservadas que retornam valores específicos das figuras gráficas. As séries existentes são: <br>
   Open ou Abertura <br>
   Close ou Fechamento <br>
   Low ou Mínima <br>
   High ou Máxima <br>
   Quantity ou Quantidade <br>
   Volume

#### Controle de fluxo
   NTSL roda de forma sequencial, linha a linha. Os controles de fluxos consegue alterar essa lógica. Os existentes são: <br>
   Estrutura IF THEN ELSE (também chamado de teste condicional) <br>
   Estrutura FOR DO <br>
   Estrutura WHILE DO

#### Operadores
   Estruturas Lógicas que auxiliam na criação do código. Podem ser matemáticos (+, -, * etc) ou lógicos (E ou AND / OR ou OU).

#### Funções 
   Comandos que geram ações específicas no código. Podem ser nativas da NTSL ou criadas pelo usuário. São as funções que classificam se uma estratégia possui indicador, coloração, execução, alarme etc. Deixar o mouse em cima de uma função escrita no código fornecerá maiores detalhes. Os detalhes envolvem descrição, quais parâmetos ela está esperando e qual é o resultado que ela retorna. <br>
   As principais funções de execução são: <br>
   BuyAtMarkert e SellAtMarket, para abrir posições a mercado <br>
   BuyToCoverAtMarket e SellToCoverAtMarket, para fechar posições a mercado <br>
   BuyLimit e SellLimit, para abrir posições com ordens limitadas <br>
   BuyToCoverLimit e SellToCoverLimit, para fechar posições com ordens limitadas <br>

#### Deslocamento
   Conceito que permite ao código acessar valores de períodos prévios.
   Exemplo: Close[0] se referencia ao preço de fechamento do candle de referência. <br>
   Exemplo: Close[1] se referencia ao preço de fechamento de 1 candle prévio ao de referência. <br>
   Exemplo: Close[2] se referencia ao preço de fechamento de 2 candle prévio ao de referência. <br>
   
