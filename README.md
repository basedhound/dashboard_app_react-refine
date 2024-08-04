<div align="center">
    <a href="https://dashboard-refine-fv.netlify.app" target="_blank">
      <img src="public/design/preview.gif" alt="Project Banner">
    </a>
  <h3 align="center">Dashboard React/Refine</h3>
</div>

##  <br /> 📋 <a name="table">Table of Contents</a>

- ✨ [Introduction](#introduction)
- ⚙️ [Tech Stack](#tech-stack)
- 📝 [Features](#features)
- 🚀 [Quick Start](#quick-start)

##  <br /> <a name="introduction">✨ Introduction</a>

**[EN]** React-based internal tools, admin panels, dashboards, B2B apps with flexibility in mind.
An open-source, headless React meta-framework, developed with a commitment to best practices, flexibility, minimal tech debt, and team alignment, could be a perfect fit for dynamic environments.

**[FR]** Applications internes, panneaux d'administration, tableaux de bord et applications B2B basés sur React, conçus pour offrir une grande flexibilité. Développé selon les meilleures pratiques, favorisant la flexibilité, minimisant la dette technique et favorisant l'alignement d'équipe, idéal pour les environnements dynamiques.

##  <br /> <a name="tech-stack">⚙️ Tech Stack</a>

- **React** is a popular JavaScript library for building user interfaces, particularly single-page applications where data changes over time. React's component-based architecture allows developers to create reusable UI components, making development more efficient and the codebase easier to maintain. Its virtual DOM enhances performance by minimizing direct interactions with the browser's DOM.

- **Refine** is a powerful open-source React meta-framework that streamlines development workflows for enterprise applications, providing efficient data handling, authentication, and access control mechanisms. It simplifies complex tasks and promotes best practices, enhancing productivity and scalability in dynamic environments.

- **GraphQL** is a query language for APIs that enables efficient data fetching and manipulation. It offers a flexible and powerful approach to data querying, allowing clients to request only the data they need. GraphQL's schema-based system and strong typing ensure robust and predictable API development, enhancing performance and developer productivity.

- **TypeScript** is a statically typed superset of JavaScript that allows for early detection of errors and more robust, maintainable code. TypeScript's type system helps developers catch mistakes early during the development process, ensuring a more stable and reliable application.

- **Ant Design** is a comprehensive UI component library for React that offers a wide range of customizable and well-designed components. It provides a unified design language and efficient development patterns, promoting consistency and usability across applications. Ant Design's modular architecture and extensive documentation make it a preferred choice for building elegant and responsive user interfaces.

- **Codegen** automates the generation of code from a GraphQL schema, facilitating the creation of type-safe APIs and reducing manual coding errors. It speeds up development by generating TypeScript typings, queries, mutations, and data access layers based on GraphQL operations, ensuring consistency and reliability in frontend-backend communication.

- **Vite** is a modern frontend build tool known for fast ES Module imports, efficient bundling, and quick development server startup times. It supports frameworks like Vue.js and React, optimizing workflow and performance compared to traditional bundlers.

## <br/> <a name="features">📝 Features</a>

👉 **Authentication**: Seamless onboarding with secure login and signup functionalities; robust password recovery ensures a smooth authentication experience.

👉 **Authorization**: Granular access control regulates user actions, maintaining data security and user permissions.

👉 **Home Page**: Dynamic home page showcases interactive charts for key metrics; real-time updates on activities, upcoming events, and a deals chart for business insights.

👉 **Companies Page**: Complete CRUD for company management and sales processes; detailed profiles with add/edit functions, associated contacts/leads, pagination, and field-specific search.

👉 **Kanban Board**: Collaborative board with real-time task updates; customization options include due dates, markdown descriptions, and multi-assignees, dynamically shifting tasks across dashboards.

👉 **Account Settings**: Personalized user account settings for profile management; streamlined configuration options for a tailored application experience.

👉 **Responsive**: Full responsiveness across devices for consistent user experience; fluid design adapts seamlessly to various screen sizes, ensuring accessibility.


## <br /> <a name="quick-start">🚀 Quick Start</a>

Follow these steps to set up the project locally on your machine.

<br/>**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

<br/>**Cloning the Repository**

```bash
git clone {git remote URL}
```

<br/>**Installation**

Let's install the project dependencies, from your terminal, run:

```bash
npm install
# or
yarn install
```

Or, to get the latest version from Refine, run:

```bash
npm create refine-app@latest -- --example app-crm-minimal
# or
yarn create refine-app@latest -- --example app-crm-minimal
```

<br/>**Running the Project**

Installation will take a minute or two, but once that's done, you should be able to run the following command:

```bash
npm run dev
# or
yarn dev
```

Open [`http://localhost:5173`](http://localhost:5173) in your browser to view the project.
