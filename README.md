- 👋 Hi, I’m @Reino Animal
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...





// Encapsulamento das propriedades e métodos de Animal
var Animal = {
  tipo: "Invertebrados", // Propriedades de valores padrão
  qualTipo: function () {
    // Método que ira mostrar o tipo de Animal
    console.log(this.tipo);
  },
};

// Cria um novo tipo de animal chamado animal1
var animal1 = Object.create(Animal);
animal1.qualTipo(); // Saída:Invertebrados

// Cria um novo tipo de animal chamado Peixes
var peixe = Object.create(Animal);
peixe.tipo = "Peixes";
peixe.qualTipo(); // Saída: Peixes



var meuObjeto = {
  meuMetodo: function (parametros) {
    // ...faça algo
  },
};



var o = {
  a: 7,
  get b() {
    return this.a + 1;
  },
  set c(x) {
    this.a = x / 2;
  },
};

console.log(o.a); // 7
console.log(o.b); // 8
o.c = 50;
console.log(o.a); // 25




// Duas variáveis, dois objetos distintos com as mesmas propriedades
var fruit = { name: "apple" };
var fruitbear = { name: "apple" };

fruit == fruitbear; // return false
fruit === fruitbear; // return false



// Duas variáveis, um único objeto
var fruit = { name: "apple" };
var fruitbear = fruit; // assign fruit object reference to fruitbear

// Here fruit and fruitbear are pointing to same object
fruit == fruitbear; // return true
fruit === fruitbear; // return true



<!---
ReinoAnimal/Reino is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

