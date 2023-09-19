# index.js
Com o terminal aberto, entramos na pasta onde o node js se encontra.
Executamos o comando source nodejs-env/bin/activate
Abrimos um nano chamado index.js
Colamos o código do repositório 'helloworld'
Executamos o código node index.js e abrimos uma aba no navegador
Colocamos "localhost:porta do nano(5000)"
Para continuarmos sem muitos problemas, escrevemos o código sudo chown usuário:usuário index.js com o nodejs-env desabilitado (com esse código não precisamos colocar o sudo para executar o nano)
Assim voltamos a ativar o node, abrir o nano e editar o código
Mudamos res.end('Hello World!'); para res.end('19/09/2023 Caroline Camargo da Silva');
E mudamos a porta (no meu caso, de 5000 para 8004)
