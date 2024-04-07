# Platform Engineering Workshop

This workshop is designed for anyone looking to enhance their skills in product design and the development of internal development platforms, while understanding the critical dynamics of effective team collaboration. Participants will be immersed in activities ranging from deep customer needs discovery to user journey mapping and the development of strategic product roadmaps. Through practical and collaborative techniques such as 'Design the Box', 'Event Storming', and 'User Story Mapping', participants will learn to effectively apply concepts in the design of internal products.

Furthermore, the workshop will incorporate essential elements of Team Topologies, emphasizing the importance of effective team structuring and inter-functional collaboration. Participants will explore how different team configurations can impact product development and solution delivery, enhancing their understanding of how to create teams aligned with business needs and design requirements.

## Objectives

- **Understand Fundamental Concepts**: Grasp the fundamental concepts and the importance of Platform Engineering in modern product and service development.
- **Trends Overview**: Gain an overview of current trends and how they affect the creation and management of internal platforms.
- **Deep Customer Needs Discovery**: Learn methods for deep customer needs discovery, including surveys, interviews, and feedback analysis.
- **User Journey Mapping**: Utilize tools and techniques for user journey mapping, identifying pain points and opportunities for improvement.
- **Team Topologies Principles**: Understand the principles of Team Topologies for effective team formation, focusing on types of teams, interactions, and responsibilities.
- **Enhance Inter-functional Collaboration**: Strategize to improve inter-functional collaboration and communication within and between teams.
- **Practical Team Configurations**: Analyze practical examples of successful team configurations in different organizational contexts.
- **Strategic Roadmap Development**: Develop strategic roadmaps for internal platforms, aligning product initiatives with business objectives.
- **Stakeholder Expectation Management**: Techniques for managing stakeholder expectations and communicating progress and changes effectively.
- **Iterative Product Launch**: Approaches for the iterative launch of products, including MVPs (Minimum Viable Products) and prototyping.
- **Post-launch Feedback Analysis**: Strategies for collecting and analyzing post-launch feedback, using data to inform future iterations.
- **Case Study Analysis**: Analyze case studies of companies that have successfully implemented Platform Engineering practices.

This workshop is ideal for participants looking to leverage practical and collaborative techniques to advance in the field of product design and platform engineering, fostering an innovative and efficient development environment.

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
