# oficina-automotiva
criando uma oficina em js
// Definindo a classe OficinaAutomotiva

class OficinaAutomotiva {
// Construtor da classe

    constructor(nome) {
    this.name = nome;
    this.carroReparados = 0;
    }

}

// Método para realizar reparo em um carro

realizarReparo(carro)
    console.log("Realizando reparo no carro ${carro.midelo}...");
    // lógica de reparo aqui
    console.log("Reparo concluído no carro ${carro.modelo}.");
    this.carrosReparados++;


//Método para pbter o número total de carros reparados
obterTotalCarrosReparados()
    return this.carrsReparados;

// Exemplo de uso da classe
const oficina = new OficinaAutomotiva("oficina do João");

// Criando um carro
const carro  = {modelo: "fusca", ano: 1980};

// Realizando reparo e manutenção
oficina.realizarReparo(carro);
oficina.realizaManutencao(carro);

// Obtendo o número total de carros reparados
const totalCarrosReparados = oficina.obterTotalCarrosReparados();
console.log("Total de carros reparados na ${oficina.nome}: ${totalCarrosReparados}");
