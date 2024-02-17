# Project: Azure Database Migration

## Introduction
I embarked on this project on December 14, 2023, with the primary objective of demonstrating my capability in architecting and implementing a cloud-based database system on Microsoft Azure. This endeavor is a testament to my hands-on expertise in cloud engineering, beginning with the establishment of a production environment database. Following this, my focus will shift towards migrating the database to Azure SQL Database, showcasing the practical steps and methodologies involved in leveraging cloud technologies for optimal database management and deployment.

## Achievements

- **Milestone 1: Setting Up the Environment**
  
  The first milestone of this project involved setting up the production environment, a task that proved to be quite straightforward given the comprehensive prerequisite information provided. I was able to successfully establish myself on Microsoft Azure, laying the foundational stone for the subsequent phases of this project.

- **Milestone 2: Setting Up the Production Environment**

  The task of setting up the production environment marked the most challenging milestone I have encountered throughout the course. Initially, I faced difficulties due to some early mistakes in the project, particularly when these errors began to emerge during this phase. Despite these setbacks, I managed to establish a solid foundation for my cloud-based database system on Azure, beginning with the successful provisioning of a Windows Virtual Machine. Initially, I mistakenly provisioned a Linux VM, which was a significant oversight. Recognizing and rectifying this error was a crucial turning point. Subsequently, I was able to move forward with installing SQL Server and SQL Server Management Studio (SSMS), securing the essential tools for effective database management. Furthermore, I successfully restored the database required for the upcoming migration task. Completing this milestone was immensely satisfying, as it represented a significant achievement amidst the challenges posed by the initial missteps that significantly impacted my progress.

- **Milestone 3: Migrating to Azure SQL Database**

  Successfully migrating a database from my local (on-premises) server to my Azure server using Azure Data Studio marked the third milestone of this project. This phase allowed me to learn the end-to-end process of database migration comprehensively. Reflecting on the challenges encountered, one significant hurdle was navigating user permissions. During the migration process, I realized the need to halt and modify my user permissions to apply the migration changes effectively and validate the process. Overcoming this challenge was pivotal in understanding the intricacies of cloud-based database management. Celebrating the successful completion of this phase, I found it to be somewhat smoother than Milestone 2, albeit not without its own set of challenges. The experience gained from navigating these hurdles has been invaluable, enhancing my understanding and skills in cloud database migration. This milestone, while challenging, has been a rewarding demonstration of the progress achievable through persistence and adaptability.

- **Milestone 4: Database Back Up and Restore**
  
  Here, I focused on implementing a robust backup and restore strategy for the database. This involved ensuring that the critical data stored in the database could be safely backed up and restored in case of unexpected incidents or data loss scenarios. By achieving this milestone, I aimed to enhance the resilience and reliability of the database system, thereby safeguarding the integrity of the data and ensuring business continuity.

    *Steps Taken for Database Backup:*
    
    - Evaluation of Backup Requirements: I began by assessing the backup requirements, considering factors such as data volume, frequency of updates, and recovery point objectives (RPOs) to determine the appropriate backup strategy.
    - Configuration of Backup Settings: Using SQL Server Management Studio (SSMS), I configured backup settings such as the backup type (full, differential, or transaction log), backup destination, and retention policies to meet the defined backup requirements.
    - Execution of Backup Operations: With the backup settings in place, I executed backup operations using SSMS, initiating full database backups to capture the entire database state at specific points in time.
    - Verification of Backup Completion: After each backup operation, I verified the completion and integrity of the backup files generated, ensuring that they were successfully stored in the designated backup destination without errors.
    - Testing of Restore Process: To validate the effectiveness of the backup strategy, I performed test restores from the backup files to a separate environment, confirming that the restored database retained its integrity and consistency.

  By meticulously following these steps, I successfully established a comprehensive backup and restore mechanism for the database, ensuring the availability and recoverability of critical data assets in the Azure environment. This milestone underscores the importance of proactive data protection measures in maintaining the resilience and continuity of cloud-based database systems. 

- **Milestone 5: Disaster Recovery Simulation**
- **Milestone 6: Georeplication Failover**
- **Milestone 7: Microsoft Entra Directory Migration**

## Conclusion
Summarise the project outcomes and any future plans or improvements.

