# Generador-Super-Prompts
Mejora un simple prompt 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>MiniMax Prompt Generator</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f0f2f5; padding: 2em; }
    .container { max-width: 600px; margin: auto; background: white; padding: 2em; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    input, button { width: 100%; padding: 0.8em; margin-top: 1em; font-size: 1em; }
    #output { margin-top: 1em; background: #e8f5e9; padding: 1em; border-radius: 5px; }
  </style>
</head>
<body>
  <div class="container">
    <h2>🧠 Generador de Prompts estilo MiniMax</h2>
    <input type="text" id="promptInput" placeholder="Escribe tu idea aquí...">
    <button onclick="generarPrompt()">Generar Prompt</button>
    <div id="output"></div>
  </div>

  <script>
    function generarPrompt() {
      const entrada = document.getElementById("promptInput").value;
      const resultado = `Prompt generado: Imagina que eres un experto en IA y responde a esta idea: "${entrada}" con profundidad y creatividad.`;
      document.getElementById("output").innerText = resultado;
    }
  </script>
</body>
</html>
