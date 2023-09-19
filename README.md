# Hellowordjs

Separei as etapas da atividade em passos:

No primeiro passo, você deve entrar na pasta onde o Node.js está localizado.

No segundo passo, digite o seguinte comando: source ./nodejs/bin/activate, mas apenas se você já tiver o Apache e o Node.js instalados. Esse comando abrirá o ambiente do Node.js.

Em seguida, abra o Nano com o arquivo de texto chamado index.js. No mesmo arquivo, usando o Nano, você deve inserir o seguinte comando:

var http = require('http');

http.createServer(function (req, res) {

res.writeHead(200, {'Content-Type': 'text/plain'});

res.end('João Guilherme Marcondes da Silva'+' 19/09/2023');

}).listen(8006);

Certifiquei de configurar a porta para 8006, pois o seu computador está no armário 1 e é o computador número 6.

Após editar o arquivo com o Nano e configurar corretamente, você precisará aplicar o firewall para permitir que todos acessem o seu IP apenas na porta 8006.

Em último passo, você ira abrir o firefow e digitar http://localhost:8006/ 

<img src="https://github.com/Gui1herm3/Hellowordjs/blob/main/tela-site.png" alt="aa">

E caso queira acessa o computador de outros é apenas mudar a porta ( http://localhost: <porta> )


