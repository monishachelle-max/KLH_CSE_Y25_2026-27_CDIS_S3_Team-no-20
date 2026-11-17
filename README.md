Act as a professional technical documentation engineer. Analyze my existing project files and create a complete, professional, beginner-friendly `README.md` file for my CDIS project.

**Project Title:**
CloudVault: Design and Implementation of a Secure and Scalable Cloud-Based File Storage and Backup System Using AWS

**Team Members:**

1. MONISHA RAGHINI CHELLE – 2520030537
2. NALIVENI SAI PRANAVI – 2520030514
3. GURRAPU NIKSHITHA – 2520030512

**Supervisor Name:** Dr.S.Vinay Kumar

### README.md must contain the following sections:

1. **Project Title**
   - Display the complete project title.
   - Include a short project tagline.

2. **Team Members**
   - Include all three members' names and ID numbers in a professional table.
   - Include the supervisor's name.

3. **Abstract**
   - Explain the purpose of CloudVault.
   - Describe how it provides cloud-based file storage, file management, and backup/recovery capabilities using AWS.

4. **Problem Statement**
   - Explain the limitations of traditional storage:
     - Limited accessibility.
     - Storage constraints.
     - Security concerns.
     - Risk of data loss.

5. **Project Objectives**
   - Centralized cloud storage.
   - Flexible file access.
   - Backup and recovery using file versioning.
   - Cloud security using IAM.
   - Practical implementation of cloud infrastructure.

6. **Technologies and AWS Services**
   Explain the role of each technology:
   - HTML, CSS, JavaScript – Frontend.
   - Python Flask – Backend.
   - Boto3 – AWS SDK for Python.
   - Amazon S3 – File storage.
   - Amazon EC2 – Application hosting.
   - AWS IAM – Identity and access management.
   - Amazon VPC – Cloud networking.
   - Nginx – Web server.
   - Terraform – Infrastructure as Code.
   - Amazon CloudWatch – Monitoring.
   - AWS CloudTrail – Activity logging.

7. **System Architecture**
   - Explain how the frontend, Flask backend, Boto3, Amazon S3, and EC2 interact.
   - Include a simple Mermaid architecture diagram if appropriate.

8. **Project Functionalities**
   - File upload.
   - File storage.
   - File listing.
   - File download.
   - File deletion.
   - File versioning.
   - Backup and recovery.
   - Cloud hosting.
   - Access management.

   Important: Verify each functionality against the actual source code. Clearly distinguish implemented features from planned features.

9. **Project Folder Structure**
   - Inspect the actual project directory.
   - Document the existing folder and file structure.
   - Do not invent files or folders.

10. **Prerequisites**
    - Python.
    - Visual Studio Code.
    - AWS account.
    - AWS CLI.
    - Required Python packages.
    - Git (if applicable).

11. **Setup and Installation Instructions**
    Provide step-by-step instructions for:
    - Cloning or opening the project.
    - Creating a Python virtual environment.
    - Activating the virtual environment on Windows.
    - Installing dependencies from requirements.txt.
    - Configuring AWS credentials securely.
    - Configuring the S3 bucket and required IAM permissions.
    - Running the Flask backend.
    - Opening the frontend/application in a browser.

12. **Execution Instructions**
    - Include the exact commands required to run the application.
    - Explain the local application URL.
    - Explain how to test the available functionalities.

13. **AWS Configuration**
    - Explain the purpose of S3, EC2, IAM, and VPC.
    - Include only configurations verified in the project.
    - Never include actual AWS access keys, secret keys, passwords, or private key contents.

14. **Current Project Phase and Status**
    - Inspect the actual project and identify completed, in-progress, and planned activities.
    - Include a status table with columns: Component, Current Status, and Description.
    - Do not mark a feature as completed unless there is evidence in the source code or verified deployment.
    - Clearly mention pending integrations and future enhancements.
    - Do not falsely claim Terraform automation, complete backup/recovery, monitoring, or production deployment if they have not been implemented.

15. **Future Enhancements**
    - User authentication.
    - Improved file sharing.
    - Automated backup scheduling.
    - Advanced monitoring.
    - Infrastructure automation using Terraform.

16. **Conclusion**
    - Summarize the project's purpose and learning outcomes.

### Documentation Requirements
- Use clean, professional GitHub Markdown.
- Add appropriate headings, tables, lists, and code blocks.
- Keep explanations understandable for beginners.
- Use accurate commands based on the existing project.
- Do not fabricate implementation details.
- Use placeholders wherever information is missing, especially the supervisor's name.
- Do not expose credentials or sensitive information.
- Inspect the actual project files before writing the README.
- Create or update the `README.md` file in the root directory of the project.
- Do not modify the application's source code.

Finally, review the completed README.md to ensure that all required sections are present and that the setup and execution instructions match the actual project.