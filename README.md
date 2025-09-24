# Banco API Tests  

## 📌 Objetivo  
Este projeto tem como objetivo automatizar os testes da [Banco API](https://github.com/juliodelimas/banco-api), contribuindo com a qualidade e o correto funcionamento de seus endpoints REST.  

## 🛠️ Stack utilizada  
- [JavaScript (Node.js)](https://nodejs.org/)  
- [Mocha](https://mochajs.org/) – Estrutura de testes  
- [Chai](https://www.chaijs.com/) – Biblioteca de asserções  
- [Supertest](https://github.com/ladjs/supertest) – Testes de API HTTP  
- [Mochawesome](https://www.npmjs.com/package/mochawesome) – Geração de relatórios em HTML  
- Outras dependências listadas no [package.json](./package.json)  

## 📂 Estrutura de diretórios  
```bash
banco-api-tests/
│── test/               # Diretório com os arquivos de testes
│── mochawesome-report/ # Relatórios em HTML (gerados após execução)
│── .env                # Configuração de variáveis de ambiente (não versionado)
│── package.json        # Dependências e scripts do projeto
```

## ⚙️ Arquivo `.env`  
É necessário criar um arquivo `.env` na raiz do projeto com a seguinte variável:  

```env
BASE_URL=http://localhost:3000
```

> O valor pode ser alterado de acordo com a URL da API em execução.  

## ▶️ Como executar os testes  

1. **Instalar dependências**  
```bash
npm install
```

2. **Executar os testes**  
```bash
npm test
```

3. **Gerar relatório HTML (Mochawesome)**  
Após rodar os testes, o relatório será gerado automaticamente no diretório:  

```bash
./mochawesome-report/mochawesome.html
```

Abra o arquivo no navegador para visualizar os resultados.  

## 📚 Documentação das dependências  
- [Mocha](https://mochajs.org/)  
- [Chai](https://www.chaijs.com/)  
- [Supertest](https://github.com/ladjs/supertest)  
- [Mochawesome](https://www.npmjs.com/package/mochawesome)  
