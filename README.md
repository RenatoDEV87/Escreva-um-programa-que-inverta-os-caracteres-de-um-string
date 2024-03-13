# Escreva-um-programa-que-inverta-os-caracteres-de-um-string

5 - Escreva um programa que inverta os caracteres de um string.

IMPORTANTE:

a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;

b) Evite usar funções prontas, como, por exemplo, reverse;

RESPOSTA:

Aqui está um programa em JavaScript que inverte os caracteres de uma string sem usar funções prontas como reverse:

function inverterString(str) {
    let invertedStr = '';
    for (let i = str.length - 1; i >= 0; i--) {
        invertedStr += str[i];
    }
    return invertedStr;
}

// Exemplo de uso
const stringOriginal = "Hello, world!";
const stringInvertida = inverterString(stringOriginal);
console.log("String original:", stringOriginal);
console.log("String invertida:", stringInvertida);

*/ Neste programa, a função inverterString() itera sobre cada caractere da string de trás para frente e os adiciona a uma nova string, invertendo assim a ordem dos caracteres. Por fim, a função retorna a string invertida. O exemplo de uso demonstra como utilizar essa função com uma string específica e exibe a string original e a string invertida no console. */
