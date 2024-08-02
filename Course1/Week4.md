# Introduction: Data, Information, Knowledge, Technology

1. **Data, Information, Knowledge, and Technology**:
    - The definition of informatics centers around data, information, and knowledge.
    - These elements are crucial in the learning health system cycle.
2. **Data**:
    - **Key Point**: Understand the flow of data within a system:
        - Origin of data.
        - Modification points.
        - Destination of data.
        - Transmission routes.
    - Data's relevance varies by purpose: clinical, research, or public health.
3. **Information**:
    - **Purpose**: To interpret data effectively.
    - **Avoid**: Misunderstanding the data.
4. **Knowledge**:
    - **Focus**: Track the flow of knowledge:
        - Possessors of knowledge.
        - Sources of knowledge.
        - Application and effectiveness.
    - **Purpose**: To understand the "why" and "how."
5. **Standards**:
    - **Appropriateness**: Ensure the correct standard is applied at each level (data, information, knowledge).
6. **Pyramid Structure**:
    - **Data**: The foundational level.
    - **Information**: Derived from data, answering who, what, where, and when.
    - **Knowledge**: Developed from information, addressing why and how.
    - **Wisdom**: Not part of the pyramid; involves experiential judgment and decision-making beyond data and knowledge.
        - Includes insights like when not to use knowledge.
7. **Algorithms**:
    - **Function**: How computers process data, information, and knowledge.
        - **Processes**: Data collection, information interpretation, and knowledge generation.
8. **DIKWA**:
    - **Concept**: Refers to the complex interaction of Data, Information, Knowledge, Wisdom, and Algorithms.
    - **Usage**: Terms will be used to describe this complex system.

# Many Types of Clinical Data

1. **Introduction to Clinical Data**:
    - Clinical data encompasses a wide range of information beyond basic health records.
    - Isaac Kohane's graphic from Boston Children's Hospital is complex and comprehensive. A simplified table is used for easier understanding.
2. **Types of Data**:
    - **Structured Data**:
        - Health data traditionally found in Electronic Health Records (EHRs).
        - Includes medical record numbers, visit types, lab results, and ICD codes.
        - Structured data follows a specific format or vocabulary, such as numeric values, checkboxes, and codes.
    - **Unstructured Data**:
        - Includes clinic notes, social history, and free-text fields.
        - Typically found in narrative formats and contains information like chief complaints, radiology reports, and images.
3. **Examples of Data**:
    - **Structured Data**:
        - **Medical Record Number**: An ID with a specific format.
        - **Visit Type**: Finite list of possibilities; considered atomic.
        - **Lab Results**: May be atomic or more complex.
        - **ICD Codes**: Structured vocabulary for diagnoses.
    - **Unstructured Data**:
        - **Clinic Notes**: Narrative texts containing patient-specific information.
        - **Social History**: Free-text fields describing occupation or lifestyle.
        - **Radiology Reports and Images**: Textual and visual data needing extraction and interpretation.
        - **Allergies**: Can be complex with varied details.
4. **Structured vs. Unstructured Data**:
    - **Structured Data**: Easily categorized and queried; includes numerical values and fixed-format fields.
    - **Unstructured Data**: Free-form and narrative; requires extraction and interpretation for analysis.
5. **Importance of IDs**:
    - IDs are crucial for database integrity and accurate patient identification.
    - Incorrect use of IDs can lead to errors and potential harm, as illustrated by the example of the computerized provider order entry (CPOE) system.
6. **Additional Data Types**:
    - **Patient-Specific**: Includes census data, grocery data, and health-related apps.
    - **Environmental Data**: Measures like lead levels in soil or air; relevant to patient health but not personal data.
7. **Future Considerations**:
    - Apps and electronic records collect both structured and unstructured data.
    - Privacy concerns and data relevance extend beyond traditional health data to include social media and police records.
8. **Population Health Data**:
    - Includes both direct and indirect health-related information.
    - Encompasses environmental data and broader societal factors affecting individual health.

# Information

- **Organization of Information:**
    - The electronic health record (EHR) example demonstrates how data is organized to facilitate interpretation.
    - Active problems, medications, allergies, and alerts are categorized for ease of access and understanding.
    - The same data, such as ibuprofen, can appear in multiple categories (medication or allergy) depending on its context.
