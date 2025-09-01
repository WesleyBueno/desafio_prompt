# desafio_prompt
3# desafio
PROMPT:
"Você irá atuar como um desenvolvedor java que está implementando uma conexão ao banco de dados MongoDB para verificar informações da base de dados. Nosso desafio atual é um erro durante a execução do código na verificação de algumas informações, nós temos implementado o seguinte trecho de código que está retornando este erro:
```
public class PagamentoService
{
private readonly string connectionString =
"mongodb://usuario:senha@host:8080/ClienteFinanceiroDB";
public bool ProcessarPagamento(decimal valor, string cpfCliente)
{
if (valor > 10000)
{
throw new Exception("Limite excedido");
}
// TODO: lógica para salvar no MongoDB
return true;
}
}
```


O Erro que ele retorna é o seguinte: //Descrição do erro.
Quando na verdade deveria retornar informações sobre o limite, conforme a lógica descrita no código.
Avaliando este cenário e o código implementado, o que pode estar causando este mal funcionamento no código?

