// 1. Imprimir Números Consecultivos
for (let i = 1; i <= 5; i++) {
    console.log(i);
}

// 2. Duplicar Valores do Array
let numeros = [10, 20, 30];
let numerosDobrados = numeros.map(num => num * 2);
console.log(numerosDobrados);

// 3. Exibir cada Nome
let nomes = ['Ana', 'Bruna', 'Carla'];
nomes.forEach(nome => {
    console.log(nome);
});

// 4. Filtrar Produtos Baratos
let precos = [15.50, 8.00, 25.00, 4.99, 12.75];
let baratos = precos.filter(preco => preco < 10);
console.log(baratos);

// 5. Contagem Regressiva (OBS)
for (let i = 5; i >= 1; i--) {
    console.log(i);
}

// 6. Nomes Maiúculo
let frutas = ['MARÇÃ', 'BANANA', 'CEREJA'];
let frutasMaiuscula = frutas.map(fruta => fruta.toUpperCase());
console.log(frutasMaiuscula);

// 7. Mostrar Detalhes de Alunos
let alunos = [{ nome: 'Pedro', idade: 10 }, { nome: 'Maria', idade: 11 }];
alunos.forEach(aluno => {
    console.log(`nome: ${aluno.nome}, Idade: ${aluno.idade} alunos.`);
});

// 8. Obter Números Maiores que 50
let pontuacoes = [45, 60, 30, 75, 50, 82];
let maioresQue50 = pontuacoes.filter(p => p > 50);
console.log(maioresQue50);

// 9. Acessar Elementos por Índice
let cores = ['vermelho', 'azul', 'verde', 'amarelo'];
for (let i = 0; i < cores.length; i++) {
    if (i === 2) {
        console.log(cores[i]);
    }
}

// 10. Somar Preços de Produtos
let itens = [
    { nome: 'Lápis', preco: 2.00 }, 
    { nome: 'Caderno', preco: 15.00 },
    { nome: 'Borracha', preco: 1.50 }
];

let soma = 0;
itens.forEach(item => {
    soma += item.preco;
});

console.log(`Total: R$ ${soma.toFixed(2)}`);
