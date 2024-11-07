class Heroi {
  constructor(nome, idade, tipo) {
    this.nome = nome;
    this.idade = idade;
    this.tipo = tipo;
  }

  atacar() {
    let ataque;
    switch (this.tipo) {
      case "mago":
        ataque = "usou magia";
        break;
      case "guerreiro":
        ataque = "usou espada";
        break;
      case "monge":
        ataque = "usou artes marciais";
        break;
      case "ninja":
        ataque = "usou shuriken";
        break;
      default:
        ataque = "atacou";
    }
    console.log(`o ${this.tipo} atacou usando ${ataque}`);
  }
}

// Exemplo de uso:
const magoGandalf = new Heroi("Gandalf", 2000, "mago");
magoGandalf.atacar(); // Saída: o mago atacou usando magia

const guerreiroConan = new Heroi("Conan", 30, "guerreiro");
guerreiroConan.atacar(); // Saída: o guerreiro atacou usando espada
