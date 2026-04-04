# Requirements Engineering Process

Developing the requirements for ServiceHub AI required careful consideration of multiple stakeholders with different priorities. Customers primarily expect an easy-to-use platform that allows them to quickly discover reliable service providers and book services without complications. On the other hand, service providers are concerned with gaining visibility, managing bookings efficiently, and receiving timely payments.

One of the main challenges encountered during the requirements elicitation process was balancing the needs of different stakeholders. For example, customers expect instant booking confirmations and notifications, while the IT operations team must ensure that the system remains scalable and performs efficiently under heavy usage.

Another challenge involved defining requirements that were specific and measurable rather than vague statements. Instead of simply stating that the system should be “fast,” measurable performance targets such as response times and system uptime were defined.

This process highlighted the importance of structured requirements engineering in software development. By clearly identifying stakeholder concerns and translating them into functional and non-functional requirements, the system design becomes more aligned with real-world user needs.

# Use Case and Test Design

The transition from system requirements to use case modeling required careful analysis to ensure that all functional requirements were accurately represented as user interactions. One of the main challenges encountered was maintaining consistency between the requirements defined in the previous assignment and the newly developed use cases.

Each use case had to clearly reflect a real-world interaction between the user and the system. For example, the “Book Service” use case was directly derived from the functional requirement related to booking management. Ensuring traceability between requirements and use cases was essential to maintain coherence across the project.

Another challenge was identifying appropriate alternative flows. In real-world systems, failures such as payment errors or unavailable services are common. Incorporating these scenarios required thinking beyond the ideal workflow and considering possible exceptions.

Developing test cases also required translating requirements into measurable validation steps. Functional test cases were designed to verify system features such as user registration, booking, and payment processing. Non-functional test cases focused on performance and security, ensuring that the system can handle concurrent users and protect sensitive data.

Balancing simplicity and completeness was another important aspect. While it was necessary to keep the diagrams and specifications clear and understandable, they also needed to be detailed enough to demonstrate a full understanding of system behavior.

Overall, this process highlighted the importance of structured design in software engineering. By systematically converting requirements into use cases and test cases, the system becomes easier to validate, implement, and maintain.


# Agile Planning Process

The transition from structured requirements and use case modeling to Agile planning introduced a different way of thinking about system development. Instead of focusing on the system as a whole, the process required breaking down features into smaller, incremental units known as user stories.

One of the main challenges encountered was prioritization. As a single developer acting in multiple roles, it was difficult to balance technical complexity with user value. For example, while implementing AI-based recommendations would significantly enhance the system, it was not essential for the minimum viable product. This required making deliberate trade-offs to focus on core functionalities such as user authentication, service search, and booking.

Another challenge was effort estimation. Assigning story points required careful judgment, especially when considering dependencies between tasks. For instance, the booking functionality depends on both user authentication and service availability, making it more complex than it initially appears. Estimating these dependencies accurately was important to ensure realistic sprint planning.

Maintaining traceability across assignments also required attention. Each user story had to align with previously defined functional requirements and use cases. This ensured consistency in the system design and demonstrated a structured development approach.

Additionally, working individually highlighted the importance of self-discipline and time management. Without a team to distribute tasks, it was necessary to carefully plan workload and ensure that each sprint goal remained achievable within the given timeframe.

Overall, this process emphasized the importance of Agile methodologies in modern software development. By focusing on incremental delivery and continuous prioritization, the system becomes more adaptable to change while still meeting stakeholder needs. The experience also reinforced the value of structured planning in delivering a functional and scalable system.


