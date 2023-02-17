# -M1S02-Ex_8_Pessoa

[M1S02] Ex 8 - Criar uma classe chamada Pessoa

Detalhes da classe

Propriedades

Nome tipo texto (string)

DataNascimento tipo Data (datetime)

Criar um método público chamado MostrarIdade

Chame o método calcular idade

Mostrar texto no console “Nome {nome} tem a Idade {idade}”

Criar uma função  com modificador privado que calcule a idade da pessoa e retorne o inteiro

Utilizar código citado

Substituir a variável local dataNascimento pela sua propriedade DataNascimento

Instanciar a classe no console conforme mostrado em aula



Código para calcular idade :

var dataNascimento = new DateTime(1984, 1, 2);
var dataAtual = DateTime.Now;
var idade = dataAtual.Year - dataNascimento.Year;
if (dataNascimento > dataAtual.AddYears(-idade))
{
 idade--;
}
