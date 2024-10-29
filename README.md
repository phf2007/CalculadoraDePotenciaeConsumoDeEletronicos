# Calculadora de Potência e Consumo de Eletrônicos

> Um aplicativo Android simples que calcula o consumo de energia e o custo associado de diferentes aparelhos eletrônicos.

## 📱 Descrição

O **Calculadora de Potência e Consumo de Eletrônicos** permite ao usuário calcular o consumo de energia e o custo associado de diferentes aparelhos eletrônicos usando:
CE = Consumo de energia em quilowatts/hora
p = Potência
H = tempo de uso em horas (h)
C = Custo da energia
PKWH = Preço de energia por kW/h
  **e sua fórmula é:**
CE = P X H / 1000
C = CE X PKWH

## 🔧 Funcionalidades

- [x] 1 Tela que fará toda a conta
- [x] Um TextView abaixo do botão que exibe o resultado
- [x] Fórmula simples
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/CalculadoraDePotenciaeConsumoDeEletronicos
/Calculadoradeenergiig.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

MyApplication
├── app
│   ├── main
│   │   ├── java/com.example.myapplication
│   │   │   ├── MainActivity.java                  # Atividade principal onde está elaborado as fórmulas
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, teremos caixas de textos para inserir a potência, o tempo de uso em horas e o preço de energia por kW/h, abaixo disso terá um botão para calcular e abaixo do botão um TextView que exibe a resposta.

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
