# 🐾 Cafofo dos Peludos

Site institucional de uma ONG fictícia de adoção de animais, desenvolvido para divulgar o trabalho de resgate, cuidado e adoção responsável de pets, além de conectar interessados em adotar, ajudar ou se voluntariar com a causa animal.

## 📖 Sobre o projeto

O **Cafofo dos Peludos** tem como objetivo apresentar o trabalho de uma ONG de proteção animal e facilitar a conexão entre animais resgatados e novas famílias. O site reúne informações institucionais, listagem de pets disponíveis para adoção, formulários de interesse, cadastro de voluntários/parceiros e uma seção de dúvidas frequentes.

## ✨ Funcionalidades

- **Página inicial** com carrossel de imagens, apresentação da ONG e vídeo explicando a importância da adoção.
- **Quero adotar**: listagem dos animais disponíveis para adoção.
- **Formulário de adoção**: coleta de dados do interessado em adotar, com página de confirmação do pedido.
- **Adicionar pet**: formulário para cadastro de novos animais para adoção.
- **Seja voluntário / Seja parceiro**: formulários para quem deseja colaborar com a ONG, com página de confirmação de inscrição.
- **FAQ**: respostas para as dúvidas mais comuns sobre como ajudar.
- **ONGs parceiras** e **Projetos sociais**: links externos para outras iniciativas de proteção animal.

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3** (folhas de estilo próprias por página/seção)
- **Bootstrap 4.1.3** (layout responsivo, navbar, carrossel, botões)
- **jQuery 3.3.1** e **Popper.js** (dependências do Bootstrap)
- **Vanilla-Tilt.js** (efeito de inclinação 3D nos cards)
- **Google Fonts** (fonte Baloo)

Todas as bibliotecas externas são carregadas via CDN, não sendo necessária instalação de dependências.

## 📁 Estrutura do projeto

```
CafofoDosPeludos1/
├── index.html          # Página inicial
├── pag1.html           # Listagem de pets para adoção
├── addPet.html         # Cadastro de novo pet
├── declaracao.html     # Formulário de interesse em adoção
├── form1.html           # Formulário de adoção
├── form2.html           # Formulário adicional
├── fim.html             # Confirmação do pedido de adoção
├── fim2.html            # Confirmação de inscrição (voluntário/parceiro)
├── sejaV.html           # Formulário para se tornar voluntário
├── qParceiro.html        # Formulário/confirmação para parceiros
├── faq.html              # Perguntas frequentes
├── html/                 # Páginas e formulários auxiliares
├── CSS/                  # Estilos específicos de cada página
└── img/                   # Imagens, logos e banners do site
```

## 🚀 Como executar

Por ser um site estático (HTML/CSS puro), não é necessário nenhum servidor ou build:

1. Baixe ou clone este repositório.
2. Acesse a pasta `CafofoDosPeludos1`.
3. Abra o arquivo `index.html` diretamente no navegador de sua preferência.

Opcionalmente, você pode servir os arquivos com um servidor local simples, por exemplo:

```bash
cd CafofoDosPeludos1
python3 -m http.server 8000
```

E acessar em `http://localhost:8000`.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request* com melhorias de layout, acessibilidade ou novas funcionalidades.

## 📄 Licença

Projeto de caráter acadêmico/demonstrativo. Consulte o autor do repositório para informações sobre uso e reaproveitamento do código.
