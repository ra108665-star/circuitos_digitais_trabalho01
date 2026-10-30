# Trabalho 1 de Circuitos digitais

O trabalho compreende o desenvolvimento e simulação do projeto de circuito combinacional: ULA de 1 bit
(Unidade Lógica e Aritmética de 1 bit

# ULA 1 Bit

## Comparador Diferente

* Operação: 000
* Entradas: A, B, C, D
* Saídas: S
* AB e CD são palavras binárias
* S = 1, quando AB ≠ CD

## Compador Maior Menor

* Operação: 001
* Entradas: A, B, C, D
* Saídas: S
* S = 1, quando A > C && B < D

## Comparador Menor Igual

* Operação: 010
* Entradas: A, B, C, D
* Saídas: S
* AB e CD são palavras binárias
* S = 1, quando AB <= CD

## Comparador Igual

* Operação: 011
* Entradas: A, B, C, D
* Saídas: S
* S = 1, quando A = C && B = D

## Gerador Paridade

* Operação: 100
* Entradas: A, B, C, D
* Saídas: S
* S = 1, quando o número de '1's é ímpar

## Verificador Paridade

* Operação: 101
* Entradas: A, B, C, D, P
* Saídas: S
* S = 1, quando P tem a mesma paridade que o nº de portas ativas, ou seja, S = 1
quando P = 0 e o nº de portas em 1 é par e quando P = 1 e o nº de portas em 1 é
ímpar.
* Obs: P não entra na contagem de portas em 1.

## Somador/Subtrator Parcial

* Operação: 110
* Entradas: A, B, C
* Saídas: S, Cout
* C alterna entre somador e subtrator

## Somador/Subtrator Completo

* Operação: 111
* Entradas: A, B, C, D
* Saídas: S, Cout
* D alterna entre somador e subtrator
* C faz o papel de Cin, *carry in* 
