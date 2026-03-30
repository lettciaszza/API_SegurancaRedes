# WiFi Security API 🔐

API desenvolvida para análise de vulnerabilidades em redes Wi-Fi.

## Objetivo

Simular uma auditoria de segurança em redes sem fio, identificando possíveis vulnerabilidades com base em boas práticas de segurança da informação.

## Tecnologias

- Node.js
- Express
- API REST
- Segurança de redes

## Rotas

### Analisar rede

POST /wifi/analyze

Exemplo:

{
  "ssid": "Wifi Campus",
  "security": "WEP",
  "password": "12345678"
}

---

### Listar vulnerabilidades

GET /wifi/vulnerabilities

---

### Gerar relatório

GET /wifi/report

## Rodando o projeto

npm install

npm start

Servidor:

http://localhost:3000

## Autor

Leticia Souza