- **Range as Information:**
    - In OpenMRS (an open-source medical record system), temperature data is presented with a range.
    - An anomaly, like a 44°C reading compared to the maximum limit of 43°C, is flagged without assessing the plausibility of the value.
- **Knowledge of Norms and Guidelines:**
    - A growth chart plots a child's height and compares it to percentiles.
    - The chart contextualizes the data, indicating how the child's height compares to other children of the same age without specifying actions to take.
- **Maps for Data Organization:**
    - Maps illustrate data distribution, such as mortality rates.
    - Different colors represent varying levels of mortality risk, allowing viewers to interpret regional differences in risk.
- **Data about Individuals vs. Population:**
    - Mortality rates are derived from individual data aggregated to calculate a ratio.
    - Emergent properties, such as herd immunity, arise from the population as a whole and cannot be deduced from individual data alone.
- **Emergent Properties:**
    - Examples like the Mona Lisa demonstrate that the whole is more than the sum of its parts.
    - Emergent properties are those that arise from the collective whole, rather than from individual components.
- **Distinguishing Data and Information:**
    - The distinction between data and information can be blurred, especially with rates or emergent properties.
    - Information may be derived from individual data, while properties like herd immunity are population-based.
- **Metadata:**
    - Metadata provides context for interpreting data, such as the significance of a sodium level or the timing and method of measurement.
    - It helps in distinguishing the relevance and accuracy of data (e.g., pre- vs. post-transfusion blood counts).
- **Conclusion:**
    - The interpretation of data as information is context-dependent.
    - Historical examples, like Marie Curie's discovery, illustrate how data's meaning can be transformative based on its interpretation.

# Knowledge

- **From Information to Knowledge:**
    - A growth chart serves as information. Knowledge emerges when this information is interpreted in context.
    - Example: A child’s growth curve initially appears below the third percentile, raising concerns. However, considering the growth chart's origin and comparing it with modern WHO standards reveals that the child's growth is normal for their background.
- **Predictive Analytics and Risk Scores:**
    - Predictive analytics generates risk scores for conditions like congenital diaphragmatic hernia.
    - The scores indicate mortality risk and require interpretation of what constitutes a high or low risk.
    - Validation of such formulas is crucial to ensure reliability. Unvalidated AI or machine learning models should not be used.
- **Risk Calculators and Data Interpretation:**
    - Risk calculators use both structured data (e.g., genetic tests) and unstructured data (e.g., medical records).
    - These calculators compare individual risks to population data, and it is essential to understand how to interpret these results (e.g., framing effect of mortality risk).
- **Active Advice and Alerts:**
    - Health IT systems can provide active advice based on lab results.
    - Example: A system reads a lab report, identifies antibiotic sensitivities, and recommends treatment, showcasing how knowledge is applied to guide actions.
- **Historical Perspective and Evolution:**
    - The concept of active advice in healthcare dates back to the late 1800s, demonstrating the evolution of knowledge application in medical practice.
- **Knowledge Applied to Imaging:**
    - MRI image analysis involves identifying anatomical structures like the femur, kneecap, and tibia.
    - The distinction between implicit and explicit knowledge in machines: while a machine may process and identify images, it may not possess explicit knowledge about the anatomy.
- **Knowledge and Judgment:**
    - Knowledge involves judgment about what to do or what something means compared to others.
    - It includes understanding implications and making decisions based on available information.
