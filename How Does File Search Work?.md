# How Does File Search Work?

## Introduction

Material Security's file search interface provides a powerful tool for identifying and securing sensitive data stored in Google Drive. This comprehensive solution goes beyond the standard Google Workspace admin dashboard, offering advanced search capabilities, content analysis, and granular access control.

## Key Features

1. **Content Classification**: The file search engine uses a custom-built ML model, trained on years of email data, to categorize files into 16 different content types, including personal, financial, health, and confidential information.

2. **Metadata Search**: Users can easily search for files based on various metadata attributes, such as file name, ownership, type (e.g., spreadsheet, presentation), and location (personal or shared drives).

3. **Sharing Analysis**: The search interface provides detailed insights into how files are being shared, including external sharing, shared with specific individuals or groups, and files shared with public links.

4. **Content Analysis**: For files identified as containing sensitive information, the system will provide a detailed analysis of the file contents, highlighting specific data points like credit card numbers, social security numbers, and other confidential information.

5. **Remediation Actions**: Users can quickly revoke external access to files, either individually or in bulk, with the option to maintain existing internal permissions or restrict access altogether.

## How to Use the File Search Interface

1. **Content Classification**: Start by exploring the available content classification categories, such as "Personal," "Financial," and "Confidential," to get a high-level overview of the types of sensitive data stored in your Google Drive.

2. **Metadata Filtering**: Use the various metadata filters to narrow down your search, such as file type, owner, and location. This allows you to quickly identify high-risk areas, like files shared with external parties or stored in shared drives.

3. **Sharing Analysis**: Dive deeper into the sharing permissions for each file, understanding who has access and whether that access is appropriate. The interface clearly displays the different access levels, including "Anyone with the link," which poses the greatest risk.

4. **Content Analysis**: For files flagged as containing sensitive information, review the detailed content analysis to understand the specific data points that were identified. This can help you prioritize your remediation efforts.

5. **Remediation**: Leverage the bulk revocation capabilities to quickly remove external access to high-risk files. You can choose to maintain existing internal permissions or restrict access altogether, depending on your organization's security policies.

## Roadmap and Future Enhancements

The Material Security team is actively working on enhancing the file search capabilities based on customer feedback. Upcoming features include:

1. **Trusted Domains**: The ability to define a list of trusted domains, allowing you to focus your remediation efforts on files shared with external, untrusted parties.

2. **Automated Alerts and Remediation**: Integration with webhooks and other notification systems to proactively alert file owners and administrators of potential risks, with the option to automate certain remediation actions.

3. **Expanded Content Analysis**: Continued improvements to the ML-based content classification, with the goal of providing even more accurate and comprehensive insights into the sensitive data stored in your Google Drive.
