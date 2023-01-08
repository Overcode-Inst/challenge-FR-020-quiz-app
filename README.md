# 📋 Indíce

- [Proposta](#id01)
  - [O desafio](#id01.1)
  - [Requisitos](#id01.2)
    - [Requisitos funcionais ](#id01.2.1)
    - [Requisitos não funcionais ](#id01.2.2)
    - [Requisitos não obrigatórios](#id01.2.3)
- [Screenshots](#id02)
- [O que aprendi](#id03)
- [Mão a obra...](#id04)
- [Pré-requisitos](#id05)
- [Procedimentos de instalação](#id06)
- [Desafios similares e dicas ](#id07)
- [Autor](#id08)

# 🚀 Proposta <a name="id01"></a>

Assim como Linus Torvalds disse "Falar é fácil, me mostre o código". Nós desenvolvedores nunca vamos aprender a programar e desenvolver software sem efetivamente codar, é como tentar aprender a andar de bicicleta lendo livros e vendo vídeos.

E foi assim que essa abordagem nasceu, um roadmap baseado em projetos. A ideia em seu princípio é simples, essa é uma demanda, tente encarar como um desafio técnico e completá-lo em até 7 dias.

Ao completar, não esqueça de publicar no linkedin e adicionar #handsOnRoadmap

## :trophy: O desafio <a name="id01.1"></a>

<br />

Imagine que você foi contratado para desenvolver uma aplicação WEB para responder questionários de perguntas sobre conhecimentos gerais.

Ao acessar a página, o usuário deve escolher a quantidade de perguntas que deseja responder.

Após escolher, deve aparecer uma página com dois botões, “Start” e “Cancel”. Ao selecionar “Cancel”, deve retornar para escolher a quantidade. Ao selecionar “Start” deve fazer requisição na URL disponibilizada, pegar as perguntas e a cada pergunta, deve exibir as respostas.

O usuário deve escolher uma resposta e a cada resposta deve contabilizar quantidade de acertos e erros. Ao final, deve vir um relatório com a quantidade de acertos e erros e uma lista de cada questão e qual foi certo e qual foi errado.

Nessa lista também deve aparecer a resposta escolhida e a resposta correta. A pontuação deve ser guardada em no localStorage. Na primeira página e se houver um questionário salvo no localStorage, deve ter a possibilidade de rever o relatório.

<br />

## :dart: Os requisitos<a name="id01.2"></a>

### :dart: Requisitos funcionais <a name="id01.2.1"></a>

<br />

Sua aplicação deve ter:

- permitir que usuário escolha a quantidade de questões que irá responder
- Permitir o usuário confirmar ou cancelar a escolha.
- Permitir o usuário responder uma pergunta por vez, ao responder lhe mostra se ele acertou ou errou.
- Deve ter um contador para quantidade de certas em relação ao número de questões escolhidos.
- Ao acabar as questões deve mostrar um resumo para o usuário, com todas questões que ele respondeu e se acertou ou errou.
- No menu home deve ficar disponível para acessar as tentativas anteriores.
- Deve ser possível limpar o histórico.

<br />

É obrigatório a utilização de:

### :dart: Requisitos não funcionais <a name="id01.2.2"></a>

<br />

É obrigatório a utilização de:

- ReactJs
- fazer deploy
- URL para gerar as questões através do link: https://opentdb.com/api.php?amount=QUANTIDADE.
- LocalStorage para armazenar dados
- Context API
- Axios
- Hooks
- Formik
- Yup
- sweetalert2-react-content para direcionamento de fluxo

<br />

### :pushpin: Requisitos não obrigatórios <a name="id01.2.3"></a>

<br />

Você será bem avaliado se usar:

<br />

- usar HTML semântico, como tags main, section...
- usar responsividade
- organizar e dividir bem os arquivos
- Componentizar e separar bem o que achar que deve
- Usar typeScript
- testes de comportamento
- demonstrar uma boa apresentação de design e uso de design patterns (como services, repositories, factories, builders e etc)
- tratamento para formatação da resposta da api de base 64 para unicode
- paradigma funcional e poo

<br />

# :camera_flash: Screenshots <a name="id02"></a>

<br />

## :iphone: Mobile design

## :iphone: Tablets design

## :desktop_computer: Desktop design

# :heavy_check_mark: O que aprendi <a name="id03"></a>

# 🛠 Mão a obra... <a name="id04"></a>

Você pode forkar esse projeto e reutilizar o readme e estrutura, mas também se sinta livre para mudar ela ou mesmo criar a sua.

# ☑️ Pré-requisitos para rodar <a name="id05"></a>

<br />

- [x] Editor de código de sua preferência (recomendado VS code)
- [x] Git
- [x] ?

<br />

# 📝 Procedimentos de instalação <a name="id06"></a>

<br />

Clone este repositório usando o comando:

```bash
git clone https://github.com/<meu_user>/<my-repo>.git
```

```bash
#processos adicionais aqui
```

<br />

# 👨🏾‍💻 Desafios similares e dicas <a name="id07"></a>

Antes ou depois de realizar esse desafio, você pode pegar desafios parecidos do front-end mentor ou similares. Isso te ajuda a fixar e melhorar. Vou deixar alguns a seguir, pode te ajudar a se inspirar.

O segredo aqui é fazer modelos parecidos até ganhar algum conforto com fazer algo com essas técnicas e esse modelo de desafio, então quem sabe pegar outros mais difíceis.

Você também pode usar o dribbble para se inspirar.

[Dribbble](https://dribbble.com)

# :sunglasses: Autor <a name="id08"></a>

<br />

- Linkedin - [Jean Carlos De Meira](https://www.linkedin.com/in/jeanmeira/)
- Instagram - [@jean.meira10](https://www.instagram.com/jean.meira10/)
- GitHub - [JCDMeira](https://github.com/JCDMeira)
