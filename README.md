# 💹 Financial Advisory System

## Overview

The decision to tackle this problem statement stems from enhancing financial advisory services through advanced technology like generative AI, offering:

- **🎯 Personalization**: Tailored investment strategies based on individual customer data, aligning with specific goals and risk profiles.
- **⏱️ Real-time Adaptability**: Continuous monitoring of market trends for timely adjustments to investment recommendations.
- **📈 Scalability**: Ability to reach a broader audience with personalized advice without compromising quality.
- **🔍 Transparency and Trust**: Explaining AI-driven recommendations fosters customer trust by demonstrating how decisions are made, enhancing confidence in the advisory process.

## Tools and Resources Used

- **📥 Data Ingestion and Storage**: 
  - Azure Data Factory for automated data ingestion.
  - Blob Storage for scalable storage.

- **📊 Data Processing and Analytics**: 
  - Azure Synapse Analytics and Databricks for large-scale data processing and analysis.

- **🗄️ Database Solutions**: 
  - Azure SQL Database for structured data.
  - Cosmos DB for unstructured data storage.

- **🤖 AI and Machine Learning**: 
  - Azure Machine Learning and Cognitive Services for building generative AI models.

- **🔄 Real-Time Data Management**: 
  - Azure Event Hubs and Stream Analytics for real-time data ingestion and processing.

- **🌐 Application Hosting and API Management**: 
  - Azure App Service hosts web apps securely.
  - API Management manages APIs.

- **🔐 Security and Identity Management**: 
  - Azure Active Directory for secure access.
  - Key Vault for managing secrets.
  - Security Center for continuous security monitoring.

## Key Differentiators & Adoption Plan

- **🎯 Personalization**: Offers highly personalized financial advice using real-time and historical data.
- **📈 Scalability**: Azure's cloud infrastructure ensures scalability to accommodate growth without compromising performance.
- **💡 User Experience**: Enhances user experience through a responsive, intuitive web interface and real-time advisory capabilities.
- **🔒 Security**: Implements robust security measures with Azure Active Directory, Azure Key Vault, and Azure Security Center to safeguard user data and system integrity.

## Business Potential and Relevance

- **🤝 Customer Engagement**: Enhances customer engagement by offering tailored financial insights and advice.
- **📊 Operational Efficiency**: Streamlines financial advisory processes with automated data handling and real-time analytics.
- **🏆 Competitive Advantage**: Positions businesses ahead by leveraging advanced AI capabilities to deliver superior financial services.

## Uniqueness of Approach and Solution

- **🧠 Integration of Generative AI**: Uses AI for personalized financial advice, combining structured and unstructured data sources.
- **⏱️ Real-Time Advisory**: Provides immediate insights based on live market data, enhancing decision-making.
- **🌐 Cloud-Based Scalability**: Azure infrastructure ensures scalability and reliability for growing customer bases.

## System Design

![System Design](https://github.com/Aakashdeep-Srivastava/Financial_Advisory/blob/main/_Bank%20of%20Baroda%20Hackathon%202024.png)

## Web Application

![Web Application](https://github.com/Aakashdeep-Srivastava/Financial_Advisory/blob/main/Webapp.png)

## APIs Used

- [Azure Data Factory REST API](https://docs.microsoft.com/en-us/rest/api/datafactory/)
- [Azure Synapse Management REST API](https://docs.microsoft.com/en-us/rest/api/synapse/)
- [Azure Machine Learning Python SDK](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/?view=azure-ml-py)
- [Azure Event Hubs REST API](https://docs.microsoft.com/en-us/rest/api/eventhub/)
- [Azure App Service Management REST API](https://docs.microsoft.com/en-us/rest/api/appservice/)
- [Microsoft Graph API](https://docs.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [Azure Key Vault REST API](https://docs.microsoft.com/en-us/rest/api/keyvault/)

## Data Sources

- **Customer Financial Data Sources**:
  - Banking transactions
  - Investment portfolios
  - Financial statements
  - Credit card transactions

- **Real-Time Data Sources**:
  - Live market feeds:
    - [📈 Yahoo Finance API](https://www.yahoofinanceapi.com/)
    - [📊 Alpha Vantage API](https://www.alphavantage.co/)
    - [📉 IEX Cloud API](https://iexcloud.io/)
  - Economic news and events:
    - [📰 News API](https://newsapi.org/)
    - [💼 Financial Times API](https://developer.ft.com/portal/docs)
    - [📺 Bloomberg API](https://www.bloomberg.com/professional/product/api/)
  - Customer interactions:
    - [☎️ Twilio API](https://www.twilio.com/docs/usage/api)
    - [💬 Intercom API](https://developers.intercom.com/intercom-api-reference/reference)
