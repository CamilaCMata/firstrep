# Jogo do Número Secreto

Projeto desenvolvido para praticar os fundamentos de JavaScript, HTML e CSS por meio da criação de um jogo interativo de adivinhação.

O objetivo é descobrir um número secreto gerado aleatoriamente entre **1 e 100**, recebendo dicas durante as tentativas até acertar o valor.

## Demonstração

Ao iniciar o jogo, o usuário deve escolher um número entre **1 e 100**.

Após cada tentativa, o sistema informa se o número secreto é **maior** ou **menor** que o valor digitado. Quando o jogador acerta, o jogo informa a quantidade de tentativas utilizadas e habilita o botão para iniciar uma nova partida.

## Funcionalidades

* Geração aleatória do número secreto;
* Validação das tentativas do jogador;
* Dicas indicando se o número secreto é maior ou menor;
* Contagem do número de tentativas;
* Reinício da partida sem recarregar a página;
* Leitura das mensagens por voz utilizando a biblioteca ResponsiveVoice;
* Interface simples e responsiva.

## Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript (ES6+)
* ResponsiveVoice (síntese de voz)
* Google Fonts

## Estrutura do projeto

```text
numero-secreto/
│
├── index.html          # Estrutura da página
├── style.css           # Estilos da aplicação
├── app.js              # Lógica do jogo
├── img/
│   └── ia.png          # Imagem utilizada na interface
└── README.md
```

## Como executar o projeto

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/numero-secreto.git
```

2. Acesse a pasta do projeto:

```bash
cd numero-secreto
```

3. Abra o arquivo `index.html` em qualquer navegador moderno.

Não é necessário instalar dependências ou utilizar servidor local.

## Como jogar

1. Digite um número entre **1 e 100**.
2. Clique em **Chutar**.
3. Leia a dica apresentada:

   * O número secreto é maior;
   * O número secreto é menor.
4. Continue tentando até acertar.
5. Ao vencer, clique em **Novo jogo** para iniciar outra partida.

## Aprendizados

Durante o desenvolvimento deste projeto foram praticados conceitos como:

* Manipulação do DOM;
* Eventos em JavaScript;
* Estruturas condicionais;
* Laços de repetição;
* Funções;
* Variáveis e constantes;
* Geração de números aleatórios;
* Atualização dinâmica da interface;
* Integração com bibliotecas externas.

## Melhorias futuras

* Definir níveis de dificuldade;
* Permitir ao usuário escolher o intervalo de números;
* Criar sistema de pontuação;
* Implementar ranking de jogadores;
* Adicionar cronômetro;
* Salvar recordes utilizando Local Storage;
* Melhorar a acessibilidade da interface.

## Autores

Desenvolvido pelos professores da Alura https://cursos.alura.com.br/classpage/git-github-compartilhando-colaborando-projetos/task/139789
Editado por **Camila da Mata** como projeto de estudos em Git e GitHub.

---

Projeto criado para fins educacionais.

Guia rápido de edição em Markdown: https://wordpress.com/support/markdown-quick-reference/
