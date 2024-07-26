# Need and System Specification

To effectively translate needs into actionable system requirements and detailed specifications, we must understand the hierarchy and iterative nature of the process, as well as the theories that guide information use and decision-making.

### Hierarchy of Needs, Requirements, and Specifications

1. **Needs**:
    - **Definition**: Needs are the high-level objectives or goals that users have. These are often broad and user-focused.
    - **Example**: Providers need to see a patient’s diagnosis when ordering medications.
2. **Requirements**:
    - **Definition**: Requirements translate needs into specific functionalities or conditions that the system must fulfill.
    - **Example**: The system should display the patient's problem list during the medication ordering process.
3. **Specifications**:
    - **Definition**: Specifications detail the technical aspects of how requirements will be implemented in the system.
    - **Example**: A specific screen in the electronic health record (EHR) system shall display the problem list in a designated field, with specific dimensions and color codes for visibility.

### Process of Elicitation and Specification

- **Iterative Nature**: Eliciting needs and translating them into requirements and specifications is iterative. Continuous feedback and adjustments are essential to ensure alignment with user expectations and practical feasibility.
- **Stakeholder Involvement**: Decision-makers, including domain experts and technologists, must collaborate to balance user needs with technical constraints and trade-offs.
- **Methods**:
    - **Interviews**: Direct conversations with users to understand their needs.
    - **Role-Playing**: Simulating scenarios to uncover implicit requirements.
    - **Prototyping**: Creating mock-ups or functional prototypes to visualize and refine requirements.

### Addressing Scope Creep

- **Scope Creep**: The gradual expansion of project scope due to additional features or requirements being added.
- **Mitigation**: Clearly define and document requirements early in the project. Use phrases like "shall," "should," and "could" to prioritize features and set clear boundaries. Consult with stakeholders to assess the impact of new requests on budget and timelines.

### Theories of Information Use and Decision-Making

1. **Don't Make Me Think**:
    - **Principle**: Systems should be intuitive and easy to use, minimizing the need for user effort to understand functionality.
    - **Example**: A simple, clear search engine interface.
2. **Berry Picking**:
    - **Principle**: Users gather information iteratively and non-linearly, like picking berries from different bushes.
    - **Example**: PubMed's citation saving feature for ongoing research.
3. **Sense Making**:
    - **Principle**: Users create mental models and narratives to understand information.
    - **Example**: Online health communities where users share stories and experiences.
4. **Cognitive Work Analysis**:
    - **Principle**: Focus on understanding how users perform their work to design supportive systems.
    - **Example**: Interviews or use case scenarios to elicit detailed work processes.

### Theories of Decision-Making

1. **Dual Process Theory**:
    - **Principle**: Decision-making involves both fast, intuitive (System 1) and slow, analytical (System 2) processes.
    - **Example**: A risk calculator that quickly highlights high-risk areas while relying on complex calculations in the background.
2. **Transtheoretical Model**:
    - **Principle**: Behavioral change occurs in stages: precontemplation, contemplation, preparation, action, and maintenance.
    - **Example**: CDC's education page on Ebola, addressing different stages of user awareness and action.
3. **Social Cognitive Theory**:
    - **Principle**: Focuses on self-efficacy and the belief in one's ability to take action.
    - **Example**: Patient decision aids designed to boost confidence and provide clear action plans.

### Practical Application

Theories provide frameworks to ensure that all aspects of user needs and behavior are considered in system design. They serve as checklists to avoid missing critical elements and help balance theoretical considerations with practical constraints.

By combining these approaches, we can create systems that effectively meet user needs, are technically feasible, and support efficient and informed decision-making.

# Articulating Workflow

Creating effective information systems in healthcare requires careful consideration of the workflow they are meant to support. Often, these systems can disrupt workflow if not properly designed, leading to harm. It's crucial to understand and articulate the workflow, even though it can be messy and complex.

### Key Points to Understand and Discuss Workflow

1. **Complex Nature of Workflow:**
    - Workflows are dynamic and often chaotic, requiring systems to support rather than disrupt.
    - A beautifully choreographed workflow may be ideal, but reality is much more disorganized.
2. **Importance of Diagrams:**
    - Drawing workflow diagrams helps identify gaps and understand the actual process.
    - Diagrams are essential for communication among stakeholders, not just for generating software.
