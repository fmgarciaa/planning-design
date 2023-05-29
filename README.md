# Planning & Design

Here's the translation: "In this repository, a series of steps are developed for the planning and development of software projects, but they can be applied to any project. Each step has a brief explanation and what is sought through it. Likewise, examples will be provided on how the deliverables should be for each step. I hope it's helpful! Happy Hacking!

## Planning & Design Tree

  1. Requirements
  2. Design Document
    2.1. Document Creation
    2.2. Document Review
  3. Architecture Development
    3.1. High-Level Architecture
    3.2. Low-Level Architecture
  4. Continuous Integration Plan




## 1. Requirements

The "Requirements" step refers to the process of gathering, documenting, and understanding the needs and expectations for the project. This step involves identifying and defining the functional and non-functional requirements of the project.

In the requirements gathering step of a project, there are several recurring questions that commonly arise. These questions help to clarify the needs and expectations of the stakeholders and ensure that the requirements are properly understood and documented. Some of the common recurring questions include:

1. What problem or need does the project aim to address?
2. Who are the primary users or stakeholders of the project?
3. What are the main goals and objectives of the project project?
4. What functionalities and features should the project have?
5. Are there any specific performance, security, or scalability requirements?
6. What are the constraints and limitations that need to be considered?
7. Are there any regulatory or compliance requirements to be met?
8. What are the usability and user experience expectations?
9. Are there any integration or interoperability requirements with other systems?
10. What are the expected deliverables and milestones of the project?

These recurring questions help to ensure a clear understanding of the requirements and assist in documenting them accurately. Regular communication and collaboration with stakeholders throughout the process can help address any uncertainties and ensure that the requirements are properly captured.

In summary, requirements typically capture the desired features, functionalities, and constraints that the software should fulfill to meet the stakeholders' needs. This step helps ensure that the software development efforts align with the intended goals and objectives of the project.

[Template example](requirements_template.md)

## 2. Design Document
With the requirements already established for the project, we will now capture and document them in a design document, which will encompass all the necessary details we need to proceed with the development of the project. The design document will serve as a comprehensive reference, outlining the architecture, modules, interfaces, algorithms, and other pertinent information that will guide the implementation of the project. By documenting the requirements in the design document, we ensure that the development team has a clear understanding of the project's objectives and can effectively translate them into a robust and functional solution.

[Template example](design_doc_template.md)

### 2.1 Document Creation
In this step, the design document is created in a general and less specific manner, involving only a few members of the team. This approach allows for greater flexibility and adaptability.

By keeping the design document at a higher level of abstraction and involving a smaller group of individuals, it becomes easier to accommodate changes and adapt to evolving project requirements. The document focuses on capturing the overall architecture, key components, and essential design decisions, providing a broad framework for the development process.

### 2.2 Document Review
In this step, the design document is reviewed and refined with the entire team to establish clear paths for the project's development.

By involving the entire team in the review process, diverse perspectives and expertise are brought together to ensure that the design document aligns with the project's objectives and meets the required specifications. This collaborative effort helps identify any potential issues, gaps, or inconsistencies in the design, allowing for necessary adjustments and improvements.

During the review, team members provide feedback, suggestions, and insights to enhance the clarity, feasibility, and effectiveness of the design. Discussions and debates within the team help to establish a shared understanding of the project's direction, resolve any ambiguities, and clarify the roles and responsibilities of each team member.

Through this collaborative review process, the team collectively marks clear paths for how the project will be developed. It establishes consensus on the overall design approach, architectural decisions, module interactions, and any necessary trade-offs. This alignment within the team ensures that everyone has a shared vision and a common understanding of the project's implementation strategies.

By refining and polishing the design document in this collaborative manner, the team sets a solid foundation for the project's development phase. It helps minimize misunderstandings, reduces the risk of rework, and enables a smoother execution by providing clear guidelines and directions for the development team to follow.

## 3. Architecture Development
Architecture Development is the structure or conceptual framework that defines how different components of a system interact with each other and how they are organized to achieve the project's objectives.

During the development of the architecture, fundamental decisions are made regarding the system's structure, technology selection, distribution of responsibilities, communication between components, scalability, and other important aspects of software design. These decisions are based on project requirements, technical constraints, best practices, and the development team's expertise.

The development of the architecture involves creating diagrams and models that visually represent the system's structure and interactions, such as flowcharts, class diagrams, sequence diagrams, component diagrams, among others. These artifacts help communicate and document the architectural decisions, facilitating understanding and collaboration among team members.

### 3.1 High-Level Architecture
High-level architecture focuses on a general and abstract view of the system, without going into specific technical details. In this stage, the main components of the system, their interactions, and the overall structure are defined. Key architectural decisions are made, such as selecting architectural patterns, defining system layers, and identifying the main data flows. The diagrams and models used in high-level architecture are less detailed and focus on the overall structure and key elements of the system.

### 3.2 Low-Level Architecture
Low-level architecture deals with the specific technical implementation details. This is where detailed interfaces of the components are defined, algorithms are designed, and precise relationships between system modules are established. Aspects such as performance, security, scalability, and efficiency are taken into consideration. In low-level architecture, the diagrams and models are more detailed and specific, showcasing implementation details and finer interactions between components.

## 4. Continuous Integration Plan
The goal of a Continuous Integration plan is to ensure that changes made by developers smoothly merge with the existing code and are quickly verified to detect possible issues. This involves the automatic execution of software tests, code quality analysis, compilation, and artifact generation. Continuous Integration allows for early detection of errors and conflicts, facilitating rapid correction and improving software quality.

A Continuous Integration plan may include the following elements:

- Configuration of version control system and shared repository.
- Definition of Continuous Integration workflows and triggering events.
- Configuration of Continuous Integration tools and services such as Jenkins, Travis CI, or CircleCI.
- Specification of integration stages and tasks, such as compilation, unit testing, integration testing, static code analysis, among others.
- Configuration of notifications and alerts to report on the results of Continuous Integration.
- Establishment of quality criteria and thresholds for accepting or rejecting an integration.
- Definition of code branching and merging practices to ensure smooth integration.

In summary, a Continuous Integration plan is a strategy that defines how the process of Continuous Integration will be implemented and managed in a software project, with the goal of improving efficiency, quality, and collaboration in software development.
