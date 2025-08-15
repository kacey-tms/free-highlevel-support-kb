**Date Updated:** 2025-07-15T01:47:40.000Z

  
This article will show you how to leverage the new GoHighLevel MCP (Model Context Protocol) server to empower your AI agents and copilots to access GoHighLevel data and tools seamlessly — all via a secure, standardized HTTP protocol.

**TABLE OF CONTENTS**

* [What is the MCP Server?](#What-is-the-MCP-Server?)
* [Key Benefits of Using the MCP Server](#Key-Benefits-of-Using-the-MCP-Server)
* [Top 21 Tools Available](#Top-21-Tools-Available)
* [Example Tool Call](#Example-Tool-Call)
* [Roadmap & Vision](#Roadmap-&-Vision)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Next Steps](#Next-Steps)

---

# What is the MCP Server?

The GoHighLevel MCP server is a standardized, secure protocol that allows AI agents to read and write data in GoHighLevel without needing SDKs or deep custom integrations. You can now give agents access to critical tools like Calendar, Contacts, Conversations, Opportunities, and Payments through a single, unified interface.

## Key Benefits of Using the MCP Server

Connecting your AI agents to GoHighLevel has never been easier or safer.

* Standardized Access: Query and update data through a unified protocol.
* Fast Integration: No SDKs required; works with any HTTP-supporting client.
* Secure: Uses private integration tokens (PITs) for granular, permission-based access.
* Scalable: Designed for future expansion to 250+ tools.
* Flexible: Supports popular clients like Cursor, Windsurf, and OpenAI Playground.

## Top 21 Tools Available

Below is the initial set of tools your AI agents can use today:

| #  | Tool                  | Endpoint                           | Description                                               |
| -- | --------------------- | ---------------------------------- | --------------------------------------------------------- |
| 1  | Get Calendar Events   | calendars\_get-calendar-events     | Get calendar events using userId, groupId, or calendarId. |
| 2  | Get Appointment Notes | calendars\_get-appointment-notes   | Retrieve notes for a specific appointment.                |
| 3  | Get All Tasks         | contacts\_get-all-tasks            | Retrieve all tasks for a contact.                         |
| 4  | Add Tags              | contacts\_add-tags                 | Add tags to a contact.                                    |
| 5  | Remove Tags           | contacts\_remove-tags              | Remove tags from a contact.                               |
| 6  | Get Contact           | contacts\_get-contact              | Fetch contact details.                                    |
| 7  | Update Contact        | contacts\_update-contact           | Update a contact.                                         |
| 8  | Upsert Contact        | contacts\_upsert-contact           | Update or create a contact.                               |
| 9  | Create Contact        | contacts\_create-contact           | Create a new contact.                                     |
| 10 | Get Contacts          | contacts\_get-contacts             | Fetch all contacts.                                       |
| 11 | Search Conversation   | conversations\_search-conversation | Search/filter/sort conversations.                         |
| 12 | Get Messages          | conversations\_get-messages        | Retrieve messages by conversation ID.                     |
| 13 | Send a New Message    | conversations\_send-a-new-message  | Send a message to a conversation thread.                  |
| 14 | Get Location          | locations\_get-location            | Get location details by ID.                               |
| 15 | Get Custom Fields     | locations\_get-custom-fields       | Retrieve custom field definitions for a location.         |
| 16 | Search Opportunity    | opportunities\_search-opportunity  | Search for opportunities by criteria.                     |
| 17 | Get Pipelines         | opportunities\_get-pipelines       | Fetch all opportunity pipelines.                          |
| 18 | Get Opportunity       | opportunities\_get-opportunity     | Fetch opportunity details by ID.                          |
| 19 | Update Opportunity    | opportunities\_update-opportunity  | Update opportunity details.                               |
| 20 | Get Order by ID       | payments\_get-order-by-id          | Retrieve payment order details.                           |
| 21 | List Transactions     | payments\_list-transactions        | Fetch paginated list of transactions.                     |

How To Set Up the MCP Server

### Step 1: Configure Your Agent/Client

Add the MCP endpoint and headers to your agent configuration:

json

CopyEdit

{

 "mcpServers": {

 "prod-ghl-mcp": {

 "url": "https://services.leadconnectorhq.com/mcp/",

 "headers": {

 "Authorization": "Bearer <your-token>",

 "locationId": "<sub-account-id>"

 }

 }

 }

}

  
### Step 2: Get Your Private Integration Token (PIT)

1. Go to Settings → Private Integrations in your GoHighLevel location.
2. Click Create New Integration.
3. Select the required scopes (listed below).
4. Copy and securely store your token.

#### Required Scopes

Make sure your PIT includes:

* View/Edit Contacts
* View/Edit Conversations
* View/Edit Conversation Messages
* View/Edit Opportunities
* View Calendars & Calendar Events
* View Locations
* View Payment Orders & Transactions
* View Custom Fields
* View Forms

### Step 3: Start Building!

Your agents can now call tools using natural language instructions, seamlessly translated into secure API calls via MCP.

## Example Tool Call

Python example:

python

CopyEdit

import requests

  
headers = {

 "Authorization": "Bearer YOUR\_PIT\_TOKEN",

 "locationId": "YOUR\_LOCATION\_ID"

}

  
data = {

 "tool": "contacts\_get-contact",

 "input": {

 "contactId": "abc123"

 }

}

  
response = requests.post(

 "https://services.leadconnectorhq.com/mcp/",

 headers=headers,

 json=data

)

  
print(response.json())

  
## Roadmap & Vision

The current MCP release is just the beginning. Our roadmap includes:

* Individual MCP servers dedicated to specific services for targeted workflows.
* npx package to support clients without native HTTP support (e.g., Claude Desktop).
* OAuth support for advanced authorization flows.
* Expansion to 250+ tools to create a true unified orchestrator layer for AI agents.
* Enable complete automation of business processes across all GoHighLevel modules.

---

## Frequently Asked Questions

Q: Can I use this with OpenAI Playground or Claude?  
 Yes! Any client supporting HTTP requests can integrate with MCP.

Q: Do I need to install an SDK?  
 No SDK is required — MCP uses a standard HTTP protocol.

Q: Is my data secure?  
 Yes. Data access is fully scoped via Private Integration Tokens and secured through HTTPS.

Q: Can I restrict what tools an agent can use?  
 Yes. You can control access by limiting scopes in your PIT.

Q: What if I need a new tool or endpoint?  
 Reach out with feedback! We're actively expanding the available toolset.

### Next Steps

* Create your Private Integration Token and configure scopes.
* Update your AI agent or client configuration with the MCP endpoint.
* Start building agent-driven automations and integrations today!
* Provide feedback to help shape future expansions and new tool support.
  
  