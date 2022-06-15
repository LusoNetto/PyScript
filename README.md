# PyScript
<! --Para voce fazer seu primeiro html utilizando o PyScript é muito facil:
1ºColoque essas referencias no seu arquivo html:

```<link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />```
```<script defer src="https://pyscript.net/alpha/pyscript.js"></script>```

2ºAbra seu ```<body></body>```:

```<link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />```
```<script defer src="https://pyscript.net/alpha/pyscript.js"></script>```

```<body></body>```

3ºDentro do ```<body></body>``` vamos criar um ```<h1></h1>``` para darmos o nome que queremos, no meu caso foi "Nosso primeiro código com PyScript":

```<link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />```
```<script defer src="https://pyscript.net/alpha/pyscript.js"></script>```

```<body>```
  ```<h1>Nosso primeiro código com PyScript</h1>```
```</body>```

4ºLogo abaixo utilizamos a tag ```<py-script></py-script>``` e dentro dela colocamos nosso código em python, o código que utilizei é simples, tratasse de importar o ```datatime``` e logo apos colocar na variável ```now``` o ```datatime.now```, depois temos um comando ```now.strftime("%m/%d/%Y, %H:%M:%S")``` que vai fazer com que seja exibido o: meses dias anos e horas minutos e segundos. Um código simples só para podermos ver o potencial da ferramenta!

```<link rel="stylesheet" href="https://pyscript.net/alpha/pyscript.css" />```
```<script defer src="https://pyscript.net/alpha/pyscript.js"></script>```
```<body>```
    ```<h1>Nosso primeiro código com PyScript</h1>```
        ```<py-script>```
    ```print('Hello World')```
    ```from datetime import datetime```
    ```now = datetime.now()```
    ```now.strftime("%m/%d/%Y, %H:%M:%S")```
        ```</py-script>```
```</body>```

5º Se voce estiver no linux é só salvar o seu documento, abrir o terminal na pasta onde esta o arquivo html e dar o comando ```$ open <nomeDoSeuArquivo>.html```
6º Se estiver no Windows é só salvar o seu documento e abrir o arquivo ```<nomeDoSeuArquivo>.html``` com o chrome.

Parabéns voce acabou de utilizar a ferramenta PyScript!-->
