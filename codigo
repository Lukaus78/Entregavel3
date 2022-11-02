var port = 3001;

// iniciando o processo do servidor
app.listen(port, function() {
  console.log(`App de Exemplo escutando na porta http://localhost:${port}/`);
});

app.post('/soma', function (req, res) {
    res.send('Response da requisição POST');
  });
  var app 
  var bodyParser = require('body-parser');
const res = require('express/lib/response');
  var body = req.body;
console.log(body);
res.send('via post');
app.use(bodyParser.json());

function soma(a, b) {
    return a + b;
  }

  var body = req.body;
var resultado = soma(body.a, body.b);

res.send(`O resultado da soma de ${body.a} e ${body.b} é ${resultado}`);

function subtração(a, b) {
    return a - b;
  }
  var body = req.body;
var resultado = subtração(body.a, body.b);

res.send(`O resultado da subtração de ${body.a} e ${body.b} é ${resultado}`);

function divisão(a, b){
    return a - b;
}
var body = req.body;
var resultado = divisão(body.a, body.b);
res.send(`O resultado da divisão de ${body.a} e ${body.b} é ${resultado}`);

function multiplicação(a, b){
    return a * b ;
}
var body = req.body;
var resultado = multiplicação(body.a, body.b);
res.send(`O resultado da multiplicação de ${body.a} e ${body.b} é ${resultado}`)
