# mandat-xsl
XML project for managing money transfer mandates using XML, DTD, XSD validation, XPath, and XSLT 3.0. Developed with Oxygen XML Editor and Saxon-PE to transform XML data into HTML reports and calculate mandate totals.

# Mandate Management – XML, DTD, XSD & XSLT

## Project Overview

This project focuses on managing and presenting money transfer mandates using XML technologies.

It demonstrates how to structure mandate information, validate XML documents, extract data using XPath, and transform XML data into an HTML report containing sender and recipient details, mandate statuses, and financial summaries.

## Technologies Used

- **XML** – Data structure and storage.
- **DTD** – Definition of XML document structure and rules.
- **XSD (XML Schema)** – Data validation and type definitions.
- **XPath** – XML data selection and extraction.
- **XSLT 3.0** – Transformation of XML documents into HTML.
- **HTML / CSS** – Styling and presentation of the generated report.
- **Oxygen XML Editor** – XML editing, validation, and transformation.
- **Saxon-PE 12.9** – XSLT transformation engine.

## Features

- Manage mandate information.
- Store mandate numbers, dates, amounts, and statuses.
- Manage sender and recipient information.
- Validate XML documents using DTD and XSD.
- Extract information using XPath expressions.
- Automatically generate HTML reports using XSLT.
- Calculate the total amount of all mandates.
- Calculate totals for received and non-received mandates.

## Project Structure

```text
XML-Mandats/
│
├── manda/
│   └── rapport2.xsl
│
├── manda2/
│   └── rapport1.xml
│
├── rapport.dtd
├── rapport.xsd
└── README.md
```

*The structure can be adjusted to match the actual organization of files in the repository.*

## How to Run

1. Open the XML and XSL files in Oxygen XML Editor.
2. Validate the XML document using the DTD or XSD schema.
3. Configure an XSLT transformation scenario.
4. Select **Saxon-PE 12.9** as the transformation engine.
5. Run the transformation to generate the HTML report.

## Sample Results

Using the demonstration XML data:

| Metric | Amount |
|---|---:|
| Total mandates | 4700 |
| Received mandates | 1500 |
| Non-received mandates | 3200 |

## Learning Objectives

This project provides practical experience with XML technologies, including data structuring, validation, querying, and transformation.

---

**Developed as part of a practical assignment on XML technologies.** 
<img width="1882" height="576" alt="image" src="https://github.com/user-attachments/assets/1bc3c261-07ea-46df-80f4-11986386ecbf" />
<img width="1920" height="1072" alt="image" src="https://github.com/user-attachments/assets/bc676161-ab8b-4b99-93ac-a7277ba84cb8" />

<img width="1258" height="789" alt="image" src="https://github.com/user-attachments/assets/bed5da9c-3089-46cf-95c9-3778b13f630a" />
<img width="1282" height="795" alt="image" src="https://github.com/user-attachments/assets/237036d4-1745-4986-828f-212d4faddef2" />
<img width="1027" height="803" alt="image" src="https://github.com/user-attachments/assets/deda7bfd-44eb-4e72-9295-005efd4347a1" />
<img width="1011" height="811" alt="image" src="https://github.com/user-attachments/assets/0ceb4285-aa9c-4f46-b17a-27e515becb5e" />



