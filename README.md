# 🧑‍💼 Controle de Candidatos

Este projeto em Java simula um processo seletivo com foco em fluxos de controle, manipulação de exceções e interação com o usuário via terminal. Ele foi desenvolvido como parte de um exercício prático para consolidar conhecimentos em estruturas de repetição, condicionais e tratamento de erros.

## 📁 Estrutura do Projeto
controle-candidatos/ ├── src/ │   └── candidatura/ │       ├── Contador.java │       ├── ParametrosInvalidosException.java │       └── ProcessoSeletivo.java ├── .gitignore ├── controle-candidatos.iml


## 🚀 Funcionalidades

### ✅ Processo Seletivo (`ProcessoSeletivo.java`)
- Simula a análise de candidatos com base em salário pretendido.
- Seleciona candidatos com base em critérios definidos.
- Imprime lista de candidatos selecionados.
- Simula tentativas de contato com os candidatos.

### 🔢 Contador de Interações (`Contador.java`)
- Recebe dois números inteiros via terminal.
- Imprime uma sequência de interações com base na diferença entre os números.
- Lança exceção customizada (`ParametrosInvalidosException`) se o primeiro número for maior que o segundo.

### ⚠️ Exceção Customizada (`ParametrosInvalidosException.java`)
- Representa uma regra de negócio: o segundo parâmetro deve ser maior que o primeiro.

## 🛠️ Como Executar

1. Compile os arquivos Java:
   ```bash
   javac src/candidatura/*.java
   
2. Execute a classe desejada:
- Para o processo seletivo:
java candidatura.ProcessoSeletivo

- Para o contador:
java candidatura.Contador

📌 Exemplo de Uso
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18

Se o primeiro parâmetro for maior que o segundo:
Digite o primeiro parâmetro
30
Digite o segundo parâmetro
12
O segundo parâmetro deve ser maior que o primeiro


👨‍💻 Autor
Desenvolvido por Diego como parte de estudos em Java e lógica de programação.


