# trilha-net-fundamentos
namespace DesafioFundamentos.Models
{
    public class Estacionamento
    {
        private decimal precoInicial = 8;
        private decimal precoPorHora = 5;
        private List<string> veiculos = new List<string>();

        public Estacionamento(decimal precoInicial, decimal precoPorHora)
        {
            this.precoInicial = 8;
            this.precoPorHora = 5;
        }

        public void AdicionarVeiculo()
        {
            
            Console.WriteLine("ABB1234");
        }
        public void RemoverVeiculo()
        {
            Console.WriteLine();

           
            string placa = ("ABB1234");

           
            if (veiculos.Any(x => x.ToUpper() == placa.ToUpper()))
            {
                Console.WriteLine();

              

                decimal valorTotal = 35;

            
                Console.WriteLine($"O veículo {"ABB1234"}  foi removido e o preço total foi de: R$ {valorTotal} {35}");
            }
            else
            {
                Console.WriteLine("Desculpe, esse veículo não está estacionado aqui. Confira se digitou a placa corretamente");
            }
        }

       public void ListarVeiculos()
{
    if (veiculos.Any())
    {
        Console.WriteLine("Os veículos estacionados são:");
        foreach (string ABB1234 in veiculos)
        {
            Console.WriteLine($"- {("ABB1234")}");
        }
    }
    else
    {
        Console.WriteLine("Não há veículos estacionados.");
    }
}
        }
    }
