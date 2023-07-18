# ADFMiniProject2
Title: COVID-19 Data Ingestion from ECDC GitHub Repository to Azure Data Lake using Azure Data Factory

Description:
This GitHub repository presents an automated data integration solution that facilitates the seamless ingestion of COVID-19 data from the European Centre for Disease Prevention and Control (ECDC) GitHub repository into Azure Data Lake Gen2. Leveraging the capabilities of Azure Data Factory (ADF) pipelines, this project fetches and transfers data from the publicly available ECDC GitHub repository.

Key Features:
1. Data Source: The solution efficiently fetches COVID-19 data directly from the ECDC GitHub repository, where it is continually updated and maintained.

2. GitHub API Access: ADF leverages HTTP activities to interact with the GitHub API, enabling the retrieval of COVID-19 data files from the ECDC repository.

3. For Each Loop: A dynamic For Each loop processes each fetched data file, seamlessly executing data copy operations.

4. Data Copy: The project adeptly copies the relevant COVID-19 data from the ECDC GitHub repository and stores it within Azure Data Lake Gen2. Data Lake's hierarchical namespace ensures organized data storage.

5. Automation and Scheduling: ADF pipelines are thoughtfully scheduled to run at specific intervals, ensuring consistent updates of COVID-19 data in Azure Data Lake Gen2.

6. Monitoring and Logging: The project offers robust monitoring and logging capabilities, facilitating visibility into the data ingestion process and aiding in troubleshooting efforts.

By exploring this project, you will gain invaluable insights into crafting comprehensive data integration solutions using Azure Data Factory. The provided code, pipelines, and workflows serve as excellent references for automating data ingestion from GitHub repositories and securely storing it within Azure Data Lake Gen2.

We warmly welcome contributions and customizations to adapt this solution to specific needs or expand its capabilities to encompass additional data sources and destinations. Your feedback and suggestions will be highly appreciated as they play an instrumental role in enhancing the project and adapting it to various COVID-19 data integration scenarios.

Embark on this exciting journey with us, harnessing the potential of Azure Data Factory to achieve seamless COVID-19 data ingestion from the ECDC GitHub repository and drive impactful data-driven insights during these unprecedented times. Happy coding!
