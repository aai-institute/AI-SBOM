# AISBOM - AI Software Bill of Materials

JSON Spec for Transparency Obligations of the EU AI Act, including LLM / foundation models

Version 0.1 (December 10, 2023)

## Overview

The AI BOM Transparency is a tool designed to support compliance with the upcoming AI Act. It is addressing mainly the transparency obligations outlined in Articles 13 and 52 of the AI Act. 

## What is the scope of Article 13 AI Act? [EU Parlaments Proposal]

Article 13 AI Act outlines requirements and considerations related to transparency and accountability in the deployment of an AI System, which are high-risk. In a nutshell:

**Article 13 (1)**: The desired task or outcome of such transparency obligations is assuring the understanding of the functioning of the respective AI System. Concretely it is to be ensured that (i) the AI System will be properly used by stating how the AI System actually works, (ii) details about the processed data is known and (iii) the AI Systems output is interpretable.

**Article 13 (2)** refers to the AI lifecycle, i.e. in most cases the developer of an AI System [the provider] will not be the one putting the AI System actually in practical use, it is the deployer in most cases. Thus there is the transparency requirement that the high-risk AI system shall be accompanied with **instructions for use** [Like a “**(Digital) User Manual**”] that helps the deployer operating and maintaining the AI System as well as supporting an informed decision making by the deployer. Such User Manual have to incorporate information referred to in Article 13 (3).

**Article 13 (3)** specifies concrete information - here is the focus of the AI BOM - which has to be provided, to assure the desired outcome of Article 13 (1) will be reached. For example information such as the intended purpose of the AI System, known/foreseeable risks/misuses, desired input data, affected persons etc.

Thus, high-risk AI systems shall be designed and developed in such a way that their operation is sufficiently transparent to assure the respective deployer (and provider themselves if they deploy their own AI System internally) appropriately interpret and use the results of the system [“Procedural Transparency”]. Such Procedural Transparency, as outlined in Article 13, is particularly crucial in the AI value chain perspective from the provider to the actual deployer of the AI System.

## What is the scope of Article 52 AI Act? [EU Parlaments Proposal]
Article 52 AI Act aims to ensure the transparency of AI Systems in case natural persons and/or the general public are exposed to an AI System. This is ensured in three ways:

(i) **Article 52 (1)**: If there is an interaction of the AI System with a natural person - like a Chatbot, Healthcare Diagnosis Tools used by doctors, AI driven robot financial advisors -  such interactions have to be made transparent through a notification to the affected natural persons [“**Interaction Transparency**”]. 

(ii) **Article 52 (2)**: If the AI System is an emotion recognition or biometric categorisation system, prior to the processing of such data, the affected person has to give their consent for such (connection to the GDPR) [“**Consent Transparency**”]. 

(iii) **Article 52 (3)**: If the AI System is generating so-called “deep fakes”, such artificially generated content shall be disclosed in a visible manner like “watermarks” [“**Content Transparency**”].

Notably, an AI System that is not classified as high-risk and therefore exempt from compliance with Article 13 may still be subject to the provisions of Article 52 if one of the three paragraphs applies.

## Purpose of the AI BOM Transparency
Collecting and providing the information required by Articles 13 and 52 can be challenging in complex AI value chains involving multiple entities. The AI BOM Transparency aims at giving a first overlook of the necessary information, keeping the following benefits in mind:

- Overview of transparency obligations: Reducing the need for an in-depth understanding of the AI Act (saves time and effort to read 160+ pages).
- Improves risk management in transparency: Completing the AI BOM helps in identifying and addressing potential vulnerabilities and dependencies related to transparency throughout the development cycle of high-risk AI systems.
- Approach to simplify compliance with transparency requirements: Helps to ensure adherence to the AI Act's transparency requirements by collecting the relevant information, which, in turn, reduces deployment and liability risks.
- AI BOM Transparency could be a first “draft” of a “User Manual” which has to be provided to the Deployer.

## Target Group of the AI BOM
AI BOM Transparency targets technical professionals engaged in compliance matters as well as compliance experts delving into technical aspects. Our goal is to support providers and deployers in managing, maintaining, and making knowledgeable choices about AI systems within the AI Act's regulations (Articles 13 and 52). Achieving this is more feasible through a collaborative approach.

## Contribution

This draft is understood as a “living paper” mapping the state of an ongoing discussion and open for feedback. We invite all stakeholders to share their insights and suggestions to enhance the tool's effectiveness and compliance capabilities. Please consider our notes for feedback and discussion.

**Note #1**: This AI BOM Transparency is for discussion purposes and does not constitute legal advice. It is essential to consult with legal experts to ensure full compliance with the AI Act. 

**Note #2**: We mainly worked with the proposal of the EU Parliament. The final text of the AI Act is still unknown. Also any standards for Article 13 and Article 52 are under development and not published at the moment. The AI BOM is current as of the date of its publication and does not necessarily reflect the present state of the law or relevant regulation.

**Note #3**: Recognizing the variety of stakeholders involved in the AI lifecycle, each possessing varying degrees of technical know-how, we understand that transparency is not a one-size-fits-all attribute. AI systems should offer tailored transparency across the AI value chain, catering to the unique needs and perspectives of each stakeholder. This calls for a collaborative effort among all parties involved to ensure effective transparency."

**Note #4**: Please be aware that transparency has an intense tension (especially proprietary AI Systems) with **Data Privacy** (access/description to training data) and **IP/trade secrets** (access/description to the model) and **Cyber Security** (access/description to training data + the model vulnerabilities) - [altogether “Sensitive Information”]
