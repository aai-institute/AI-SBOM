# AISBOM - AI Software Bill of Materials

JSON Spec for Transparency Obligations of the EU AI Act, including LLM / foundation models

Version 0.1 (December 11, 2023)

## How to

- This Json file is intended as a means to address the transparency requirements in the upcoming EU AI Act (Focus on Article 13 & 52). 
- The file is an illustrative example as the basis for discussion and feedback.
- To use the file, copy the template and insert the values of the AI System at hand.
- The file is not in line with the Json Schema, but we may adopt the schema in the future.

## Call to action

- Please share your feedback in the Github Discussion. 
- See the call for contributing at the end of this document.

## How to cite this work

Adrian XXXXX & appliedAI Institute for Europe gGmbH (2024). AI Bill of Material - Transparency (AI BOM). GitHub. [https://github.com/XXXX](https://github.com/aai-institute/AI-SBOM/discussions)

## Overview

EU AI Act. It is addressing mainly the transparency obligations outlined in Articles 13 and 52 of the AI Act to share and emphasize relevant information with various stakeholders and interested parties

BOM = Bill of Material; The set of elements, an inventory, that are needed to compile or produce a product; Adopted to an AI System and inspired from areas like manufacturing and cybersecurity.

## Purpose of the AI BOM Transparency

Collecting and providing the information required by Articles 13 and 52 can be challenging in complex AI value chains involving multiple entities who control or need certain information. The AI BOM Transparency is intended as the single point of truth for collecting and sharing the necessary information, keeping the following benefits in mind:

- Overview of transparency obligations: Reducing the need for an in-depth understanding of the AI Act (saves time and effort to read 160+ pages).
- Improves risk management in transparency: Completing the AI BOM helps in identifying and addressing potential vulnerabilities and dependencies related to transparency throughout the development cycle of high-risk AI systems.
- Approach to simplify compliance with transparency requirements: Helps to ensure adherence to the AI Act's transparency requirements by collecting the relevant information, which, in turn, reduces deployment and liability risks.
- AI BOM Transparency may complement and/or refer to the instruction for use (“User Manual”). It could be a first “draft” of a “User Manual” which has to be provided to the Deployer.

## Target group of the AI BOM

AI BOM Transparency targets technical professionals engaged in compliance matters as well as compliance experts delving into technical aspects. Our goal is to support providers and deployers in managing, maintaining, and making knowledgeable choices about AI systems within the AI Act's regulations (Articles 13 and 52). Achieving this is more feasible through a collaborative approach.

## What is the scope of Article 13 AI Act? [EU Parlaments Proposal]

Article 13 AI Act applies to high risk AI Systems (details in Article 6) and outlines requirements and considerations related to transparency and accountability in the deployment of an AI System. In a nutshell:

**Article 13 (1)**: The transparency obligations are set to enable the understanding of the outcomes and functioning of the respective AI System. Specifically, it entails the obligation to ensure that: (i) the AI System will be used properly i.e.according to its intended purpose by stating how the AI System actually works, (ii) details about the processed data are known and (iii) the AI Systems output is interpretable and can be explained to affected persons.

**Article 13 (2)** Requires that the high-risk AI System shall be accompanied with **instructions for use** [Like a “**(Digital) User Manual**”] that helps the deployer (the entity who is putting the AI System into use) operating and maintaining the AI System as intended, as well as supporting an informed decision making by the deployer. Such a User Manual has to incorporate information referred to in Article 13 (3) and be available prior to putting the AI System into service or placing the AI System on the market.

**Article 13 (3)** Specifies concrete information that shall be communicated for reaching sufficient transparency to satisfy Article 13 (1). This is the focus of the AI BOM and includes information such as the intended purpose of the AI System, known/foreseeable risks/misuses, desired input data, affected persons etc. The AI BOM is not meant to replace or implement the instructions for use. The AI BOM aims to support in collecting such relevant information for the instructions of use during the development process of an AI System.

Thus, high-risk AI Systems shall be designed and developed in such a way that their operation is sufficiently transparent to assure the respective deployer (and provider themselves if they deploy their own AI System internally) appropriately interpret and use the results of the AI System [“Procedural Transparency”]. Such Procedural Transparency, as outlined in Article 13, is particularly crucial in the AI value chain perspective from the provider to the actual deployer of the AI System.

## What is the scope of Article 52 AI Act? [EU Parlaments Proposal]
Article 52 AI Act aims to ensure the transparency of AI Systems in case natural persons and/or the general public are exposed to an AI System. This is ensured in three ways: 

(i) **Article 52 (1)**: If there is an interaction of the AI System with a natural person - like a Chatbot, Healthcare Diagnosis Tools used by doctors, AI driven robot financial advisors -  such interactions have to be made transparent through a notification to the affected natural persons [“**Interaction Transparency**”]. 

(ii) **Article 52 (2)**: If the AI System is an emotion recognition or biometric categorisation system, prior to the processing of such data, the affected person has to give their consent for such (connection to the GDPR) [“**Consent Transparency**”]. 

(iii) **Article 52 (3)**: If the AI System is generating so-called “deep fakes”, such artificially generated content shall be disclosed in a visible manner like “watermarks” [“**Content Transparency**”].

Notably, an AI System that is not classified as high-risk and therefore exempt from compliance with Article 13 may still be subject to the provisions of Article 52 if one of the three paragraphs applies. Conversely, if an AI System is classified as high risk, Article 52 might apply in addition.

## Contributing

This draft is understood as a “living paper” mapping the state of an ongoing discussion and open for feedback. We invite all stakeholders to share their insights and suggestions to enhance the tool's effectiveness and compliance capabilities. Please consider our notes for feedback and discussion.

**Note #1**: This AI BOM Transparency is for discussion purposes and does not constitute legal advice. It is essential to consult with legal experts to ensure full compliance with the AI Act. 

**Note #2**: We mainly worked with the proposal of the EU Parlament. The final text of the AI Act is still unknown. Also any standards for Article 13 and Article 52 are under development and not published at the moment. The AI BOM is current as of the date of its publication and does not necessarily reflect the present state of the law or relevant regulation.

**Note #3**: Recognizing the variety of stakeholders involved in the AI lifecycle, each possessing varying degrees of technical know-how, we understand that transparency is not a one-size-fits-all attribute. AI systems should offer tailored transparency across the AI value chain, catering to the unique needs and perspectives of each stakeholder. This calls for a collaborative effort among all parties involved to ensure effective transparency."

**Note #4**: Please be aware that transparency has an intense tension (especially proprietary AI Systems) with **Data Privacy** (access/description to training data) and **IP/trade secrets** (access/description to the model) and **Cyber Security** (access/description to training data + the model vulnerabilities) - [altogether “Sensitive Information”]
