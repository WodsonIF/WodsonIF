- 👋 Hi, I’m @Reino Animal
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...



Código da Classe Animal

package dominino;

public class Animal {
	private String nome,anoNascimento, sexo, especie, raca;
	private Cliente cli;
	
	public Animal(String nome, String anoNascimento, String sexo, String especie, String raca) {
		this.nome = nome;
		this.anoNascimento = anoNascimento;
		this.sexo = sexo;
		this.especie = especie;
		this.raca = raca;
	}
	
	public String getNomeA() {
		return nome;
	}
	
	public void setNome(String nome) {
		this.nome = nome;
	}
	
	public String getAnoNascimento() {
		return anoNascimento;
	}
	
	public void setAnoNascimento(String anoNascimento) {
		this.anoNascimento = anoNascimento;
	}
	
	public String getSexo() {
		return sexo;
	}
	
	public void setSexo(String sexo) {
		this.sexo = sexo;
	}
	
	public String getEspecie() {
		return especie;
	}
	
	public void setEspecie(String expecie) {
		this.especie = expecie;
	}
	
	public String getRaca() {
		return raca;
	}
	
	public void setRaca(String raca) {
		this.raca = raca;
	}
	
	public void setCli(Cliente cli) {
		this.cli = cli;
	}
}






public class Animal {
	private String nome,anoNascimento, sexo, especie, raca;
	private Cliente cli;
	
	public Animal(String nome, String anoNascimento, String sexo, String especie, String raca) {
		this.nome = nome;
		this.anoNascimento = anoNascimento;
		this.sexo = sexo;
		this.especie = especie;
		this.raca = raca;
	}
	
	public String getNomeA() {
		return nome;
	}
	
	public void setNome(String nome) {
		this.nome = nome;
	}
	
	public String getAnoNascimento() {
		return anoNascimento;
	}
	
	public void setAnoNascimento(String anoNascimento) {
		this.anoNascimento = anoNascimento;
	}
	
	public String getSexo() {
		return sexo;
	}
	
	public void setSexo(String sexo) {
		this.sexo = sexo;
	}
	
	public String getEspecie() {
		return especie;
	}
	
	public void setEspecie(String expecie) {
		this.especie = expecie;
	}
	
	public String getRaca() {
		return raca;
	}
	
	public void setRaca(String raca) {
		this.raca = raca;
	}
	
	public void setCli(Cliente cli) {
		this.cli = cli;
	}
}






Código da Classe Cliente

package dominino;

import java.util.ArrayList;
import java.util.Vector;

public class Cliente {
	private String cpf, nome, endereco, telefone;
	private ArrayList<Animal> listaAnimal;
	
	public Cliente(String cpf, String nome, String endereco, String telefone) {
		this.cpf = cpf;
		this.nome = nome;
		this.endereco = endereco;
		this.telefone = telefone;
		listaAnimal = new ArrayList<Animal>();
	}

	public String getCpf() {
		return cpf;
	}

	public void setCpf(String cpf) {
		this.cpf = cpf;
	}

	public String getNome() {
		return nome;
	}

	public void setNome(String nome) {
		this.nome = nome;
	}

	public String getEndereco() {
		return endereco;
	}

	public void setEndereco(String endereco) {
		this.endereco = endereco;
	}

	public String getTelefone() {
		return telefone;
	}

	public void setTelefone(String telefone) {
		this.telefone = telefone;
	} 
	
	public void addAnimal(Animal novoAnimal) {
		if (listaAnimal.contains(novoAnimal)) 
			return;
		else {
			listaAnimal.add(novoAnimal); 
			novoAnimal.setCli(this);  
		}
	}
	
	public void removeAnimal (Animal exAnimal) {
		if (!listaAnimal.contains(exAnimal))
			return;
		else {
			listaAnimal.remove(exAnimal);
			exAnimal.setCli(null);
		}
	}
	
	public ArrayList getListaAnimal() { 
		return listaAnimal;
	}
}



        this.nome = nome;
        this.comprimento = comprimento;
        this.num_patas = num_patas;
        this.cor = cor;
        this.ambiente = ambiente;
        this.vel_media = vel_media;
        this.alimento = alimento;




   
    public String getAlimento()
    {
        return this.alimento;
    }


     public void setAlimento(String alimento)
    {
        this.alimento = alimento;
    }
   
    public void dadosMamifero()
    {


 public void dadosMamifero()
    {
        String str = "DADOS DO MAMÍFERO:\nNome: " + this.nome + "\nComprimento: " + this.comprimento +
                     "m\nNúmero de patas: " + this.num_patas + "\nCor: " + this.cor +
                     "\nAmbiente: " + this.ambiente + "\nVelocidade Média: " + this.vel_media + " km/h\n" +
                     "Caracteristica: " + this.caracteristica;
           
           
        System.out.println(str);
    }
}

public void Aquático()


public class Animal {
	private String nome,anoNascimento, sexo, especie, raca;
	private Cliente cli;
	
