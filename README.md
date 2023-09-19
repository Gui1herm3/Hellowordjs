# Hellowordjs

Separei as etapas da atividade em passos:

 Em primeiro passo, seria vc entrar na pasta aonde esta localizado o nodejs
 no segundo passo, digitar o seguinte comando source ./nodejs/bin/activate mas ja com apache e nodejs baixado. Esse comando vai abrir o nodejs-env
 vai abrir o nano com o arquivo de texto chamado index.js. nesse mesmo arquivo com o nano, você vai colocar o seguinte comando:
 {
 
 var http = require('http');

http.createServer(function (req, res) {

  res.writeHead(200, {'Content-Type': 'text/plain'});
  
  res.end('João Guilherme Marcondes da Silva'+' 19/09/2023');
  
}).listen(8006);

}
Teria que configurar a porta para 8006 pois meu computador é do armário 1 e é o computador número 6.
Depois de colocar o nano e configurar certo, tive que aplicar o firewall para todos conseguirem entrar no meu ip apenas com a porta 8006.
