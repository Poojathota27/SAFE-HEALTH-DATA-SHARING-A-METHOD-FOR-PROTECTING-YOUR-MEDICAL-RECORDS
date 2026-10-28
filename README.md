Safe Health Data Sharing: A Method for Protecting Your Medical Records
Overview
Safe Health Data Sharing is a Java/JSP web application project focused on managing and sharing medical records among different user roles. The source code includes pages for document owners, healthcare service providers, and health-system users, along with database scripts and supporting web assets.

This repository presents the project source code for learning, review, and further development. It should not be used with real patient information without a thorough security, privacy, and compliance review.
Main Features
Based on the included JSP page names and project files, the application includes workflows for:
- User registration and login
- Patient and clinical-report management
- Medical-document access requests and access-control workflows
- Key-request and key-response pages
- Viewing medical-record details and profiles
- Database-backed application pages
These descriptions reflect the available source filenames; functionality should be tested before being treated as production-ready.
Technology Stack
- Java Server Pages (JSP)
- Java Servlet web application components
- HTML, CSS, and JavaScript
- MySQL (the project includes a MySQL JDBC connector JAR and SQL scripts)
- A JSP/Servlet-compatible Java application server, such as Apache Tomcat
The ZIP contains legacy dependencies. Exact compatible Java, server, and database versions should be confirmed before running the application.
Repository Structure
Safe-Health-Data-Sharing/
├── Database/
│   ├── Database.sql
│   └── tables.sql
├── Gallery/
│   ├── connect.jsp
│   └── sample documents and image assets
├── WEB-INF/
│   ├── lib/
│   └── web.xml
├── css/
├── images/
├── js/
├── sources/
├── *.jsp
├── index.html
└── README.md
The exact files and folders may vary depending on which project assets are included in the repository. Preserve the original paths because JSP pages may reference them.
Setup Notes
This is a legacy JSP project, so it may require configuration before it runs.
1. Install a compatible JDK and a JSP/Servlet container such as Apache Tomcat.
2. Install MySQL and create a database for the project.
3. Review Database/Database.sql and Database/tables.sql. Import only the required schema and sample data into a development database.
4. Review connect.jsp and any other database configuration files. Configure database connection settings locally; do not commit real passwords or credentials.
5. Deploy the application to the compatible server and test the pages in a local development environment.
6. Check server logs and resolve dependency or compatibility issues as needed.
The repository does not currently guarantee a one-click installation. The original dependency versions and configuration may be outdated, and the application has not been independently validated in a modern environment.
Security and Privacy Notice
- Do not use real patient records or confidential health information in a public repository.
- Never commit database passwords, secret keys, private keys, or personal data.
- Review the authentication, authorization, encryption, and key-management implementation before relying on it for sensitive data.
- Use only synthetic or properly anonymized test data.
- Confirm the license and redistribution terms for third-party JARs, libraries, images, and sample files before publishing them.
Project Status
Academic / demonstration project. Further work is needed to validate compatibility, test security controls, document configuration, and assess privacy and compliance requirements before any real-world use.
