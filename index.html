<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>La libertad avanza | Fiscales</title>
  <link rel="icon" href="paloma.ico" type="/img/paloma">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootswatch/5.3.2/quartz/bootstrap.rtl.min.css" integrity="sha512-WEpIXD3Qj3ZReJ8K8CKEDr+khds1UpgRngbPLF1terZBkQqT0pF+rjT6AEfiRGUB0ORmbkP2nC5bFBYBnFauaA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link href="https://cdn.jsdelivr.net/npm/select2@4.1.0-rc.0/dist/css/select2.min.css" rel="stylesheet" />
</head>
<body>


<div class="container" id="calculos">
  <p></p>

  <div class="text-center bg-white rounded-pill">
      <img src="./img/enpapel.png" class="rounded" alt="..." style="width: 200px;">
  </div>

  <p></p>
      
    <div class="card">
      <div class="card-header text-center">
        Calculadora de stickers/metro
      </div>
      <div class="card-body">

            <p></p>
            <small>Precio por metro material</small>
            <input type="number" id="preciometro" class="form-control border  border-opacity-75">
            <p></p>
            <small>Piezas por metro</small>
            <input type="number"  id="piezasmetro" class="form-control border  border-opacity-75">
            <p></p>
            <small>Piezas necesarias</small>
            <input type="number"  id="piezasnecesarias" class="form-control border border-opacity-75">
            <p></p>
            <div class="row">
              <p></p>
                <div class="btn-group" role="group" aria-label="Basic radio toggle button group">
                  <input type="radio" class="btn-check" name="btnradio" id="sincorte"  checked="">
                  <label class="btn btn-outline-primary" for="sincorte">Sin corte</label>
                  <input type="radio" class="btn-check" name="btnradio" id="concorte" >
                  <label class="btn btn-outline-primary" for="concorte">Con corte</label>
                </div>

          
            </div>
            <p></p>

            <div class="container p-0" id="elementosCortes">
              <small>Precio por metro corte</small>
              <input type="number" id="preciocorte" class="form-control border border-opacity-75">
            </div>
<p></p>
           
         <div class="d-grid gap-2">
           <button type="button"  class="btn btn-primary calcular">Calcular</button>
         </div>

  <p></p>
   

         <div id="resultado">
        
        </div>


      </div>
      <div class="card-footer text-muted">
        Te amo ♡
      </div>
    </div>

   
</div>
<p></p>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootswatch/5.3.2/quartz/bootstrap.rtl.min.css" integrity="sha512-WEpIXD3Qj3ZReJ8K8CKEDr+khds1UpgRngbPLF1terZBkQqT0pF+rjT6AEfiRGUB0ORmbkP2nC5bFBYBnFauaA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/select2@4.1.0-rc.0/dist/js/select2.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.min.css">



<script>



const pantalla = document.querySelector("#calculos");

cargarEventListener();
acciondecheck();

function cargarEventListener(){
    pantalla.addEventListener('click',verClick);
}


function verClick(e){
    

    if( e.target.classList.contains('btn-check')){
      acciondecheck();
    }

    if( e.target.classList.contains('calcular')){
     
      var inputPrecio = document.getElementById("preciometro").value;
      var inputPiezas = document.getElementById("piezasmetro").value;
      var inputPrecioCorte = document.getElementById("preciocorte").value;
      var inputNecesarias = document.getElementById("piezasnecesarias").value;

      var TotalLargo = (100 / inputPiezas) * inputNecesarias; TotalLargo = Math.ceil(TotalLargo);
      
      var LargoRedondeado = Math.ceil(TotalLargo / 50) * 50;

      var PrecioLona = ((TotalLargo * inputPrecio)/100);
      
      var pCortado =  ((LargoRedondeado * inputPrecioCorte )/100);

     
      var PrecioRedondeado = ((LargoRedondeado * inputPrecio)/100);

      var totalLo = PrecioRedondeado + pCortado;

        var resultado = document.getElementById("resultado");
        resultado.innerHTML = `
        <div class="card text-white bg-dark">
          <div class="card-header">Resultados</div>
          <div class="card-body">
          <h2>Resultados </h2>
            <p> Redondeando necesitas un total de ${LargoRedondeado} cm de largo </p>
            <p> Pago Lona :  ${PrecioRedondeado} $</p>
            <p> Pago corte :  ${pCortado} $</p>
            <p> Total : ${totalLo} $</p>

            <figure class="text-center">
            <blockquote class="blockquote">
               Calculo exacto
            </blockquote>
            <figcaption class="blockquote-footer">
              ${TotalLargo} cm de largo | Pago :  ${PrecioLona}
            </figcaption>
          </figure>

          </div>
        </div>
       
       `;
      
    }

}

function getSelectedRadioButton() {
    var radioButtons = document.getElementsByName("btnradio");
    for (var i = 0; i < radioButtons.length; i++) {
      if (radioButtons[i].checked) {
        return radioButtons[i].id;
      }
    }
    return null; // Ningún botón está seleccionado
  }

  function acciondecheck(){
    

    var selectedRadioButton = getSelectedRadioButton();
      var elementosCortes = document.getElementById("elementosCortes");
      var inputcorte = document.getElementById("preciocorte");

      if (selectedRadioButton == "concorte") {
        inputcorte.removeAttribute("readonly");
        inputcorte.value =  "";
    
      } else if  (selectedRadioButton == "sincorte") {
        inputcorte.setAttribute("readonly", true);
        inputcorte.value =  "";
    
      }

  }


</script>
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
</body>

</html>
