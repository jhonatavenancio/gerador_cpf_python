# Gerador de CPFs Válidos em Python

Este é um script em Python que gera CPFs válidos aleatórios. O CPF (Cadastro de Pessoa Física) é um documento de identificação fiscal no Brasil, composto por 11 dígitos. Este script utiliza o algoritmo de geração de dígitos verificadores para garantir que os CPFs gerados sejam válidos.

## Como Funciona

O script gera CPFs válidos aleatórios utilizando o algoritmo de geração de CPF. Aqui está uma explicação passo a passo do processo:

1. Um loop é usado para gerar 1000 CPFs.
2. Para cada CPF, nove dígitos são gerados aleatoriamente.
3. O primeiro dígito verificador é calculado com base nos primeiros nove dígitos.
4. O segundo dígito verificador é calculado com base nos primeiros nove dígitos e no primeiro dígito verificador.
5. O CPF completo, incluindo os dígitos verificadores, é então validado e impresso na saída padrão.

## Como Usar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Copie e cole o código em um arquivo Python.
3. Execute o arquivo Python.

```bash
python gerador_cpf.py
```

## Exemplo de Saída

A saída do script será uma lista de CPFs válidos gerados aleatoriamente, um por linha.

```
12345678910
23456789101
34567891012
...
```
