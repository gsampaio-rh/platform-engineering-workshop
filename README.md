# Platform Engineering Workshop
Este repositório serve como o centro de documentação e recursos para o workshop de Platform Engineering, uma experiência abrangente e interativa destinada a explorar as profundezas e amplitudes da engenharia de plataforma em ambientes de TI modernos. Com um foco prático e aplicado, este workshop guia os participantes através de conceitos essenciais e práticas avançadas de Platform Engineering, destacando como essas estratégias podem ser implementadas para otimizar a entrega de software e melhorar a produtividade do desenvolvedor.

Cada componente do workshop foi cuidadosamente desenhado para não apenas transmitir conhecimento, mas também para incutir habilidades práticas e pensamento crítico, permitindo que os participantes apliquem o que aprenderam em seus próprios contextos de trabalho. Os facilitadores e participantes são encorajados a usar este repositório como um recurso vivo e dinâmico, contribuindo com suas próprias ideias e feedback para enriquecer ainda mais a experiência de aprendizado coletiva.

## 📁 Estrutura do Repositório

- **`/docs`**: Diretório principal com toda a documentação do workshop.
  - **`1_PlatformEngineering`**: Documentação relacionada ao módulo de Engenharia de Plataforma.
  - **`2_DeveloperProductivityEngineering`**: Documentação sobre Engenharia de Produtividade do Desenvolvedor.
  - **`3_Comportamento`**: Materiais sobre comportamento organizacional e mudança.
  - **`/desafios`**: Detalhes sobre os desafios específicos enfrentados durante o workshop.
  - **`/images`**: Recursos visuais para complementar a documentação e desafios.
  - **`_sidebar.md`**: Barra lateral de navegação para a documentação.
  - **`index.html`**: Arquivo HTML para visualização da documentação via Docsify.
  - **`README.md`**: Informações gerais e orientações para cada seção.

- **`/changelogs`**: Registros de alterações feitas no projeto, incluindo backlog e notas de lançamento.

Os módulos do workshop Platform Engineering são criados usando o **Docsify**. Escreva a documentação em Markdown e use o CLI do Docsify para servi-los. Armazene a documentação de cada módulo no diretório `docs/<numero-do-modulo>`.

## 📘 O que é o Docsify?
Docsify é uma ferramenta leve para gerar sites de documentação diretamente de arquivos markdown. Diferentemente de alguns outros geradores de sites estáticos, o Docsify não requer que você compile o markdown em HTML com antecedência. Em vez disso, ele gera dinamicamente o conteúdo do site quando a página é carregada, tornando-o bastante ágil. Com uma variedade de plugins e temas disponíveis, o Docsify oferece uma maneira flexível e fácil de criar documentação interativa e amigável.

### 🔍 Pré-requisitos:
1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado. Ele virá com o npm (gerenciador de pacotes do node) que é usado para instalar o Docsify.

### 1. Instale o Docsify CLI:
Se você ainda não instalou o Docsify CLI, pode fazê-lo usando o npm:

```bash
npm install -g docsify-cli
```

### 2. Inicialize e Sirva os Documentos:
Sirva os documentos:

```bash
docsify serve docs
```

Isso iniciará um servidor local, geralmente em http://localhost:3000. Abra este link no seu navegador para ver sua documentação.

### 3. Acessando a Documentação ao Vivo:
Depois de iniciar o servidor Docsify usando o comando acima, você pode acessar sua documentação ao vivo navegando para a URL local fornecida (normalmente http://localhost:3000).

#### 🛠️ Dicas:

- Sempre que fizer alterações nos arquivos de documentação, simplesmente atualize o navegador para ver o conteúdo atualizado.
- Você pode personalizar a aparência e funcionalidade do seu site Docsify editando o arquivo index.html na raiz do seu diretório de documentação. O Docsify oferece uma infinidade de opções para melhorar e personalizar sua experiência de documentação.

#### 📜 Configurações e Personalizações:
Se você precisar de configurações específicas, personalizações ou quiser adicionar plugins, temas, etc., pode fazê-lo editando o arquivo index.html na raiz do seu diretório de documentação.

🧠 Lembre-se, o Docsify carrega o conteúdo dinamicamente, então não há necessidade de recompilar ou reconstruir toda vez que você fizer alterações. Uma simples atualização do navegador resolverá!


## 🤝 Contribuindo

Se você deseja contribuir para esta documentação, sinta-se à vontade para fazer um fork, fazer suas alterações e enviar um pull request.

## 📬 Contato

Para quaisquer perguntas ou feedback, entre em contato com Gabriel Sampaio em gsampaio@redhat.com.
