# 🧩 Microsserviço Serverless para Validação de CPF

Projeto desenvolvido como desafio da DIO (Digital Innovation One).

Este projeto consiste em um microsserviço serverless responsável por validar números de CPF, informando se o CPF é válido ou inválido.

---

## 🚀 Tecnologias
- Node.js
- Azure Functions
- HTTP Trigger

---

## 📌 Descrição
Este microsserviço recebe um número de CPF via **query string** ou **body da requisição**, realiza a validação dos dígitos verificadores e retorna um JSON informando se o CPF é válido.

---

## 📥 Exemplo de Entrada
### Solicitação POST
{
  "cpf": "12345678909"
}
### Requisição GET
https://SEU-ENDPOINT.azurewebsites.net/api/ValidateCPF?cpf=12345678909
