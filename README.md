# **AppPotencia (Calculadora de Potência e Consumo de Eletrônicos)**

> Um aplicativo Android desenvolvido para monitorar o consumo de potência elétrica.

## Descrição
O **AppPotencia** permite ao usuário monitorar e gerenciar o consumo de potência elétrica, fornecendo dados e estatísticas que ajudam na compreensão do uso de energia e na tomada de decisões informadas.

## Funcionalidades
- [x] Entrada de dados de consumo de potência
- [x] Cálculo e exibição de estatísticas de consumo energético
- [x] Gráficos interativos para visualização dos dados de consumo
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes unidades de medida (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   [https://github.com/Hacker19991/AppPotencia](https://github.com/Hacker19991/Calculadora-de-Pot-ncia-e-Consumo-de-Eletr-nicos-Android-Studio)

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projet

── app
 ├── src
 │ ├── main
 │ │ ├── java/com/example/apppotencia
 │ │ │ ├── MainActivity.java # Atividade principal para monitoramento de potência
 │ │ ├── res
 │ │ │ ├── layout
 │ │ │ │ ├── activity_main.xml # Layout da tela principal
 │ │ │ └── values
 │ │ │ ├── strings.xml # Strings usadas no app
 │ │ │ ├── colors.xml # Cores definidas no projeto
 └── build.gradle # Configuração do Gradle

 ## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/67e111a7-7f25-4737-9ea5-9326ecf70377)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 3 EditText para, Tempo de uso(h), Potencia do dispositivo(W), e o Preço de Energia(R$/kWh), um botão para processar a conta informada adequadamente,e no final o TextView para mostrar o resultado final do calculo com as informações insiridas de maneira certa.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