3. **Types of Diagrams:**
    - **Flowcharts:** Show the flow of control with steps (actions) and decisions (diamonds).
    - **Swim Lane Diagrams:** Highlight different participants in the workflow, showing their interactions and support needs.

### Steps to Create Effective Workflow Diagrams

1. **Identify Participants:**
    - Determine all the roles involved in the workflow.
    - For example, in a clinical handoff, participants might include the departing resident, the team, the chief resident, the incoming resident, and the information system.
2. **Create Swim Lanes:**
    - Arrange participants in swim lanes to visualize their specific roles and interactions.
    - This helps identify which participants need more support and where potential gaps or issues might arise.
3. **Use Standard Symbols:**
    - Action boxes represent tasks or activities.
    - Decision diamonds indicate points where decisions are made.
    - Split/join lines show where processes diverge or converge.

### Communication and Iteration

- **Communication Tool:** Use diagrams to communicate with clients and team members to ensure everyone understands the workflow.
- **Iterative Process:** Create and refine diagrams through feedback and iteration to capture the workflow accurately and identify any missing elements.

### Complexity in Teamwork

- Complexity increases exponentially with the number of participants.
- It's essential to manage this complexity through clear and effective diagrams, which help in understanding and improving care coordination.

### Summary

- **From Needs to Specifications:** Move from identifying needs to defining requirements and finally specifying system functionalities.
- **Art of Diagramming:** Balance between being specific and allowing flexibility; focus on communication rather than exact representation.

By using these tools and methods, you can develop a deeper understanding of the workflow, communicate effectively with stakeholders, and design information systems that support rather than hinder the complex processes in healthcare.

# Information System Architecture

### Understanding Workflow and Communication

1. **Importance of Workflow**: Effective information systems support workflow by ensuring that every participant in a process can perform their role efficiently.
2. **Workflow Complexity**: The reality of workflows in healthcare is complex and often messy, involving multiple people and processes that need to be managed and coordinated.

### Tools for Understanding Workflow

1. **Flowcharts**: Useful for visualizing the steps in a process, showing how control flows from one step to another.
    - **Boxes**: Represent actions or tasks.
    - **Diamonds**: Represent decisions that need to be made.
2. **Swim Lane Diagrams**: Help identify different participants in a workflow and their roles.
    - **Participants**: Each participant is placed in a separate lane, showing their specific activities and interactions.
    - **Information System**: Explicitly represented to highlight its role in storing and transferring data.

### Concept of Modules and Systems

1. **Definition**:
    - **Module**: A component within a larger system that can function independently.
    - **System**: A collection of modules that work together to achieve a broader objective.
2. **Interdependence**: Modules can be systems themselves, and systems can function as modules within larger systems.

### Examples of System Architecture

1. **Provider-Centric Care**: EHRs integrate various modules supporting different providers.
    - **Types of Components**: Products (e.g., nursing care plan), activities (e.g., charting), devices, and logical components (e.g., knowledge databases).
2. **Patient-Centric Care**: mHealth and health apps.
    - **Layered Architecture**: Analysis, processing, storage, and data transport layers common across apps.
3. **Population-Centric Care**: Data from EHRs feeding into larger data repositories for public health initiatives.

### Integration and Interoperability

1. **Integrating the Healthcare Enterprise (IHE)**: Effort to write profiles for coordinating different participants and tasks.
2. **APIs and Standards**:
    - **FHIR (Fast Healthcare Interoperability Resources)**: Standard for data representation.
    - **CDS Hooks**: Provide clinical decision support by linking EHRs to external systems.

### Challenges and Considerations

1. **Architectural Influence**: Information system architecture is heavily influenced by the goals and context of the system.
2. **Legislation and Policies**: Often dictate the structure and function of information systems, leading to siloed architectures.

### Practical Application

- When developing or improving an information system, consider the interplay of various modules and systems.
- Use diagrams and flowcharts as communication tools to ensure a shared understanding among stakeholders.
- Recognize the limitations of diagrams as exact representations and use them as starting points for discussions and refinements.

Understanding these principles will help in designing systems that effectively support workflows in healthcare settings, ensuring that the right information is available to the right people at the right time.

# The Modules Comprising Clinical Information Systems

### Variety and Complexity of Clinical Information Systems

