# 🏦 Banco do Brazil com Z

Sistema bancário desenvolvido em **TypeScript** com interface de linha de comando (CLI), que simula operações essenciais de uma conta bancária.

---

## 📋 Funcionalidades

- ✅ Criar conta bancária
- ✅ Listar todas as contas
- ✅ Buscar conta por número
- ✅ Atualizar dados da conta
- ✅ Apagar conta
- ✅ Realizar saque
- ✅ Realizar depósito
- ✅ Transferência entre contas

---

## 🚀 Tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/)
- [readline-sync](https://www.npmjs.com/package/readline-sync) — leitura de input no terminal

---

## 📁 Estrutura do Projeto

```
conta_bancaria/
├── src/
│   └── util/
│       └── Colors.ts       # Utilitário para colorir o terminal
├── Menu.ts                 # Ponto de entrada — menu interativo
├── tsconfig.json
├── package.json
└── .gitignore
```

---

## ▶️ Como executar

### Pré-requisitos

- [Node.js](https://nodejs.org/) instalado
- [TypeScript](https://www.typescriptlang.org/) instalado globalmente

```bash
npm install -g typescript
```

### Instalação

```bash
# Clone o repositório
git clone https://github.com/BiaNascimento/conta_bancaria.git

# Acesse a pasta do projeto
cd conta_bancaria

# Instale as dependências
npm install
```

### Execução

```bash
# Compile o TypeScript
tsc

# Execute o programa
node Menu.js
```

---

## 💻 Preview

```
*****************************************************
                                                     
                BANCO DO BRAZIL COM Z                
                                                     
*****************************************************
                                                     
            1 - Criar Conta                          
            2 - Listar todas as Contas               
            3 - Buscar Conta por Numero              
            4 - Atualizar Dados da Conta             
            5 - Apagar Conta                         
            6 - Sacar                                
            7 - Depositar                            
            8 - Transferir valores entre Contas      
            9 - Sair                                 
                                                     
*****************************************************
```

---

## 👩‍💻 Autora

Desenvolvido por **Bianca Nascimento**

[![GitHub](https://img.shields.io/badge/GitHub-BiaNascimento-181717?style=flat&logo=github)](https://github.com/BiaNascimento)
[![Email](https://img.shields.io/badge/Email-biancanascimentodev%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:biancanascimentodev@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-bianca.gbworks.com.br-0A66C2?style=flat&logo=google-chrome&logoColor=white)](https://bianca.gbworks.com.br)