- **Implicit vs. Explicit Knowledge:**
    - Implicit knowledge refers to understanding without explicit articulation (e.g., recognizing a knee's anatomy).
    - Explicit knowledge involves clear, actionable information (e.g., specific treatment guidelines).
- **Context and Interpretation:**
    - Knowledge depends on context and the interpretation of data (e.g., ibuprofen listed as an allergy vs. medication).
    - The meaning and application of data can vary based on its classification and context.
- **Conclusion:**
    - Understanding the distinctions between data, information, and knowledge is crucial.
    - Recognizing how knowledge is applied, interpreted, and validated helps in making informed decisions and improving practices in various fields, especially healthcare.

# Putting DIKW Together

1. **Diabetes Management System:**
    - **Data:**
        - Numerical values like 190 (blood glucose level) and 45 (carbohydrate ingestion).
        - The type of insulin and the amount prescribed.
        - Metadata such as the date and time of the data entry.
    - **Information:**
        - The graph showing historical blood glucose levels and insulin doses in a structured manner.
        - Feedback on whether the current blood glucose level (190) is above the target (130), which helps in interpreting the data.
    - **Knowledge:**
        - The system’s recommendation to take insulin based on the current blood glucose level and carbohydrate intake, which is actionable advice derived from the data.
2. **Electronic Health Record (EHR) Front Sheet:**
    - **Data:**
        - Individual elements within each panel, such as the medication name (e.g., Ibuprofen) and the vaccination data.
    - **Information:**
        - The organization of data into specific blocks (e.g., allergies, medications, active problems) which helps in understanding the meaning of the data.
    - **Knowledge:**
        - The recommendations for vaccinations in the upper right-hand side, which provide actionable advice based on the organized data.
3. **Public Health Dashboard:**
    - **Data:**
        - Individual data points on the map or graph, such as color-coded counties or specific data values.
    - **Information:**
        - The map itself, which organizes and visualizes data across different regions.
    - **Knowledge:**
        - The regression line or association depicted on the graph, which represents an understanding of the relationship between variables (e.g., health outcomes and environmental factors).

**Note:** Wisdom is not directly observable in these interfaces but involves making informed decisions based on the knowledge derived from the data and information.

# Data Exchange

1. **Problem with Data Exchange:**
    - Data can’t always be simply sent from one place to another due to differences in naming and representation.
    - Example: Anemia can be spelled differently (e.g., anemia vs. anaemia) or represented differently (e.g., sodium as Na, Na+, or NaCl). These variations can lead to discrepancies in data interpretation.
2. **Metadata and Naming:**
    - Metadata provides context about data, such as the name and units (e.g., sodium level as 135 mmol/L).
    - If names or metadata are incorrect or inconsistent, it can result in incorrect data interpretation or processing.
3. **LOINC Codes:**
    - LOINC (Logical Observation Identifiers Names and Codes) standardizes medical terminology to ensure consistent representation of observations (e.g., sodium levels).
    - Different LOINC codes may represent different aspects or methods of measuring sodium, which can impact how data is collected and used.
4. **Intention vs. Extension:**
    - **Intention:** What is in the researcher’s or clinician’s mind (e.g., the concept of heart failure as understood by the researcher).
    - **Extension:** What is represented in the data or coding systems (e.g., specific ICD-10 codes for heart failure).
    - The gap between intention and extension can lead to miscommunication or misinterpretation of data.
5. **Clinical Coding Systems:**
    - **ICD-10:** Used for diagnoses with many codes.
    - **HCPCS:** Used for procedures and supplies.
    - Different coding systems serve different purposes and have varying numbers of codes.
6. **Unstructured Data to Structured Data:**
    - Techniques like text processing and natural language processing (NLP) are used to convert unstructured data (e.g., clinical notes) into structured formats.
    - NLP can handle complex language and negation (e.g., “patient denies alcohol use”).
7. **Data Quality:**
    - **Conformance:** Does the data match the expected format?
    - **Completeness:** Are all required values present?
    - **Consistency:** Is the data consistent over time and across sources?
    - **Plausibility:** Does the data make sense (e.g., a height of 62 inches for an adult)?
    - **Verification:** Can the data be validated against external sources?
8. **Conclusion:**
    - Data exchange involves more than just transferring data; it requires attention to naming conventions, intention vs. extension, and data quality.
    - Understanding and addressing these factors is crucial for effective and accurate data exchange in clinical and research settings.

# Interoperability Revisited: Text Data

1. **Data Packaging Standards:**
    - **HL7 (Health Level Seven):** An important standard for healthcare data exchange, focusing on how data should be packaged for communication. It has evolved through various versions (e.g., HL7 v2.x) and is used to ensure consistent information transfer between different healthcare systems.
    - **Clinical Document Architecture (CDA):** A format for structuring clinical documents, though it hasn't been as successful in practice as intended.
    - **FHIR (Fast Healthcare Interoperability Resources):** A newer standard aimed at improving data exchange by addressing some limitations of HL7 and CDA.
2. **Communication Layers and Protocols:**
    - **Application Layer:** Deals with data exchange at the application level (e.g., HL7 for healthcare applications).
    - **Presentation Layer:** Handles character encoding (e.g., Unicode, ASCII) and data formats.
    - **Session Layer:** Manages connections between machines.
    - **Transport Layer:** Ensures data is reliably sent and received.
    - **Network Layer:** Breaks data into packets and manages their routing.
    - **Data Link Layer:** Connects packets to physical media.
    - **Physical Layer:** The actual transmission medium (e.g., fiber optics, radio waves).
3. **Challenges with HL7 Standards:**
    - **Variation in Implementation:** Even if different systems claim to conform to the same version of HL7, differences in field usage, formatting, and missing data can occur.
    - **Complexity:** The standards involve numerous segments and fields, making consistent interpretation and integration challenging.
    - **Inconsistencies:** Issues like different timestamp formats and missing mandatory fields can complicate data exchange.
4. **Vocabularies and Codes:**
    - **LOINC (Logical Observation Identifiers Names and Codes):** Standardizes names and codes for clinical observations and measurements, such as sodium levels.
    - **ICD (International Classification of Diseases):** Used for diagnoses and procedures with numerous codes to specify various health conditions and interventions.
5. **Data Quality Dimensions:**
    - **Conformance:** Ensuring data adheres to expected formats.
    - **Completeness:** Verifying that all necessary data points are present.
    - **Consistency:** Checking for data accuracy over time and across different sources.
    - **Plausibility:** Ensuring data falls within reasonable bounds.
    - **Verification:** Cross-checking with external sources for validation.
6. **Text and Natural Language Processing (NLP):**
    - **Text Processing:** Extracting known data (e.g., codes) from text.
    - **NLP:** Handling more complex tasks such as negation and context understanding, which is crucial for interpreting clinical notes accurately.

### **Summary**

Interoperability in healthcare data exchange involves ensuring that different systems and applications can communicate effectively using standardized formats and vocabularies. Despite efforts to standardize through frameworks like HL7 and FHIR, challenges persist in maintaining data consistency and quality. Understanding these standards and their implementation details is crucial for anyone working in healthcare informatics or data science.

# Interoperability: Images

In the realm of medical imaging, **DICOM (Digital Imaging and Communications in Medicine)** is a crucial standard. Here’s a breakdown of key points from the discussion about DICOM and its role in imaging informatics:

### **Overview of DICOM**

1. **Purpose and Evolution:**
    - **Standardization:** Before DICOM, different imaging modalities (like MRI, CT scans, X-rays) used their proprietary formats and interfaces, leading to inefficiencies and high costs. DICOM was developed to standardize the way images and related information are transferred and stored, reducing redundancy and cost.
    - **Adoption:** DICOM has become the global standard for medical imaging, ensuring interoperability across various imaging devices and systems.
2. **Modality and Image Types:**
    - **Modality:** Refers to the device or technique used to capture the image, such as MRI, CT, ultrasound, or X-ray. DICOM supports all modalities, allowing consistent handling of images regardless of their source.
    - **Image Example:** An ultrasound image showing blood flow can be stored and transferred using DICOM standards, ensuring it can be accessed and interpreted by different systems.
3. **Image Transfer and Storage:**
    - **Formats:** DICOM defines how images should be stored and transferred. This includes both digital and analog formats, with digital images being stored in a standardized format that can be accessed universally.
    - **Transmission:** Images can be transferred via physical media (e.g., DVDs) or electronically over networks. DICOM ensures that images remain accessible and interpretable regardless of how they are sent.
4. **Conformance and Semantics:**
    - **Conformance:** Ensures that both the sending and receiving systems adhere to DICOM standards, so images and data are accurately interpreted. This is critical for ensuring compatibility between different systems and devices.
    - **Semantics:** Refers to the intended use and meaning of the image data. DICOM encompasses both the technical aspects of image transfer and the contextual meaning of the data.
5. **Components and Systems:**
    - **PACS (Picture Archiving and Communication System):** Manages and stores images for radiologists, allowing for efficient retrieval and viewing.
    - **RIS (Radiology Information System):** Handles scheduling, orders, and reporting within the radiology department, integrating with PACS to provide a comprehensive workflow.
6. **Data Structure:**
    - **Studies and Series:** A study may consist of multiple series (e.g., different angles or phases of a CT scan), and each series comprises multiple images. DICOM manages these hierarchies, ensuring all related images and metadata are appropriately linked.
7. **Complexity and Scope:**
    - **Volumes of Standards:** DICOM is extensive, with multiple volumes covering various aspects of image management and communication. For those working in imaging informatics, familiarity with these volumes is essential for effective implementation and troubleshooting.

### **Summary**

DICOM plays a critical role in the field of medical imaging by providing a standardized framework for storing, transferring, and managing images across different systems and modalities. It ensures that images from various sources can be universally accessed and interpreted, supporting a wide range of imaging technologies and workflows in healthcare. Understanding DICOM is fundamental for professionals involved in medical imaging, as it integrates technical, clinical, and operational aspects of image management.

# Making It Work Together

The discussion highlights the complexity of managing and orchestrating data exchange in healthcare as it scales from point-to-point communication to more complex workflows involving multiple stakeholders. Here’s a summary of the key concepts related to workflow management and interoperability:

### **IHE (Integrating the Healthcare Enterprise)**

1. **Purpose and Scope:**
    - **Workflow Management:** IHE is designed to address the complexities of managing interactions and data exchanges across entire healthcare institutions, handling multiple modalities and systems.
    - **Integration Profiles:** IHE uses integration profiles to define specific use cases (e.g., telemedicine, immunization reporting) and the steps required for data exchange in these scenarios.
2. **Examples of Use:**
    - **Telemedicine:** Involves interactions between patients, doctors, and multiple healthcare facilities. IHE’s integration profiles help manage the data flow and ensure completeness in a many-to-many relationship.
    - **Public Health Reporting:** Coordinates data across different entities, such as vaccination clinics, supply chains, and public health agencies, ensuring all relevant parties are updated and data is properly managed.
3. **Components:**
    - **Integration Profiles:** These are detailed descriptions of how to implement specific data exchange scenarios, including rules and workflows.
    - **Implicit Knowledge:** Integration profiles often contain rules and processes that might seem obvious to humans but need to be explicitly defined for machines to follow.

### **Interoperability and Policy**

1. **Interoperability Stack:**
    - **Functions:** Different stakeholders require various functions from interoperability systems, such as sending, receiving, finding, and using data.
    - **Technical and Policy Components:** Interoperability involves both technical standards (e.g., data formats) and policy considerations (e.g., privacy, security).
2. **Policy and Technical Components:**
    - **Data Formats and Standards:** Standards like DICOM and HL7 are crucial for data exchange at different levels.
    - **Higher-Level Issues:** As you move up the stack, policy issues and broader interoperability challenges become more prominent.
3. **Understanding Interoperability:**
    - **Comprehensive View:** Understanding the entire stack of interoperability—from low-level data formats to high-level workflow management and policy—provides a more complete picture of how data is exchanged and managed across healthcare systems.

### **Key Takeaways**

- **IHE** is essential for managing complex workflows and data exchanges across multiple healthcare systems.
- **Integration Profiles** define specific use cases and the required steps for successful data exchange.
- **Interoperability** involves both technical standards and policy considerations, with different levels of the stack addressing various aspects of data management and exchange.
- **Understanding the Stack:** Knowledge of both the technical and policy components of interoperability helps in navigating and implementing effective data exchange solutions in healthcare.

This overview of IHE and interoperability highlights the intricate nature of managing data across healthcare systems and the importance of having robust standards and workflows to ensure seamless and effective communication.

# Technology: Hype Cycles

**Hype Cycles Overview:**

- **Innovation Trigger:** The initial phase where a new technology emerges and captures attention. It's often characterized by high expectations and excitement.
- **Peak of Expectations:** The technology reaches peak interest, with inflated expectations and optimism about its potential.
- **Trough of Disillusionment:** Reality sets in as the technology fails to meet the high expectations, leading to disappointment and reduced enthusiasm.
- **Plateau of Productivity:** The technology matures and its practical value becomes clearer, leading to widespread adoption and integration into standard practices.

### **Applying Hype Cycles to Healthcare Technologies**

1. **Electronic Health Records (EHRs):**
    - **Current Position:** At the bottom of the Trough of Disillusionment.
    - **Reason:** EHRs have faced significant challenges and dissatisfaction among clinicians. Despite this, there is hope for future improvements and more effective implementations.
2. **Blockchain:**
    - **Current Position:** Likely moving from the Innovation Trigger towards the Peak of Expectations.
    - **Future Projection:** The hype around blockchain might eventually lead to disillusionment before reaching practical, productive applications.
3. **Smart City Technologies:**
    - **Relevance:** Integrate with public health through social determinants of health and environmental factors. Includes technologies like transportation and the Internet of Things (IoT).
    - **Current Status:** Continues to develop with applications in health and broader urban environments.
4. **Big Data:**
    - **Current Position:** Moving past the Trough of Disillusionment and rising towards the Plateau of Productivity.
    - **Observation:** Despite initial setbacks, big data is becoming increasingly valuable in various applications, including healthcare.
5. **Data Science and Machine Learning:**
    - **Current Status:** Includes predictive analytics, which is moving towards the Trough of Disillusionment.
    - **Note:** Technologies like predictive analytics may face challenges, but they are critical for advancing healthcare and other fields.

### **Key Takeaways**

- **Focus on the Right-Hand Side:** While new and exciting technologies (left side of the Hype Cycle) capture attention and investment, it is crucial to also address the technologies and solutions that are already in the Trough or Plateau stages. These are where practical improvements can be made and where current patient needs are being addressed.
- **Balance Excitement with Practicality:** Understand that while emerging technologies are exciting, practical and meaningful advancements often come from technologies that have matured and are in widespread use.

# Careers

### **Careers in Informatics**

**Where Are the Jobs?**

1. **Hospitals and Healthcare Providers:**
    - Opportunities exist in various settings from small practices to large integrated delivery networks and accountable care organizations.
    - Small practices might prefer consultants due to limited resources.
2. **Consultancies:**
    - Consultancies, especially those specializing in healthcare or IT, need informaticians to bridge the gap between technology and clinical practice.
3. **Vendors, Startups, and Health Information Exchanges:**
    - These organizations often require informaticians to design, implement, and improve solutions that connect and enhance health systems.
4. **Government Agencies:**
    - Government entities involved in health policy and regulation need informaticians to ensure that policies are feasible and align with IT realities.
5. **Universities:**
    - Academic roles involve innovation, research, and teaching in informatics and related fields.

**Roles in Informatics:**

1. **Evaluator:**
    - Assesses the effectiveness and fit of software and systems. Requires an understanding of both clinical needs and technological capabilities.
2. **Specifier:**
    - Involves creating detailed requirements and specifications for systems. Requires a strong grasp of both informatics and clinical workflows.
3. **Builder:**
    - Develops software and systems. While IT-oriented, having informaticians on the team can prevent issues and streamline development.
4. **Maintainer:**
    - Ensures that systems and knowledge are up-to-date and functioning correctly. Often involves IT staff but can benefit from informatics expertise.
5. **Innovator:**
    - Focuses on developing new technologies or approaches. Can be internal or academic, involving innovation in informatics practices or new IT solutions.

**Educational Pathways:**

1. **Masters Degrees:**
    - Accredited programs (e.g., CAHIIM in the U.S.) provide specialized knowledge in health informatics.
2. **Certificates and Fellowships:**
    - Offer targeted learning and practical experience in informatics.
3. **PhD Programs:**
    - For advanced research and academic careers in informatics. Some institutions offer specialized doctoral pathways.
4. **Data Science and Related Fields:**
    - Fields like data science, computer science, biomedical engineering, and biostatistics offer advanced training that complements informatics.

**Key Takeaways for a Career in Informatics:**

- **“Can vs. Should”:** Focus on not only what technology can do but what it should do to benefit healthcare and avoid harm.
- **Balance:** Address the practical aspects of current technologies while staying informed about emerging innovations.
- **Career Opportunities:** Consider roles that align with your interests and skills, whether they are in clinical settings, consultancies, or academia.

**Final Thoughts:**

- Informatics is a dynamic field with vast opportunities for impact and growth.
- Embrace the challenges and advancements in technology with a focus on improving patient care and system efficiency.