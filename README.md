let energia = 50;
let reciclagem = 50;
let transporte = 50;
let agua = 50;

function atualizarCidade(){

let score = Math.floor(
(energia + reciclagem + transporte + agua) / 4
);

document.getElementById("energia").textContent = energia;
document.getElementById("reciclagem").textContent = reciclagem;
document.getElementById("transporte").textContent = transporte;
document.getElementById("agua").textContent = agua;

document.getElementById("score").textContent = score;

let mensagem = "Sua cidade está em desenvolvimento sustentável.";

if(score >= 70){
mensagem = "🌱 Boa gestão! Sua cidade está ficando sustentável.";
}

if(score >= 90){
mensagem = "🏆 Parabéns! Sua cidade é referência em sustentabilidade.";
}

document.getElementById("resultado").textContent = mensagem;
}

function melhorarEnergia(){
if(energia < 100){
energia += 10;
atualizarCidade();
}
}

function melhorarReciclagem(){
if(reciclagem < 100){
reciclagem += 10;
atualizarCidade();
}
}

function melhorarTransporte(){
if(transporte < 100){
transporte += 10;
atualizarCidade();
}
}

function melhorarAgua(){
if(agua < 100){
agua += 10;
atualizarCidade();
}
}

atualizarCidade();
# 🏙️ Cidade Sustentável

Projeto desenvolvido para o Programa Agrinho.

## Objetivo

O jogador administra uma cidade e toma decisões para melhorar:

- Energia
- Reciclagem
- Transporte
- Água

Cada ação aumenta os indicadores ambientais e melhora a pontuação geral da cidade.

## Tecnologias

- HTML5
- CSS3
- JavaScript

## Funcionalidades

✅ Sistema de pontuação

✅ Gestão sustentável

✅ Tomada de decisões

✅ Indicadores ambientais

✅ Interface responsiva

## Como jogar

1. Clique nos botões de melhoria.
2. Aumente os níveis ambientais.
3. Alcance 100 pontos de sustentabilidade.

## Autor

ISABELY GARRIDO