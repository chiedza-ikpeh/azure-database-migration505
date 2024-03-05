# Project: Azure Database Migration

## Introduction
I commenced this project on December 14, 2023, with the primary objective of demonstrating my capability in architecting and implementing a cloud-based database system on Microsoft Azure. This endeavour is a testament to my hands-on expertise in cloud engineering, beginning with the establishment of a production environment database. Following this, my focus will shift towards migrating the database to Azure SQL Database, showcasing the practical steps and methodologies involved in leveraging cloud technologies for optimal database management and deployment. I successfully completed the project on March 5, 2024.

***Click here to view the Project UML diagram***

## Milestone Achievements

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

  During this phase, I encountered significant challenges that prolonged the duration of the task beyond my initial estimates. Despite meticulous planning and preparation, unforeseen hurdles arose during the delete and restore process, leading to delays in completion. These challenges encompassed a variety of technical and operational issues, which required extensive troubleshooting and investigation to overcome. However, after dedicating additional time and effort to address these obstacles, I ultimately achieved success in executing the delete and restore process. This experience served as a valuable learning opportunity, highlighting the importance of resilience, perseverance, and continuous improvement in navigating complex tasks within the Azure Database Migration project. For the disaster recovery simulation, I intentionally deleted critical data from the production database to replicate a scenario where data integrity is compromised. The following steps outline the delete and restore process, along with documentation of the simulation:
  
  1. **Delete Process:**
     - Executed DELETE statements in SQL Server Management Studio (SSMS) to remove specific data from the database.
     - Documented the simulated data loss, including affected tables, rows, and conditions, in the README file.
  
  2. **Restore Process:**
     - Restored the database from a recent backup using Azure portal.
     - Referenced the documentation created in Step 1 as a blueprint for restoring the critical data lost during the simulation.
  
  3. **Validation:**
     - Used Azure Data Studio to connect to the restored database and verified that the critical data was successfully recovered.
     - Documented the success of the restoration process in the README file.

- **Milestone 6: Georeplication Failover**

  As I approached the conclusion of this project, the successful setup of geo-replication for the production Azure SQL Database brought a sense of relief and satisfaction. This critical step in fortifying the database system against potential disasters or disruptions was meticulously executed. Leveraging the Azure Portal, I configured a synchronized replica of the primary database in a separate geographical region, ensuring seamless synchronization between the two databases. Monitoring the replication status provided valuable insights into the effectiveness of the setup, reaffirming the importance of proactive disaster recovery measures. The geographical separation not only minimized shared risks but also bolstered overall data availability and integrity, marking a significant milestone in the optimization of database management and deployment on Microsoft Azure.
  
- **Milestone 7: Microsoft Entra Directory Migration**
  
  As the project draws to a close, the integration of Microsoft Enterprise ID (Entra) marks a significant milestone in enhancing the security and accessibility of the Azure SQL production database. The configuration process involved enabling Microsoft Entra ID authentication for the SQL Server hosting the database, thereby establishing Entra credentials as a trusted identity provider. This step seamlessly integrates Entra credentials, enabling users to authenticate using their Microsoft Enterprise credentials. Moreover, the creation of both admin and reader accounts within Microsoft Entra ID allowed for precise control over user management and access control within the database environment. The admin account, endowed with privileged permissions, assumes authority over user management, while the reader account, assigned the db_datareader role, is granted read-only privileges. This meticulous role definition ensures that users have access tailored to their respective responsibilities, maintaining the integrity and security of the production database. The successful completion of Milestone 7 not only signifies the culmination of the project but also underscores the commitment to implementing robust security measures and enhancing user experience within the Azure database environment.
  
## Conclusion

  In conclusion, this project has been a challenging yet deeply fulfilling exercise that demanded unwavering determination and focus at every turn. Navigating through the complexities of architecting and implementing a cloud-based database system on Microsoft Azure presented numerous hurdles, each requiring careful analysis and strategic problem-solving. However, overcoming these challenges has been immensely rewarding, underscoring the resilience and adaptability essential in the realm of cloud engineering. As I reflect on this journey, I am filled with excitement for the opportunities ahead to grow and strengthen my skills, knowledge, and experience in this space. This project has ignited a passion for cloud database management, and I eagerly anticipate further exploration and innovation in this field. With a clear vision of a career dedicated to mastering cloud technologies and driving impactful solutions, I am motivated to pursue continued learning and development to realize my aspirations in the dynamic and ever-evolving landscape of cloud computing.