1. **Diverse Modules**: There are numerous types of clinical information systems, each serving different purposes.
    - **Inpatient Systems**: Systems used within hospital settings, such as EHRs, CPOE (Computerized Physician Order Entry), and laboratory information systems.
    - **Outpatient Systems**: Systems used in clinics and outpatient care, including scheduling systems, outpatient EHRs, and practice management software.
    - **Long-Term Care Systems**: Systems that cater to nursing homes and long-term care facilities, which combine aspects of inpatient and home care.
    - **Managed Care Systems**: Business-oriented systems focusing on the administration and management of healthcare services, including claims processing and patient management.
2. **Constant Change**: The landscape of clinical information systems is ever-changing, with new technologies, modules, and vendors continually emerging.

### Skills and Approach

1. **Focus on Core Skills**: Rather than memorizing the specifics of every system, develop core skills to assess and understand any clinical information system.
    - **Purpose**: Understand what the system is designed to accomplish.
    - **Functionality**: Learn the key functions and capabilities of the system.
    - **Evaluation**: Assess how the system's performance is measured and validated.
    - **Architecture**: Understand the system's architecture, including its components and how they interact.
    - **Technology**: Familiarize yourself with the underlying technology and infrastructure.
2. **Stack Analysis**: Conduct a stack analysis on any module or system to understand its components and interactions.
    - **Components**: Identify the different layers of the system, from hardware to software and logical components.
    - **Interactions**: Examine how data flows through the system and how different modules communicate and coordinate.

### Practical Exercise

1. **Choose a Module**: Select a clinical information system or module that you are interested in or currently use.
2. **Conduct a Stack Analysis**: Analyze the system based on the core skills mentioned above.
    - **Purpose and Functionality**: Define the system's goals and main features.
    - **Evaluation**: Research any available evaluations or performance metrics.
    - **Architecture and Technology**: Map out the system's architecture and identify key technological components.

### Key Insights

1. **Evaluation and Adaptation**: Continually evaluate the systems in use and adapt to new technologies and methods.
2. **Holistic View**: Understand that each module is part of a larger system and should be analyzed both as an individual component and as part of the broader healthcare ecosystem.
3. **Interoperability**: Focus on how different systems and modules can work together to create a seamless healthcare environment.

### Conclusion

Clinical information systems are intricate and varied, requiring a strategic approach to understand and utilize effectively. By focusing on core evaluation skills and conducting thorough stack analyses, you can navigate this complexity and contribute to the development and improvement of healthcare information systems.

# Developing Software

### Building vs. Buying Clinical Information Systems

### Decision Factors:

1. **Customization vs. Off-the-Shelf**:
    - **Bespoke Systems**: Custom-built to meet specific needs, acting like a multifunction knife.
    - **Off-the-Shelf Solutions**: Pre-built systems that may not meet all specific requirements but are ready to use.
2. **Cost and Disruption**:
    - **Financial Cost**: Custom solutions are usually more expensive to develop.
    - **Workflow Disruption**: Implementing off-the-shelf solutions might disrupt existing workflows and require significant adjustments.

### Key Considerations:

1. **Request for Proposal (RFP)**:
    - **Use Cases**: Clearly define use cases that the system must fulfill.
    - **Needs, Requirements, Specifications**: Understand and articulate internal needs and requirements before issuing an RFP.
    - **Vendor Evaluation**: Assess vendor capabilities, avoid relying solely on sales pitches, and seek peer institution references.
2. **Vendor Relationship**:
    - **Cultural Fit**: Ensure that the vendor's organizational culture aligns with yours.
    - **Communication and Workflow**: Establish clear lines of communication and shared workflows.
    - **Long-Term Relationship**: Remember, purchasing a system involves a long-term relationship with the vendor.

### Software Development Approaches

### Traditional Waterfall Model:

1. **Sequential Phases**:
    - **Requirements**: Gathering and documenting detailed requirements.
    - **Design**: Creating design specifications.
    - **Implementation**: Coding and building the system.
    - **Testing**: Ensuring the system functions as designed.
    - **Deployment**: Implementing the system in the real environment.
2. **Limitations**:
    - **Rigid Structure**: The sequential nature can be inflexible.
    - **Time-Consuming**: By the time the system is deployed, requirements and technology may have evolved.

### Agile Methodology:

1. **Continuous Iteration**:
    - **Flexible Phases**: Regular iterations through all development phases.
    - **Prototyping**: Building prototypes to elicit user needs and adjust specifications iteratively.
