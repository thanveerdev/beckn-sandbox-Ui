## TL;DR

### Backend Setup
-   Set BPP Client URL and Base URL in .env
-   Run `npm install` and `npm run start:dev` to start sandbox
-   Set the `client.webhook.url` field in BPP Client config/default.yml to the address of this sandbox installation. (Previously you needed to configure a software called beckn-sandbox-webhook. That software is not required anymore.)

### Frontend Demo
-   Open `beckn-demo.html` in your browser for an interactive demonstration
-   No additional installation required - works out of the box
-   Demonstrates all Beckn domains with mock API responses

## Project Introduction/Overview

A sandbox environment typically replicates the necessary components of the production system but operates independently. It may include a separate server, database, network, and other resources. By isolating the sandbox environment from the production system, any errors, bugs, or vulnerabilities discovered during testing can be addressed without affecting live users or critical data.

## Release Notes

Latest version: 1.1.0

<!--
--Previous versions: Table having version number hyperlinked to Wiki page.
<Please follow a Tabular structure>

<Wiki Page of previous versions to have details such as Version number and corresponding features released>
-->

## Installation/Setup and User Guide

### Backend Installation

You can access the detailed Backend Installation and User Guide from [here](https://github.com/beckn/beckn-sandbox/blob/main/USER_GUIDE.md).

### Frontend Demo Installation

#### Quick Start (Recommended)
1. **Open the Interactive Demo:**
   ```bash
   open beckn-demo.html
   ```
   Or simply double-click the `beckn-demo.html` file in your file explorer.

2. **Explore Beckn Domains:**
   - Select any domain card (Mobility, Tourism, Retail, Healthcare, Education, Logistics)
   - Fill in the search parameters
   - View real-time Beckn API responses

#### Features of the Frontend Demo
- **🌐 Multi-Domain Support**: Demonstrates 6 key Beckn domains
- **🔍 Interactive Search**: Domain-specific search forms with real-time responses
- **📱 Responsive Design**: Works on desktop, tablet, and mobile devices
- **🎯 Educational**: Built-in explanations of Beckn protocol concepts
- **⚡ No Setup Required**: Pure HTML/JavaScript - runs in any modern browser

#### Advanced Frontend Development
If you want to develop a more advanced React-based frontend:

1. **Create React Frontend:**
   ```bash
   npx create-vite@latest beckn-frontend --template react-ts
   cd beckn-frontend
   npm install
   ```

2. **Install Additional Dependencies:**
   ```bash
   npm install axios @types/node
   ```

3. **Start Development Server:**
   ```bash
   npm run dev
   ```

4. **Configure API Endpoint:**
   Update the base URL in your API service to point to the running Beckn sandbox:
   ```typescript
   const baseUrl = 'http://localhost:3000';
   ```

#### Frontend Architecture
The demo showcases:
- **Unified API Structure**: Same request/response format across all domains
- **Context-Aware Searches**: Location and domain-specific parameters
- **Beckn Protocol Compliance**: Proper context, message, and catalog structures
- **Mock Data Integration**: Realistic responses for demonstration purposes

<!--
## Link to Experience Center
<Links to various environments of Experience Center to be listed here>

## Link to FRS document
<Wiki Page to have all the details for FRS; include Wiki page link here>

## Link to Test cases
< Details to be added to a new Wiki page and link to be included here >
-->

<!--
## License information
< License details to be added here >


## Contributing guidelines
< Contributor guidelines to be added in a Wiki Page and link to be included here >
-->

## Architecture Diagrams/Technical Overview

You can access the Architecture Diagrams and Technical Details [here](https://github.com/beckn/beckn-sandbox/blob/main/USER_GUIDE.md#Sandbox-Architecture).

## Link to Postman Collections

You can access the Postman Collection details [here](https://github.com/beckn/beckn-sandbox/blob/main/USER_GUIDE.md#Import-Collection-in-Postman).

## Frontend Demo

### Interactive Web Interface
The sandbox includes a comprehensive frontend demo (`beckn-demo.html`) that provides:

#### Supported Domains
- **🚗 Mobility**: Ride-hailing, public transit, transportation services
- **🏔️ Tourism**: Travel packages, hotels, adventure experiences  
- **🛒 Local Retail**: Groceries, electronics, local shopping
- **🏥 Healthcare**: Medical consultations, pharmacy, diagnostics
- **📚 Education**: Courses, training, educational services
- **📦 Logistics**: Package delivery, logistics services

#### Key Features
- **Domain Selection**: Interactive cards for each Beckn domain
- **Dynamic Forms**: Context-aware search forms for each domain
- **Real-time Responses**: Mock Beckn API responses with proper protocol structure
- **Educational Content**: Built-in explanations of Beckn protocol concepts
- **Mobile Responsive**: Works seamlessly across all devices

#### Usage
1. Open `beckn-demo.html` in any modern web browser
2. Click on a domain card to explore that sector
3. Fill in the search parameters specific to that domain
4. View the structured Beckn API response
5. Learn how the same protocol works across different industries

The demo showcases the power of Beckn's unified protocol - how the same API structure enables commerce across completely different industries.

<!--
## Applicable use cases
<Mention the applicable use cases of the application, if any>

## Gateway
<Mention the gateway details and links if applicable>
-->

## Registry

You can access the Registry Details [here](https://github.com/beckn/beckn-sandbox/blob/main/USER_GUIDE.md#Setting-Up-Instances-of-Protocol-Server).

<!--
## Sandbox
<Mention the sandbox details if applicable>

## Link to demos
<Mention the demo details/links if applicable>

## Environments
<Mention the environment details and links>

## Deployment
<Mention the deployment details and links>

## Related Repositories
<Mention the related repositories for the project, dependent repositories, backend APIs, hosting details and links>

## Related URLs
<Mention the related URLs for the repositories / project>
-->

## Troubleshooting Steps

You can access the Troubleshooting Steps [here](https://github.com/beckn/beckn-sandbox/blob/main/TROUBLESHOOT_GUIDE.md).

## Team Contact information

For technical support or issues related to installation, contact the following contributors:

1. https://github.com/shreyvishal
2. https://github.com/shenoyninad
