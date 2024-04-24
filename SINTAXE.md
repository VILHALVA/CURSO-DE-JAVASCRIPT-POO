# SINTAXE POO
POO (Programação Orientada a Objetos) é um paradigma de programação que se baseia na ideia de "objetos", que podem conter dados na forma de campos, também conhecidos como atributos, e código, na forma de procedimentos, geralmente chamados de métodos. Esses objetos são instâncias de classes, que funcionam como modelos para criar objetos.

Os quatro pilares da programação orientada a objetos são:

1. **Abstração:**
   - **Conceito:** Abstração em JavaScript é alcançada através da criação de classes que representam entidades ou objetos do mundo real.
   - **Exemplo de código:**

    ```javascript
    class Veiculo {
        constructor(marca, modelo) {
            this.marca = marca;
            this.modelo = modelo;
        }
    
        dirigir() {
            console.log(`Dirigindo o ${this.modelo} da marca ${this.marca}.`);
        }
    }
    ```

2. **Encapsulamento:**
   - **Conceito:** Encapsulamento em JavaScript é geralmente alcançado usando closures para criar membros privados de uma classe.
   - **Exemplo de código:**

    ```javascript
    class Veiculo {
        constructor(marca, modelo) {
            this.marca = marca;
            this.modelo = modelo;
            let ligado = false;
    
            this.ligar = function() {
                ligado = true;
                console.log("Veículo ligado.");
            }
    
            this.desligar = function() {
                ligado = false;
                console.log("Veículo desligado.");
            }
    
            this.estaLigado = function() {
                return ligado;
            }
        }
    }
    ```

3. **Herança:**
   - **Conceito:** Herança em JavaScript é alcançada usando o protótipo. Uma classe pode herdar métodos e propriedades de outra classe.
   - **Exemplo de código:**

    ```javascript
    class Carro extends Veiculo {
        constructor(marca, modelo, cor) {
            super(marca, modelo);
            this.cor = cor;
        }
    
        info() {
            console.log(`Marca: ${this.marca}, Modelo: ${this.modelo}, Cor: ${this.cor}`);
        }
    }
    ```

4. **Polimorfismo:**
   - **Conceito:** Polimorfismo em JavaScript é a capacidade de uma função ou método se comportar de maneiras diferentes com base nos tipos de argumentos passados ou nos tipos dos objetos.
   - **Exemplo de código:**

    ```javascript
    class VeiculoEletrico extends Veiculo {
        constructor(marca, modelo, autonomia) {
            super(marca, modelo);
            this.autonomia = autonomia;
        }
    
        dirigir() {
            console.log(`Dirigindo o ${this.modelo} da marca ${this.marca} com autonomia de ${this.autonomia} km.`);
        }
    }
    ```

Estes são os quatro pilares da programação orientada a objetos implementados em JavaScript. Cada pilar desempenha um papel fundamental na criação de sistemas orientados a objetos robustos e reutilizáveis em JavaScript.