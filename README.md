# BuildBoxDesafio
Projeto de automação de teste para a plataforma Burger Eats

## 🚀 Começando

### 📋 Pré-requisitos

O Cypress é um framework para automação de testes end-to-end, que utiliza o JavaScript como linguagem de programação. Para executar o código Java Scripy precisa-se instalar a ferramenta NodeJS.

```

### 🔧 Instalação

1) Abra uma janela do terminal em seu computador. Isso pode ser feito da seguinte forma:

Windows: Você pode acessar a busca no menu inicial e procurar por Prompt de Comando, ou acessar via Menu Iniciar > Sistema do Windows > Prompt de Comando.
MacOs: O Terminal está disponível no menu de Aplicações, dentro da pasta de Utilitários.
Linux (Ubuntu): O Terminal está disponível no menu de Programas/Aplicações. Caso não localize, pode estar dentro da pasta Utilitários.

2) No terminal, digite node --version ou node -v - caso retorne um número de versão, como por exemplo, v16.13.1, o NodeJS já está instalado.

Caso precise instalar, siga as instruções para cada sistema operacional que estão na página inicial do NodeJS . 

3) Para poder usar o Cypress, precisamos fazer a instalação do mesmo. Vamos usar o comando *npm i cypress --save-dev*. 


```


## ⚙️ Executando os testes

Primeiro devemos abrir o arquivo de teste **buger.cy.js** em uma IDE. Deve-se abrir um novo terminal e inserir o comando para rodar o teste: *npx cypress open*.

Agora para poder executar e ver a interface gráfica do Cypress, precisamos rodar o comando que vai abrir o script de teste. Para isso vamos digitar *npm run test*. 
![image](https://user-images.githubusercontent.com/60972875/187288615-6c5e11f0-396c-4903-b3ca-587b2dc91864.png)

Nessa tela você irá escolher **E2E Testing**, pois agora o Cypress também tem a opção de fazer testes de componentes, geralmente criados pelas pessoas desenvolvedoras front-end.

Em sequência, uma nova tela que mostra todos os navegadores instalados, para que você escolha qual irá utilizar inicialmente.

![image](https://user-images.githubusercontent.com/60972875/187289074-bfdebfd3-d5d6-4aaa-8ed0-a3741701292f.png)

Depois de selecionado, você vai marcar a opção **Start E2E Testing in (navegador escolhido)**.

O botão Specs demonstra todos os arquivos de teste do projeto. Um clique em um dos arquivos já executa o mesmo e mostra os outros na barra lateral esquerda, para serem executados também facilmente.


### 🔩 Relatórios de teste

Para rodar os testes sem abrir a interface gráfica, usaremos o comando *npx cypress run*. Esses testes vão ser executados em background, sem abrir nenhuma tela. Nesse momento, o cypress identifica quais testes estão sendo executados com sucesso, sem erro; nos mostra o tempo que levou para rodar todos os testes, e nós conseguimos ver os resultados. Além disso há o recurso de vídeo que é gerado, que nos mostra o que aconteceu, caso tenhamos dúvida sobre algum teste, possibilitando que façamos o playback dessa ação.

### Cenários de Teste
```

* Verificação de Mensagens de Validação em Campos obrigatórios
* Verificação de mensagem de CPF inválido
* Verificação de CEP inválido
* Confirmação de cadastro quando o mesmo for efetuado.

```

## 🛠️ Construído com

* [Cypress](https://www.cypress.io/) - O framework web usado


## ✒️ Autores


* **Geovana Paes** -  [QualityAssurance](https://github.com/GeovanaPaes)
