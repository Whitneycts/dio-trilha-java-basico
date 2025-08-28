# Desafio POO - iPhone

Este projeto implementa um sistema de iPhone usando Programação Orientada a Objetos com interfaces e implementação de múltiplas funcionalidades.

## Funcionalidades

O iPhone implementa três interfaces principais:

### 1. ReprodutorMusical
- `tocar()` - Reproduz música
- `pausar()` - Pausa a reprodução
- `selecionarMusica(String musica)` - Seleciona uma música específica

### 2. AparelhoTelefonico
- `ligar(String numero)` - Faz uma ligação para um número
- `atender()` - Atende uma chamada recebida
- `iniciarCorreioVoz()` - Inicia o correio de voz

### 3. NavegadorInternet
- `exibirPagina(String url)` - Exibe uma página web
- `adicionarNovaAba()` - Abre uma nova aba no navegador
- `atualizarPagina()` - Atualiza a página atual

## Estrutura do Projeto

- `ReprodutorMusical.java` - Interface para funcionalidades de música
- `AparelhoTelefonico.java` - Interface para funcionalidades de telefone
- `NavegadorInternet.java` - Interface para funcionalidades de navegação
- `iPhone.java` - Classe principal que implementa todas as interfaces
- `Main.java` - Classe principal para testar as funcionalidades

## Como Executar

1. Compile o projeto:
   ```
   javac -d bin src/*.java
   ```

2. Execute a classe Main:
   ```
   java -cp bin Main
   ```

## Exemplo de Saída

```
Selecionando a música: Imagine - John Lennon
Reproduzindo música...
Música pausada.
Ligando para: 11987654321
Atendendo ligação...
Iniciando correio de voz...
Exibindo página: https://www.dio.me
Nova aba aberta no navegador.
Página atualizada.
```

## Conceitos POO Aplicados

- **Interfaces**: Definem contratos para implementação
- **Implementação Múltipla**: Uma classe pode implementar várias interfaces
- **Polimorfismo**: Uso de interfaces para referenciar objetos
- **Encapsulamento**: Métodos públicos para interação com o objeto
