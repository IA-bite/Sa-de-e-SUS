export default function SaudeMunicipal() {
  return (
    <div className="min-h-screen bg-gray-100 p-6">
      <h1 className="text-3xl font-bold text-center mb-8">Sistema Municipal de Saúde</h1>

      {/* Login */}
      <div className="max-w-md mx-auto bg-white p-6 rounded-2xl shadow mb-8">
        <h2 className="text-xl font-semibold mb-4">Login do Cidadão</h2>
        <input className="w-full border p-2 rounded mb-3" placeholder="CPF" />
        <input className="w-full border p-2 rounded mb-3" placeholder="Senha" type="password" />
        <button className="w-full bg-blue-600 text-white py-2 rounded-xl">Entrar</button>
        <p className="text-sm text-gray-500 mt-3">Opções de segurança: SMS • E-mail • Gov.br</p>
      </div>

      {/* Dashboard */}
      <div className="grid md:grid-cols-3 gap-6">
        <div className="bg-white p-5 rounded-2xl shadow">
          <h3 className="font-semibold mb-2">📅 Consultas</h3>
          <p className="text-gray-600">Histórico e próximas consultas</p>
        </div>

        <div className="bg-white p-5 rounded-2xl shadow">
          <h3 className="font-semibold mb-2">🧪 Exames SUS</h3>
          <p className="text-gray-600">Resultados sincronizados com o SUS</p>
        </div>

        <div className="bg-white p-5 rounded-2xl shadow">
          <h3 className="font-semibold mb-2">🏥 Exames da Clínica</h3>
          <p className="text-gray-600">Uploads e integrações locais</p>
        </div>
      </div>

      {/* Lista de Exames */}
      <div className="bg-white p-6 rounded-2xl shadow mt-8">
        <h2 className="text-xl font-semibold mb-4">Resultados de Exames</h2>
        <table className="w-full text-left">
          <thead>
            <tr className="border-b">
              <th className="py-2">Exame</th>
              <th>Origem</th>
              <th>Data</th>
              <th>Status</th>
            </tr>
          </thead>
          <tbody>
            <tr className="border-b">
              <td className="py-2">Hemograma</td>
              <td>SUS</td>
              <td>10/01/2025</td>
              <td className="text-green-600">Disponível</td>
            </tr>
            <tr>
              <td className="py-2">Raio-X Tórax</td>
              <td>Clínica Municipal</td>
              <td>15/01/2025</td>
              <td className="text-yellow-600">Em análise</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  );
}
