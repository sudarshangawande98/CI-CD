# Build and development automation

❇️ Build and development automation refers to the use of tools and processes to streamline and automate the various stages of software development, from writing and testing code to deploying applications.

## Key Concepts

<b>1. Continuous Integration (CI):</b> </br>
⁃ Integrates code changes from multiple contributors into a shared repository several times a day.</br>
⁃ Each integration is verified by an automated build to detect errors quickly.

<b>2. Continuous Delivery (CD):</b> </br>
⁃ Extends CI by automatically deploying all code changes to a testing or production environment after the build stage.</br>
⁃ Ensures the software can be reliably released at any time.

<b>3. Continuous Deployment:</b> </br>
⁃ Every change that passes all stages of the production pipeline is released to customers.</br>
⁃ No human intervention is required; only a failing test will prevent a new change to be deployed to production.

<b>4. Version Control:</b> </br>
⁃ Uses systems like Git to manage changes to source code over time.

<b>5. Build Automation:</b> </br>
⁃ Automates the process of compiling code, running tests, and creating deployment packages.</br>
⁃ Tools: Apache Maven, Gradle, Make, etc.

<b>6. Test Automation:</b> </br>
⁃ Automates the execution of tests to ensure code quality and functionality.</br>
⁃ Tools: JUnit

<b>7. Deployment Automation:</b> </br>
⁃ Tools: Kubernetes, Docker

## Common Tools and Platforms:

### Continuous Integration/Continuous Deployment (CI/CD) Tools
<b>1. Jenkins:</b></br>
⁃ Open-source automation server for building, deploying, and automating any project.</br>
⁃ Highly extensible with plugins.

### Build Tools
<b>1. Apache Maven:</b></br>
⁃ A build automation tool used primarily for Java projects.</br>
⁃ Manages project dependencies and lifecycle.

<b>2. Gradle:</b></br>
⁃ A build automation tool that builds upon the concepts of Apache Ant and Maven.</br>
⁃ Highly customizable and supports multi-project builds.

### Containerization and Orchestration
<b>1. Docker:</b></br>
⁃ Platform to develop, ship, and run applications in containers.</br>
⁃ Ensures consistent environments across development, testing, and production.

<b>2. Kubernetes:</b></br>
⁃ An open-source system for automating deployment, scaling, and management of containerized applications.</br>
⁃ Manages clusters of instances of applications.

### Workflow Example
<b>1. Code Commit:</b></br>
⁃ Developers commit code to a version control system like Git.

<b>2. CI Pipeline:</b></br>
⁃ Automated tests and builds are triggered by CI tools (e.g., Jenkins, Travis CI).</br>
⁃ If tests pass, a build artifact is created.

<b>3. CD Pipeline:</b></br>
⁃ The artifact is deployed to staging environments for further testing.</br>
⁃ Automated integration and acceptance tests are run.

<b>4. Production Deployment:</b></br>
⁃ Once the application passes all tests, it is automatically deployed to production.</br>
⁃ Monitoring tools keep track of the application’s health.
