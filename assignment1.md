# Homework 1
## Task 1
### Organization
Real estate company

### **Business challenges**
* CRM part
    * Manage customer relations efficiently, improve the performance of advertisement calls
    * Keep track of the sales process
    * Be able to assess the efficiency of sales and reasons for failures
    * Manage relations with real estate developers to acquire better properties to offer
* Monitor the current state of real estate listings to avoid providing customers with stale data
* Monitor the current real estate market to adjust prices to be relevant to customer expectations

### Should we invest in this system?

#### **Pros:**
* **Standardizes** the sales process to apply best practices to each stage for each sales manager
* Makes customer service more **transparent to management** to analyze the sales process
* Provides the ability to set **market-relevant** prices and potentially increase sales
* Provides an opportunity to observe relevant prices (for intermediaries) and real estate building statuses to provide more information to a customer to make a decision and potentially reveals new niches or marketing strategies
* Ability to **integrate** with some ready SaaS solutions (Salesforce, SAP) to reduce development costs

#### **Cons:**
* Requires **effort to maintain** the system, especially if it is technologically complex
* If it would be built from scratch and without external services integration, it **raises expenses** significantly
* The necessity to **revise current sales process**, depending on the rigidity of sales managers, may be painful for them

### Management, organization, technological efforts to implement IS

#### **Management**
* Communicate with ready solutions distributors and evaluate their relevance to decide which parts are reasonable to outsource, which to build based on SaaS solutions, which to build from scratch
* Evaluate **expenses**, time costs that are reasonable to spend to build IS
* Identify **potential risks** and create a risk mitigation plan
* Define **key performance indicators** (KPIs) that will be used to measure the success of the IS implementation
* Monitor the **project budget** closely and track all expenses related to the IS implementation

#### **Organization**
* Create or choose development, operations, or DevOps **teams** for implementing the system
* Create **cross-functional teams** with members from various departments (sales, marketing, IT, customer service, etc.) to ensure that the IS is designed to meet the needs of the entire organization.
* Build an IS **integration framework** for different departments
* Establish **data governance policies** and practices to ensure data quality, security, and compliance with relevant regulations
* Assess the **current IT infrastructure** and determine if any upgrades or changes are needed to support the IS
* Document **existing business processes** and workflows. Identify areas where the IS can streamline and improve these processes.
* Develop a clear **communication plan** to keep all stakeholders informed about the IS implementation progress
* Develop a **data migration strategy** if there is any legacy IS
* Implement a robust **testing and quality assurance** process

#### **Technology**
* Evaluate **current** technology **stack**, infrastructure, and software systems
* Decide on the **technology platform** or framework that will be used to develop the IS. Consider factors such as scalability, compatibility with existing systems, and ease of maintenance, local market technology spread
* Plan and design the **database structure** that will store all relevant data for the IS
* Depending on your decisions regarding building from scratch or integrating with external services, initiate the **software development process**. This includes coding, testing, and iterative development to ensure that the IS meets the defined requirements
* If the IS is integrating with external services or third-party applications (e.g., Salesforce, SAP), work on the **integration mechanisms**
* Implement robust **security** measures to protect sensitive data
* Create a user-friendly and intuitive **interface** for the IS
* Consider whether the IS should have a **mobile application** or be accessible on mobile devices
* Create comprehensive **documentation** for the IS, including user guides, technical documentation, and troubleshooting guides
* **Deploy** the IS in a controlled environment, such as a staging or testing environment, before rolling it out to the entire organization
* Implement **monitoring** tools and processes to continuously monitor the performance and health of the IS
* Set up a system for providing **user support** and troubleshooting
* Develop a robust backup and disaster **recovery plan** to ensure that data can be recovered in case of unforeseen events or system failures
* Ensure that the IS complies with all relevant data protection and privacy **regulations**, depending on your geographic location and industry.

#### **Potential business problems**
* Some implementation challenges, because implementation process may be complex and time-consuming
* Software bugs, crashes, or compatibility problems can lead to downtime
* Storing sensitive data may expose the company to breaches or privacy issues
* Employees, particularly sales managers, may resist changes to their established processes
* Keeping the IS up-to-date and maintaining its functionality can be resource-intensive and may require ongoing technical support, leading to increased operational costs
* The expenses associated with developing, integrating, and maintaining the IS may exceed the initial budget
* If the IS heavily relies on external services or third-party integrations, disruptions or changes in those services could negatively impact the company's operations
* Ensuring that all employees effectively use the IS may require extensive training efforts
* Increasing complexity of business-processes while IS improperly implemented will cause company to make great efforts to just keep status-quo and prevent from introducing disrupting innovations

## Task 2
### Functional and non-functional requirements for *Personal Finance Management (PFM)* feature
#### **Functional requirements:**
* User should be able view their expenses via **different** accounts / deposits / credit cards for each account / deposit / credit card individually
* Each transaction processed by bank should be **categorized** by it's purpose (entertainment, groceries, taxi, resonants, etc)
* User should be able to set some **limit** to some transaction categories and it would be notification raised once limit exceed
* User should be able to set up their **budgeting goals** for some period of time
* There would be some **higher level categories** present, such as transportation (public transportation + taxi + airplanes + ...)
* System should **forecast cash flow** for any amount of subsequent months
* User should receive some personal finance **insights**

#### **Non-functional requirements**
* Employ robust security measures to protect sensitive financial data
* Feature should be performant to provide quick access to user financial data
* Feature should be unavailable for 10 minutes a mount maximum
* Feature should be scalable enough to implement additional functional and integrate with other application systems
* Interface should be user friendly, intuitive and compliant with current usability standards and provide intuitive data visualization
* Feature should be accessible to users with some disables and to be compatible with all contemporary devices and operating systems
* Feature should comply with bank and financial regulations, unavailable under unauthorized access and protected from the most well-known security vulnerabilities, there should be no vulnerable dependencies used for development