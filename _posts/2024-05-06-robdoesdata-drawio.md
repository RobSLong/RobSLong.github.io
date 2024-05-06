---
title:  "Why use Drawio in data engineering?"
mathjax: true
layout: post
categories: media
---

<img src="/images/blogs/banners/2024-05-06-drawio.png">


# Summary
One of the key challenges in data engineering is understanding the flow of data through various systems and processes. Not all data engineers enjoy committing time to creating visualisations and this is where Draw.io steps in as a user-friendly interface for efficiently creating diagrams. Draw.io offers a collaborative toolkit for data engineers to map out the entire data flow from source to destination, making it easier to identify potential bottlenecks or inefficiencies and to communicate these results with less technical stakeholders.


# Examples
I use Draw.io as my go to tool for all of my data diagram needs; whether I need to create a rough diagram to communicate with business stakeholders or create a publication quality graphic. In this article, I will not give a deep dive into how to use Draw.io as many great tutorials and resources exist. Instead, I want to illustrate and demonstrate some of the diagrammatic capabilities that Draw.io empowers data engineers to use. In particular, I will show examples of an **Entity Relationship (ER) diagram, Data Flow diagram (DFD),** and an **architecture diagram**.


### ER diagrams
Whether it is planning a new data storage solution or understanding the relationships between tables in an existing database, entity-relationship (ER) diagrams will always be prominent in data engineering. Draw.io has a dedicated suite of tabular elements and connectors, which are typically used in ER diagrams to represent the different types of relationships between tables (e.g., many-to-one). A simple example visualising a collection of tables which describe the training courses individuals have taken is shown in Figure 2. Draw.io not only provides access to the geometric components to make the diagram but also offers full customisation; both to the table structures and aesthetics (e.g., table colouring).


<p>


![image info](../images/drawio/drawio-er.png)
<center>
<em>Figure 1: ER diagram </em>
</center>
</p>


### Data flow diagrams
**Data flow diagrams (DFD)** are key in the planning of new data projects and focus on illustrating the flow of data within a system. DFD provide a high-level overview of the data flow and highlights the interactions between different components within a system to help stakeholders understand the data processing logic.


The drag-and-drop experience in Draw.io enables data engineers to combine symbols (to represent data storage, etc.) with text blocks to interactively iterate the creation of data flow diagrams. The user can resize components or refactor the visualisation without having to delete content.


<p>    


![image info](../images/drawio/drawio-dataflow.png)
<center>
<em>Figure 2: Data flow diagram </em>
</center>
</p>


### Architecture Diagrams


Data engineers use **architecture diagrams** to visually represent the structure and components of a data system or application. These diagrams provide a high-level overview of the system's architecture, including data sources, processing components, data storage systems, and data flow paths. Architecture diagrams are an essential resource for data engineers to effectively plan, design, communicate, and troubleshoot data systems.


To accurately depict the specific components of the data architecture, Draw.io includes official symbols from a wealth of providers, such as Microsoft. Figure 3 shows an architecture diagram for an ingestion and analytics workload using components within Microsoft Azure's cloud offering. Draw.io allows the user to add numerical labels to arrows, which indicate the order of actions on a given diagram.


<p>


![image info](../images/drawio/drawio-architecture.png)
<center>
<em>Figure 3: Architecture diagram </em>
</center>
</p>


# Closing thoughts
In this article, I have demonstrated how Draw.io can be a useful low-code diagramming tool for diagrams typically created by data engineers.


**Ultimately, you get what you put in.** I know that within 5 minutes I can spin up a rough-and-ready diagram using Draw.io which can be used to drive conversation in a team meeting. Equally, if I need a report ready diagram, I know this is also achievable with a larger time investment.


So why do I advocate for Draw.io over other diagrammatic platforms?
1. Draw.io offers a secure solution; your diagram data only lives in your browser on your local device while you are working on it.
0. The diagrams can be version controlled by using the native .drawio files, allowing collaboration and best practices to be followed.
0. Static images, as shown in this article, are great for reports and team meetings, but Draw.io also offers animations that can be used to make more engaging diagrams for presentations.
0. For those who prefer to write their diagrams as code, Draw.io supports the Mermaid language (with a syntax similar to Markdown where you can use text to describe and automatically generate diagrams).


In closing, I hope that this article helped to inform you about whether or not Draw.io can be useful to you and potentially peaked enough interest for you to check it out!
