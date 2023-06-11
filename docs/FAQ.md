---
sidebar_position: 8
---
# Frequently Asked Questions

## Q1: Can I add authentication to Stirling PDF?
No, Stirling PDF doesn't support built-in authentication, and it is not a planned feature. For secure access, we recommend implementing an external, trusted authentication solution such as Authentik or Authelia.

## Q2: What new features are planned for Stirling PDF?
Some of the upcoming features include: 
- Progress bar/Tracking: To give you a real-time update on ongoing operations.
- Custom logic pipelines: To combine multiple operations.
- Folder support: To automate operations on the contents of a folder.
- Auto rename: To rename files based on their title text.

## Q3: Why are .htm files being downloaded when I use the application?
This is often caused by your NGINX configuration. NGINX's default file upload size is 1MB, and any file larger than this will cause an .htm file to be downloaded instead. To fix this issue, you should modify your NGINX configuration to increase the maximum file upload size.

## Q4: Can I customize the appearance and language of the Stirling PDF application?
Yes, Stirling PDF provides several environment variables to allow customization of the application, including the name, description, default language, and visibility to search engines. Please refer to the "Customisation" section for more details.

## Q5: I want to add a new feature to Stirling PDF. How can I contribute?
We welcome contributions from the community! Please open an issue on our GitHub page to discuss the feature before making any changes. After the feature has been discussed and approved, you can make the changes and submit a pull request.

## Q6: I found a bug in Stirling PDF. Where can I report it?
Please report any bugs or issues you encounter through our GitHub Issues page. Be sure to include as much detail as possible so we can diagnose and resolve the issue quickly.