2. **Advantages**:
    - **Adaptability**: Adjust to changing requirements and technologies.
    - **User Feedback**: Continuous user involvement and feedback.
3. **Challenges**:
    - **Scope Management**: Difficult to define fixed scopes and timelines.
    - **Contract Complexity**: Harder to write and manage contracts due to evolving requirements.

### Software Development Governance

1. **Governance Models**:
    - **COBIT**: A framework for managing and governing enterprise IT.
    - **Maturity Models**: Assess the maturity of the software development and management process.
2. **Key Elements**:
    - **Business Goals**: Align IT goals with business objectives.
    - **IT Goals**: Define IT-specific goals that support business objectives.
    - **Workflow and Activities**: Manage the workflow and activities of the development team.
    - **Monitoring and Evaluation**: Continuously monitor and evaluate the process and outcomes.

### Practical Considerations

1. **Enterprise-Level Governance**:
    - **Broad Stakeholder Involvement**: Include a wide range of stakeholders in decision-making and governance.
    - **Scalability**: Consider scalability beyond initial implementation, especially for mHealth and other expansive solutions.
2. **Skepticism and Vigilance**:
    - **Critical Evaluation**: Maintain a critical approach to vendor claims and project progress.
    - **Avoid Pitfalls**: Be aware of potential misunderstandings and miscommunications throughout the process.

### Conclusion

The decision to build or buy a clinical information system involves a complex interplay of customization needs, cost considerations, workflow impacts, and long-term vendor relationships. Utilizing appropriate software development methodologies and governance models can significantly influence the success of the system implementation. Remember to continuously evaluate and adapt to changing requirements and technologies to ensure the system remains effective and aligned with organizational goals.

# Harming Workflow

The discussion on the impact of Health IT interventions highlights several critical issues and considerations for the implementation and usability of electronic health records (EHRs) and other health IT systems. Here's a summary and analysis of the key points:

### Impact of Health IT Interventions

### Potential for Harm

- **Minor to Severe Harm**: Health IT interventions can cause harm ranging from minor errors (like wrong colors or page numbers) to severe incidents (like incorrect medication dosages leading to patient harm or death).

### Workflow Disruptions

- **Death by a Thousand Clicks**: Many physicians find vendor EHR systems time-consuming and disruptive, taking away valuable time from patient care.
- **Nurse Practitioners' Struggle**: An example highlighted involves a nurse practitioner needing to log into 11 different systems and navigate through over 200 screens and 600 clicks, leading to significant inefficiency.

### Usability Issues and Alert Fatigue

- **Survey Results**: A significant percentage of nurses report poor usability, time consumption, and interference with patient care due to EHR systems.
- **Alert Fatigue**: Overloading clinicians with alerts can lead to important warnings being ignored. For example, a commercial system at Brigham Hospital increased alert firing rates, reducing clinician compliance with alerts and causing wasted time and frustration.

### Workflow and Usability Problems

- **Human Factors**: Issues include incomplete displays, unintuitive menus, repetitive prompts, and inability to batch process orders.
- **Affective Responses**: Frustration from dealing with non-user-friendly systems can lead to strong negative emotions and decreased trust in the system.

### Improving Health IT Systems

### User-Centered Design

- **Focus on Users**: Shifting focus towards user-centered design can address many usability issues.
- **Attributes of Usability**: A well-developed user-centered design practice can improve system usability and user satisfaction.

### Key Takeaways

1. **Balance Between Technology and Workflow**: It's essential to ensure that Health IT systems support clinical workflows rather than disrupt them. This requires careful consideration of how technology impacts day-to-day operations.
2. **User Involvement**: Involving end-users (clinicians, nurses, etc.) in the design and testing phases can help create systems that are more intuitive and better aligned with clinical needs.
3. **Managing Alerts**: Implementing intelligent alert management systems that prioritize critical alerts and reduce false alarms can help mitigate alert fatigue.
4. **Continuous Improvement**: Adopting agile methodologies and continuously iterating based on user feedback can help ensure that systems evolve to meet changing needs and technologies.

### Conclusion

Implementing Health IT systems requires a careful balance between technology and human factors. By focusing on user-centered design and continuously iterating based on feedback, healthcare organizations can develop systems that enhance rather than hinder clinical workflows, ultimately improving patient care and clinician satisfaction.