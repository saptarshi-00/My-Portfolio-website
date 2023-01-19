---
title: About
layout: PageLayout
colors: colors-a
backgroundImage:
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      #### I am Saptarshi Bandyopadhyay, a Power BI Data Analyst at Cognizant. I
      have around 1.5 years of experience in Azure Data Factory, Azure
      Databricks, SQL, DAX, Python, Power BI,Pyspark and Powershell. I have
      worked on both data engineering and data analysis team.


      #### I am an active learner willing to learn new technologies while adding
      value to the organisation. Proficient in English language to convince
      potential customers and clients.

    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: SQL
      - type: Label
        label: Python
      - type: Label
        label: Azure Data Factory
      - type: Label
        label: Azure Databricks
      - type: Label
        label: Power BI
      - type: Label
        label: DAX
      - type: Label
      - type: Label
        label: Swift
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: >+
          **Aug 2022 - Present : Cognizant Technology Solutions**


          **Programmer Analyst (Data Analyst)**


          > Technologies used : Power BI, SQL, DAX, ORACLE, Denodo


          *   Developed a Power BI reports and dashboards for the client R\&D
          team.


          *   Worked on the migration of old cognos report into Power BI reports
          and converted cognos SQL to equivalent DAX syntax.


          *   Single handedly worked on the optimization of query to enhance the
          performance of reports and dashboard in dev environment.


          **Aug 2021 - Aug 2022 : Cognizant Technology Solutions**


          **Programmer Analyst Trainee (Data Engineer)**


          > Technologies used : Azure Data Factory, Azure Databricks, Pyspark,
          Python, SQL, Powershell


          *


          **Jan 2021 - Jul 2021 : Cognizant Technology Solutions**


          **Intern ( Azure cloud stack Intern)**


          > Technologies used : SQL, Microsoft Azure, Hadoop, Pyspark


          *   Extensively worked on the development of Timesheet Management
          System, where employees can log their daily work timings. Single
          Handedly worked on the creation of database for this project using
          MySQL.

          *   Gained Knowledge and insights on Azure, Hadoop and other Bigdata
          technologies through knowledge transfer sessions and several handson
          activities.

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: EDUCATION
        text: |+
          *   **B.Tech in Mechanical Engineering ( 2017-2021)**

          > Kalyani Government Engineering College, West Bengal
          >
          > 8.76 (DGPA)

          *   **High School : AISSCE (2017)**

          > Bholananda National Vidyalaya
          >
          > 77 %

          *   **High School : CISCE (2015)**

          > Assembly of Angels' Secondary School
          >
          > 89.5%

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
          subtitle:
            fontWeight: 500
            textDecoration: underline
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
