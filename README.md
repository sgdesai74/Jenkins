# Jenkins

Key Tools and Technologies used
1. Jenkins: Automation server used for continuous integration and continuous delivery (CI/CD).
2. AWS EC2: Virtual machine in the cloud where Jenkins is hosted.
3. Apache Ant: Build tool integrated with Jenkins for compiling and running Java-based projects.
4. Git: Version control system used to manage the source code repository.
5. GitHub: Platform where the source code repository is hosted, and you will fork and clone the repository.
6. AWS IAM: Identity and Access Management for secure access to the AWS Management Console.
7. Bash/Shell Scripting: Used to install and configure necessary tools like Ant and Git on the EC2 instance.

Task Details
1. Sign in to AWS Management Console or Via CLI 
2. Connect to the EC2 instance
3. Setup Jenkins in EC2 instance
4. Connect Ant with Jenkins
5. Create a GIT repository
6. Create a job in Jenkins and integrate Ant

Architecture Diagram -

Fingerprints and Artifacts in Jenkins :-

In Jenkins, artifacts are files generated as output by a job during its build process. These files can include reports, compiled binaries, configuration files, or any other output that needs to be preserved after a job is completed. Artifacts play a crucial role in continuous integration (CI) and continuous delivery (CD) workflows as they allow users to inspect, share, or promote build outputs across various stages of a pipeline.

Fingerprints in Jenkins, on the other hand, provide a unique identifier (or hash) for files or artifacts. They are used to track where and how files are being utilized across different jobs, builds, and environments. Fingerprinting enables traceability of files, making it easier to follow their usage across multiple Jenkins jobs and workflows.

Benefits of Fingerprints and Artifacts in Jenkins:
1. Traceability: Track file usage across different jobs and builds.
2. Artifact Management: Preserve build outputs for review, sharing, or promotion.
3. File Integrity: Ensure file consistency through fingerprint comparison.
4. Version Control: Maintain versioned snapshots of build outputs.
5. Cross-Job Collaboration: Share and track files between jobs for team collaboration.
6. Build Reproducibility: Ensure consistent builds with archived artifacts.

Features of Fingerprints and Artifacts in Jenkins:
1. Artifact Archiving: Store and retain build outputs for future use.
2. Artifact Promotion: Reuse artifacts across environments without rebuilding.
3. File Fingerprinting: Generate unique file hashes to track files.
4. Tracking File Usage: View file flow through the CI/CD pipeline.
5. Security and Integrity: Detect file changes or corruption through fingerprinting.
6. Build Visibility: Access build outputs and file usage for better transparency.

<img width="1150" height="911" alt="image" src="https://github.com/user-attachments/assets/d7a1f16b-76f6-486b-b2c7-05d45d660943" />

