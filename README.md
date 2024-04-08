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

## 📁 Repository Structure

- **`/docs`**: The primary directory containing all documentation for the workshop.
  - **`1_ThePlatform`**: Documentation related to the foundational concepts of platforms.
  - **`2_PlatformOpportunities`**: Insights into the opportunities platforms provide for business and development.
  - **`3_TeamTopologies`**: Materials on organizing team structures for optimal collaboration and efficiency.
  - **`4_DeveloperProductivityEngineering`**: Documentation on practices and tools to enhance developer productivity.
  - **`5_PlatformTeam`**: Guidelines for assembling and managing an effective platform team.
  - **`6_NetworkEffects`**: Exploration of network effects and their significance in platform dynamics.
  - **`7_BehaviorDesign`**: Information on influencing and designing user behavior within platforms.
  - **`/images`**: Visual resources to supplement the documentation.
  - **`README.md`**: General information and guidance for navigating the documentation.

- **`/changelogs`**: Logs detailing changes made to the project, including backlogs and release notes.

The Platform Engineering workshop modules are designed using **Docsify**. Documentations are written in Markdown and served using the Docsify CLI. Store the documentation for each module in the `docs/<module_number>` directory.

## 📘 What is Docsify?

Docsify is a lightweight tool designed for creating beautiful documentation websites directly from Markdown files. Unlike some static site generators, Docsify doesn't require the pre-compilation of your Markdown into HTML. Instead, it dynamically renders your site's content on the fly as the page loads, offering speed and agility in documentation delivery. With its support for a wide range of plugins and themes, Docsify provides a flexible and straightforward approach to crafting interactive and user-friendly documentation.

### 🔍 Prerequisites

1. Ensure [Node.js](https://nodejs.org/) is installed on your system, as it comes with npm (Node Package Manager), which is essential for installing Docsify.

### Installing Docsify CLI

1. To install the Docsify CLI, if you haven't already, use npm with the following command:

    ```bash
    npm install -g docsify-cli
    ```

2. To serve your documentation, execute:

    ```bash
    docsify serve docs
    ```

    This command launches a local server, typically accessible at <http://localhost:3000>. Visit this URL in your web browser to view your documentation live.

3. Accessing Your Live Documentation

**With the Docsify server running as instructed above, your live documentation is available by navigating to the provided local URL (usually <http://localhost:3000>).**

### 🛠️ Tips

Refresh your browser to view updated content anytime you make changes to the documentation files.

Customize the look and functionality of your Docsify site by modifying the index.html file located at the root of your documentation directory. Docsify offers numerous customization options to enhance your documentation experience.

### 📜 Configurations and Customizations:

For specific settings, customizations, or to incorporate plugins, themes, etc., you can do so by editing the index.html file at the root of your documentation directory.

🧠 Remember, Docsify dynamically loads content, eliminating the need for recompilation or rebuilding with each change. A simple browser refresh is all it takes!

### 🤝 Contributing

If you're interested in contributing to this documentation, feel free to fork the repository, make your changes, and submit a pull request.

### 📬 Contact

For questions or feedback, please reach out to Gabriel Sampaio at <gsampaio@redhat.com>.
