# Lista de Estados e Municípios com código do IBGE

Este repositório reúne as listas de estados e municípios, de acordo com o IBGE, em vários formatos.

Esta lista foi gerada em maio de 2017.

No formato SQL, existe uma relação direta entre as tabelas de estados e município. Nos demais formatos, para fazer a relação entre estados e municípios, basta pegar os dois primeiros dígitos do cdigo do município, que se referem ao código do estado.

## SQL

Script SQL que cira as tabelas `uf` e `município`.

## PHP

Arquivo que traz um `Array` de estados e um de municípios, para ser copiado e colado em um script PHP.

## json

Arquivos com as listagens de estados e municípios no formato json, com a mesma estrutura de arrays dos arquivos PHP

## CSV

Arquivos .csv com listagens de estados e municípios
