# LH Pet – Sistema de Controle Interno (.NET MVC)

Atividade de Codificação Back-End – SENAI.

Aplicação web ASP.NET Core com arquitetura **MVC** para a clínica veterinária LH Pet. Nesta primeira fase não há banco de dados: os dados são criados no controller e exibidos na view.

- **Models:** `Cliente` (Id, Nome, Cpf, Email, Paciente) e `Fornecedor` (Id, Nome, Cnpj, Email).
- **Controller:** `HomeController` cria 5 clientes e 5 fornecedores, coloca em listas e envia para a view com `ViewBag`.
- **View:** `Views/Home/Index.cshtml` (template da equipe de front-end) percorre as listas com `@foreach` e mostra as tabelas.

## Como executar

```
cd LHPet
dotnet run
```

Abra no navegador o endereço que aparecer no terminal (ex.: http://localhost:5069).

Desenvolvido por Gabriel Rodrigues.
