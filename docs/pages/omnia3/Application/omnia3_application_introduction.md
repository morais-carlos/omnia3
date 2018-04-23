---
title: OMNIA 3.0 Application Introduction
keywords: omnia3
summary: "OMNIA 3.0 Application Introduction"
sidebar: omnia3_sidebar
permalink: omnia3_application_introduction.html
folder: omnia3
---


## 1. Introduction

Business applications, in the OMNIA platform, are  generated from the model. They can be utilized via the API directly or via the user interface.

## 2. Understanding the menu

Via the user interface, when you login and select a tenant, you will be shown a default menu in the sidebar that allows you to access the different options.

The organization of the menu is:
- **Documents**: Contains all of the modeled Documents.
- **Configuration**: Contains all of the modeled non-document entities: Agents, Resources and Generic Entities.
- **Series**: Contains all of the modeled Series.
- **Dashboards**: Contains all the modeled Dashboards.

## 3. Using the application

Every application modeled will have its own usage flow and criteria. However, the general logic will be:

- **Agents, Resources and Generic Entities** must be created first, as they can depend on each other, but cannot depend on Commitments, Events or Resources.
- Every Document has a **Serie** associated. This means that you must configure that document's serie before being able to create documents.
- **Commitments** and **Events** cannot be created separately, and only exist in the context of documents.
- After having all this information, you can create **Documents**. Commitments and/or Events are displayed as "lines" in the form, if using the application via the OMNIA UI.