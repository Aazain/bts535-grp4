# Bike Shop Website

## 1. Introduction
This project aims to create a dynamic and user-friendly website for a bike shop. The website will allow customers to browse products by category, track orders, chat with customer support, and access cycling tips. It will also include a product review section for experienced cyclists and a bike finder tool for beginners.

_October 12th, 2024_

_Current Version: 1.0_

_Project Managers (and sponsor): Aazain Rafiq, Olivia Christy Kuitchoua Kewang, Renata Toleugazina, Saurab Kayaith_

## 2.Overview
The bike shop plans to enhance customer interaction by providing an online platform where users can easily navigate product categories, place orders, and get real-time support through a chat feature.

### 2.1 Objective
The primary objective is to have a fully functional website live by the end of the quarter, featuring real-time chat, order tracking, a cycling tips blog, and other tools to assist both beginner and experienced cyclists in their shopping experience.



## 3.Milestones
1. Finalize list of technologies required in the front-end, back-end, database, and hosting technologies for deployment.
2. Establish a website front-end and back-end
3. Design and develop a bike finder tool for users to streamline shopping experience
4. Implement categories for bike offerings
5. Design and develop a customer reviews and ratings feature for product feedback

### 3.1 Work Breakdown Structure
| ID  | Task                     | Sub Task                                     | Owner                           |
|-----|--------------------------|--------------------------------------------- |---------------------------------|
| 1   | Planning                 | Finalize technologies required               | Project Manager                 |
| 2   | Front-End Development    | Design layout and implement design           | Front-End Developer             |
| 3   | Back-End Development     | Set up database and server                   | Back-End Developer              |
| 4   | Bike Finder Development  | Design and develop bike finder tool          | Development Team                |
| 4   | Category Development     | Design and develop categories for bikes      | Development Team                |
| 5   | Customer Review Feature  | Develop rating and review submission feature | Development Team                |
| 6   | Testing                  | Conduct testing                              | QA Team                         |
| 7   | Launch                   | Finalize details and marketing               | Project Manager, Marketing Team |


![work breakdown structure](https://github.com/user-attachments/assets/92b7fea7-6c19-4dec-93c6-fc31af40ed90)



### 3.2 Requirements Traceability Matrix
| Req ID | Requirement                                     | Del ID | Deliverable                                        | Owner                | Status   |
|--------|-------------------------------------------------|--------|----------------------------------------------------|----------------------|----------|
| REQ01  | Hosting defined and set up                      | DEL01  | Website up and running from the server             | Project Manager      | done     |
| REQ02  | Server up and running                           | DEL01  | Website operational with static pages              | Developer Team       | testing  |
| REQ03  | Front-end design completed                      | DEL02  | Interactive bike finder tool available             | Front-End Developer  | pending  |
| REQ04  | Category development completed                  | DEL03  | Categories for bike offerings available            | Front-End Developer  | pending  |
| REQ05  | Customer reviews feature developed              | DEL04  | Reviews and ratings section operational            | Developer Team       | pending  |


## 4.Deliverables
1. Website up and running from the server 
2. Website operational with static pages  
3. Interactive bike finder tool available 
4. Categories for bike offerings available 
5. Reviews and ratings section operational

### 4.1 Gantt Chart

### Gantt Chart

| Task                     | Oct | Nov | Dec | Jan | Feb |
|--------------------------|-----|-----|-----|-----|-----|
| Planning                 | ####|     |     |     |     |
| Front-End Development    |     | ####| ####|     |     |
| Back-End Development     |     |     | ####|     |     |
| Bike Finder Development  |     |     |     | ####|     |
| Category Development     |     |     |     | ####|     |
| Customer Review Feature  |     |     |     |     | ####|
| Testing                  |     |     |     |     | ####|
| Launch                   |     |     |     |     | ####|



=======
### 6. Organization/Stakeholders

| **Project Role**   | **Responsibilities**                          | **Assigned to**                        |
|--------------------|------------------------------------------------|----------------------------------------|
| Project Manager    | Oversee the design, development, and launch of the website | Aazain Rafiq|
| Project Sponsor    | Provide financial resources and strategic guidance | Olivia Christy Kuitchoua Kewang |
| Developers         | Build and maintain the website, ensuring functionality and responsiveness | Saurab Kayaith |
| Marketing Team     | Promote the website and drive customer engagement | Renata Toleugazina |
| Customers (Users)  | Access the website, browse products, track orders, and use the bike finder tool | Bike Shop Customers                    |


### 7. Risks, Assumptions, and Constraints

#### 7.1 Risks
1. **Hosting and Domain Issues**: Problems with website hosting or domain registration could affect the availability of the website, making it inaccessible to customers if the hosting provider experiences downtime.
2. **Service Provider Price Hikes**: Unexpected price increases in contracted services such as hosting, domain registration, or payment gateways (e.g., Square) could negatively impact the project’s budget and timeline.
3. **Unintended Changes by Admin**: Administrators or other team members with access to the system could inadvertently make changes that cause the website to malfunction or become inaccessible.
4. **Usability Issues for Customers**: Some customers, particularly those unfamiliar with online shopping, may find it difficult to navigate the new system, leading to potential frustration and loss of sales.

#### 7.2 Risk Evaluation Chart

| **Risk**                               | **Likelihood** | **Impact**  | **Mitigation Plan**                                             |
|----------------------------------------|----------------|-------------|------------------------------------------------------------------|
| Hosting and Domain Issues              | Medium         | High        | Use a reliable hosting service with regular backups in place.    |
| Service Provider Price Hikes           | Low            | Medium      | Keep contingency funds available in the budget for adjustments.  |
| Unintended Changes by Admin            | Low            | High        | Restrict administrative privileges and create clear guidelines.  |
| Usability Issues for Customers         | Medium         | Medium      | Provide user-friendly design, guides, and a live chat feature.   |

#### 7.3 Assumptions
1. The project team will be proficient in all the technologies required to create and maintain the website, including HTML, CSS, JavaScript, React, Node.js, MySQL, and server management.
2. The contracted services for hosting and domain registration will be extremely reliable, with a service uptime of more than 99.9%, ensuring the website remains accessible.
3. Customers will find value in the features offered, such as the bike finder tool, product reviews, and live chat support, encouraging regular use of the platform.

#### 7.4 Constraints
1. **Data Privacy**: The website will not store or display any sensitive personal information beyond customer names and emails, adhering to privacy and security regulations.
2. **Budget Limitations**: The project must operate within a fixed budget, meaning the team will need to carefully prioritize features and services that offer the most value for the website.
3. **Technology Stack**: The project will use a fixed technology stack (HTML, CSS, JavaScript, React, Node.js, MySQL, Square for payment processing) and cannot deviate from these core technologies.

#### 7.5 Quality Assurance
1. **Testing**: The website will undergo multiple types of testing to ensure functionality, security, and performance:
   - **Unit Testing**: Individual components of the website will be tested to ensure they work as expected.
   - **Integration Testing**: Different parts of the website will be tested together to ensure that they work harmoniously.
   - **User Acceptance Testing (UAT)**: End users (customers) will test the website to ensure that it meets their needs and is easy to navigate.
2. **Security Testing**: The website will undergo regular security checks, particularly for sensitive transactions such as those handled by the Square payment gateway.
3. **Cross-Browser Compatibility**: The website will be tested across multiple browsers (e.g., Chrome, Firefox, Safari, Edge) to ensure consistent behavior and performance on different platforms.
4. **Performance Testing**: The website will be optimized for fast load times and responsiveness on both desktop and mobile devices, ensuring a smooth customer experience.