	public Animal(String nome, String anoNascimento, String sexo, String especie, String raca) {
		this.nome = nome;
		this.anoNascimento = anoNascimento;
		this.sexo = sexo;
		this.especie = especie;
		this.raca = raca;
	}
	
	public String getNomeA() {
		return nome;
	}
	
	public void setNome(String nome) {
		this.nome = nome;
	}
	
	public String getAnoNascimento() {
		return anoNascimento;
	}
	
	public void setAnoNascimento(String anoNascimento) {
		this.anoNascimento = anoNascimento;
	}
	
	public String getSexo() {
		return sexo;
	}
	
	public void setSexo(String sexo) {
		this.sexo = sexo;
	}
	
	public String getEspecie() {
		return especie;
	}
	
	public void setEspecie(String expecie) {
		this.especie = expecie;
	}
	
	public String getRaca() {
		return raca;
	}
	
	public void setRaca(String raca) {
		this.raca = raca;
	}
	
	public void setCli(Cliente cli) {
		this.cli = cli;
	}
}




    }
   
    public String getAlimento()
    {
        return this.alimento;
    }
   
    public void setAlimento(String alimento)
    {
        this.alimento = alimento;
    }
   
    public void dadosMamifero()
    {



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


public class principal ()
	private String nome,anoNascimento, sexo, especie, raca;
	private Cliente cli;
	
	public Reinoteste(String nome aquático, String Carcharias taurus, fêmea, 7, água salgada, false;
- Pygocentrus nattereri, macho, 3, água doce, true;, String Aereo , String especie, String raca) {
		this.nome = nome;
		this.anoNascimento = anoNascimento;
		this.sexo = sexo;
		this.especie = especie;
		this.raca = raca;
	}
	
	public String getNomeA() {
		return nome;
	}
	
	public void setNome(String nome) {
		this.nome = nome;
	}
	
	public String getAnoNascimento() {
		return anoNascimento;
	}
	
	public void setAnoNascimento(String anoNascimento) {
		this.anoNascimento = anoNascimento;
	}
	
	public String getSexo() {
		return sexo;
	}
	
	public void setSexo(String sexo) {
		this.sexo = sexo;
	}
	
	public String getEspecie() {
		return especie;
	}
	
	public void setEspecie(String expecie) {
		this.especie = expecie;
	}
	
	public String getRaca() {
		return raca;
	}
	
	public void setRaca(String raca) {
		this.raca = raca;
	}
	
	public void setCli(Cliente cli) {
		this.cli = cli;
	}
}






Código da Classe Cliente

package dominino;

import java.util.ArrayList;
import java.util.Vector;

public class Cliente {
	private String cpf, nome, endereco, telefone;
	private ArrayList<Animal> listaAnimal;
	
	public Cliente(String cpf, String nome, String endereco, String telefone) {
		this.cpf = cpf;
		this.nome = nome;
		this.endereco = endereco;
		this.telefone = telefone;
		listaAnimal = new ArrayList<Animal>();
	}

	public String getCpf() {
		return cpf;
	}

	public void setCpf(String cpf) {
		this.cpf = cpf;
	}

	public String getNome() {
		return nome;
	}

	public void setNome(String nome) {
		this.nome = nome;
	}

	public String getEndereco() {
		return endereco;
	}

	public void setEndereco(String endereco) {
		this.endereco = endereco;
	}

	public String getTelefone() {
		return telefone;
	}

	public void setTelefone(String telefone) {
		this.telefone = telefone;
	} 
	
	public void addAnimal(Animal novoAnimal) {
		if (listaAnimal.contains(novoAnimal)) 
			return;
		else {
			listaAnimal.add(novoAnimal); 
			novoAnimal.setCli(this);  
		}
	}
	
	public void removeAnimal (Animal exAnimal) {
		if (!listaAnimal.contains(exAnimal))
			return;
		else {
			listaAnimal.remove(exAnimal);
			exAnimal.setCli(null);
		}
	}
	
	public ArrayList getListaAnimal() { 
		return listaAnimal;
	}
}public class principal {
	String nome;
	int idade;
	
	//Metodos
	public void ReinoAnimal ()
	{
		System.out.println("todos!");
	}
}


public class  aquático extends Animal {
	//Metodos

Carcharias taurus, fêmea, 7, água salgada, false;
- Pygocentrus nattereri, macho, 3, água doce, true;


	public void vivem águas (todos!)



	{
		System.out.println("10");
	}
	
		System.out.println(" 7");
	}
}


public class  terr extends Animal {
	//Metodos



	public void vivem águas (todos!)



	{
		System.out.println("10");
	}
	
		System.out.println(" 7");
	}
}

public void listarAnimais() { for(int i =0; i<jaula.length; i++) { System.out.println(jaula[i].getClass().getSimpleName()); } }

Ou, melhor ainda:

public void listarAnimais() { for(Animal animal : jaula) { System.out.println(animal.getClass().getSimpleName()); } }




<!---
ReinoAnimal/Reino is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

