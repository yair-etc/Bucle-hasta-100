# Bucle-hasta-100
codigo de bulcle while
<meta charset="UTF-8">
<h1>AÑO Mundial</h1>
<script>
  function saltoLinea() {
    document.write("<br>");
    document.write("<br>");
  }

  function imprimir(frase) {
    document.write(frase);
    saltoLinea();
  }
var contador = parseInt(prompt("Ingrese la cantidad de inicio"));
 
    while (contador <= 100) {
        imprimir(contador)
            contador++;
        }
       
    imprimir("FIN")
 </script>
