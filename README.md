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

  var yearMundial = 1929;
  var yearLimite = parseInt(prompt("ingresa el año limite para calcular:"));
    while (yearMundial <= yearLimite ){
        alert("hubo  mundial de la FIFA en el año  " + yearMundial);
        yearMundial = yearMundial + 4;
        if (yearMundial == yearLimite){
            break;

        }
        yearMundial++;

    }
    alert("fin")


</script>
