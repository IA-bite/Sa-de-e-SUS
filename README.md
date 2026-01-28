<!doctype html>
<html lang="pt-BR">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Sistema Municipal de Saúde</title>

    <!-- Se você usa Tailwind via CDN (opcional) -->
    <script src="https://cdn.tailwindcss.com"></script>
  </head>

  <body class="min-h-screen bg-gray-100 p-6">
    <h1 class="text-3xl font-bold text-center mb-8">Sistema Municipal de Saúde</h1>

    <!-- Login -->
    <div class="max-w-md mx-auto bg-white p-6 rounded-2xl shadow mb-8">
      <h2 class="text-xl font-semibold mb-4">Login do Cidadão</h2>

      <input class="w-full border p-2 rounded mb-3" placeholder="CPF" />
      <input class="w-full border p-2 rounded mb-3" placeholder="Senha" type="password" />

      <button class="w-full bg-blue-600 text-white py-2 rounded-xl" type="button">
        Entrar
      </button>

      <p class="text-sm text-gray-500 mt-3">Opções de segurança: SMS • E-mail • Gov.br</p>
    </div>

    <!-- Dashboard -->
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white p-5 rounded-2xl shadow">
        <h3 class="font-semibold mb-2">📅 Consultas</h3>
        <p class="text-gray-600">Histórico e próximas consultas</p>
      </div>

      <div class="bg-white p-5 rounded-2xl shadow">
        <h3 class="font-semibold mb-2">🧪 Exames SUS</h3>
        <p class="text-gray-600">Resultados sincronizados com o SUS</p>
      </div>

      <div class="bg-white p-5 rounded-2xl shadow">
        <h3 class="font-semibold mb-2">🏥 Exames da Clínica</h3>
        <p class="text-gray-600">Uploads e integrações locais</p>
      </div>
    </div>

    <!-- Lista de Exames -->
    <div class="bg-white p-6 rounded-2xl shadow mt-8">
      <h2 class="text-xl font-semibold mb-4">Resultados de Exames</h2>

      <table class="w-full text-left">
        <thead>
          <tr class="border-b">
            <th class="py-2">Exame</th>
            <th>Origem</th>
            <th>Data</th>
            <th>Status</th>
          </tr>
        </thead>

        <tbody>
          <tr class="border-b">
            <td class="py-2">Hemograma</td>
            <td>SUS</td>
            <td>10/01/2025</td>
            <td class="text-green-600">Disponível</td>
          </tr>

          <tr>
            <td class="py-2">Raio-X Tórax</td>
            <td>Clínica Municipal</td>
            <td>15/01/2025</td>
            <td class="text-yellow-600">Em análise</td>
          </tr>
        </tbody>
      </table>
    </div>
  </body>
</html>
