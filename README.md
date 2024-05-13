<html>
<head>
<title>Eventos de Teclado</title>
</head>
<body>
<label for="digitado">Teste de Eventos de Teclado:</label>
<textarea id="digitado"></textarea>
<label for="resposta">Eventos Tratados:</label>
<textarea id="resposta" rows="30" cols="50"></textarea>
<script>
    digitado.addEventListener("keydown",
    function(evento) {
        resposta.innerHTML  +=  "\nTecla  Pressionada:  "   +
evento.keyCode;
        });
    digitado.addEventListener("keyup",
    function(evento) {
        resposta.innerHTML+="\nTecla Liberada";
        });
</script>
</body>
<html>