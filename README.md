**OmniStudio Contact Search Feature**

This repository contains a Contact Search implementation using Salesforce OmniStudio. It allows users to search for contacts using multiple fields and displays results in a structured table. Users can select a contact, and the Omniscript updates with the selected contact’s details.


**🚀 Features**

Multiple Search Filters: Search using First Name, Last Name, Date of Birth, Email, or Phone Number.

Search Results Display: Results are shown in a table with pagination for handling large datasets.

Single Contact Selection: Selecting a contact automatically updates the Omniscript with relevant details.

OmniStudio Components: Built using FlexCards, OmniScripts, and Integration Procedures for efficient and scalable implementation.

No Custom Development: This project follows a no-code approach, relying on standard OmniStudio tools.


**📂 Components Used**

OmniScript: Manages the user interface and handles search input.

FlexCard: Displays search results in a structured, user-friendly table.

Integration Procedure: Fetches contact data dynamically using search filters.

DataRaptor (Extract & Transform): Retrieves and formats the contact data.


**🔧 Installation & Setup**

**Prerequisites**

Salesforce Org with OmniStudio Enabled: Ensure you have access to OmniStudio components.

Salesforce CLI (optional, for deployment): Download Here

OmniStudio Tools: Ensure your org has OmniStudio Admin and Developer permissions.


**Clone this Repository**
```
git clone https://github.com/your-username/omnistudio-contact-search.git
```

**Deploy the Components**

If using Salesforce CLI, navigate to the project directory and push the metadata:
```
sfdx force:source:push -u <your-org-alias>
```

Or manually import OmniStudio JSON files into your org.


**💡 Use Case**

Customer Support Teams: Quickly search and retrieve customer contact details.

Sales Representatives: Fetch customer information for engagement.

Admin Users: Provide a seamless way to access contact details.


**🌟 Future Enhancements**

✅ Multi-Select Contacts: Allow selection of multiple contacts at once.

✅ Export Search Results: Add an option to download search results as CSV.

✅ Advanced Filtering: More filter options like Custom Fields.

✅ Enhanced UI: Improve table design with sorting and additional actions.


**📌 Notes**

This project is built using OmniStudio's standard features.

Ensure that OmniStudio is enabled in your Salesforce org.

For deployment issues, check OmniStudio Runtime Permissions.


**📽️ Demo & Documentation**

Video Walkthrough: Google Drive Link (Upload your demo video & add link here)

Step-by-Step Guide: Documentation.md (Create this file if needed)
