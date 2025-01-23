# AWS Cloud Club - Mapúa University Manila Web Application Proposal 🚀

### 🌐 **Visit our sample Website**: [AWS Cloud Club Website](https://purple-mud-098a42e10.4.azurestaticapps.net/)

## 🚀 Project Overview

The **AWS Cloud Club** at Mapúa University Manila is a student organization focused on leveraging AWS services for educational purposes. This web application will serve as a centralized platform for the club's activities, events, member registration, and resources. By integrating various AWS technologies, the platform will offer a highly interactive and informative experience for students.

## 🌐 System Architecture

### **Components**

- 👥 **Users**: Students and club members who interact with the web application.
- 🖥️ **AWS Lambda**: Executes serverless code using Node.js to handle requests and process data.
- 📊 **DynamoDB**: A NoSQL database that stores event details, member information, and other club-related data.
- 🌐 **Amazon Route 53**: Provides DNS service for domain name resolution.
- 🚀 **Amazon CloudFront**: A Content Delivery Network (CDN) that caches content closer to the users to improve website performance.
- 🗂️ **Amazon S3**: Stores static assets such as images, videos, and documents.

### **AWS Architecture Diagram**

![AWS Architecture](Untitled%20Diagram.drawio.png)

### **Interactions Flow**

1. **User Request**: A student accesses the web application via their browser.
2. **Route 53**: Resolves the domain name to the appropriate IP address.
3. **CloudFront**: Determines if the requested content is cached. If not, forwards the request to Lambda or the origin server.
4. **AWS Lambda (Node.js)**: Handles requests such as retrieving data from DynamoDB or generating dynamic content.
5. **Response**: CloudFront returns the response to the user's browser, caching it for future requests.

## 🛠️ System Requirements

### **Frontend**

- **Languages**: HTML, CSS, JavaScript (React.js)
- **Responsive Design**: Tailwind CSS or Bootstrap
- **Features**:
  - 🎉 Hero Section with Event Countdown and Key Information

### **Backend**

- **AWS Lambda**: Node.js for serverless processing
- **DynamoDB**: For storing event data, user registrations, etc.
- **AWS S3**: For static content hosting
- **API Gateway**: For managing API requests and communication between the frontend and backend

### **Networking**

- **Amazon Route 53**: For domain management and DNS services
- **Amazon CloudFront**: For caching and content delivery

## 📋 Project Specifications

### **User Management**

- 📝 Member Registration and Login (via AWS Cognito)
- 🎟️ Event Registration and Ticketing

### **Event Management**

- 📅 Dynamic Event Schedule
- 🎤 Workshop and Speaker Information
- ⏳ Event Countdown Timer

### **User Interaction**

- 📧 Contact Form with direct communication to club organizers
- ❓ FAQs Section

### **Design**

- 🎨 Modern design with AWS branding
- 📱 Mobile-friendly and accessible

## 💻 Technologies Used

### **Frontend**

- ⚛️ React.js
- 🎨 Tailwind CSS

### **Backend**

- 🖥️ AWS Lambda (Node.js)
- 📊 DynamoDB
- 🌐 API Gateway

### **Hosting and Storage**

- 🗂️ AWS S3
- 🚀 CloudFront

### **Networking**

- 🌐 Route 53

## 🗓️ Sprint 1 Tasks

### **Sprint Duration**: 2 Weeks

#### Week 1

- 📝 **Create User Stories** for member registration, event details, and interactions.
- 🖥️ **Frontend Design**: Design wireframes and UI components for the homepage, registration page, and event schedule.
- 🌐 **Set up AWS Infrastructure**:
  - Configure Route 53 and CloudFront.
  - Set up Lambda functions for basic request handling.
  - Set up DynamoDB tables for event data storage.

#### Week 2

- 📱 **Frontend Development**:
  - Implement homepage and event countdown section.
  - Develop responsive layouts using Tailwind CSS.
- 🔧 **Backend Setup**:
  - Implement Lambda functions for event registration and user management.
  - Configure API Gateway for backend communication.
- 📦 **Static Assets**:
  - Upload static assets to AWS S3 and integrate with CloudFront for caching.

### **Sprint 1 Deliverables**

- 🏠 Homepage layout completed.
- 🛠️ AWS services (Lambda, API Gateway, DynamoDB, S3) set up and configured.
- ⏳ Event registration and countdown functionality implemented.

## 💰 Estimated Yearly Cost

| **Service**       | **Estimated Cost** |
| ----------------- | ------------------ |
| 🖥️ **AWS Lambda** | $100               |
| 📊 **DynamoDB**   | $50                |
| 🚀 **CloudFront** | $60                |
| 🗂️ **S3 Storage** | $30                |
| 🌐 **Route 53**   | $10                |
| **Total**         | **$250/year**      |

_Note: These costs are estimates and may vary depending on usage and scale._

## 📌 Features of the AWS Cloud Club Website

- 🗓️ **Event Management**: Display event schedules, workshops, and speaker profiles.
- 💬 **Interactive FAQs**: Help students with event-related queries.
- 🔗 **Peer-to-Peer Networking**: Provide contact options for members to connect with event organizers and peers.
- 💼 **Sponsor and Partnership Pages**: Showcase event sponsors and partners with logos and links.
- 🎟️ **Event Registration**: Allow students to register for events and workshops online.
- 📝 **Blog**: A blog section where members can post articles related to AWS technologies, events, and educational resources.
- 📱 **Mobile Responsive Design**: Ensure the website is accessible and functional across all devices.

## 🤖 Future Enhancements

- 🏷️ **Member Dashboard**: Provide personalized event recommendations and notifications.
- 🔒 **Secure Member Authentication**: Implement AWS Cognito for login and user authentication.
- 📊 **Analytics Integration**: Track user interactions and event attendance.
- 🧑‍🏫 **Educational Resources**: Include AWS training materials and links to relevant courses.

## 📣 Conclusion

The **AWS Cloud Club - Mapúa University Manila** web application will be the central hub for students interested in AWS technologies. By utilizing AWS services such as Lambda, DynamoDB, and CloudFront, we aim to deliver a fast, scalable, and reliable platform. This project will foster a community where students can learn, interact, and collaborate on AWS-based initiatives.

---

© 2024 AWS Cloud Club - Mapúa University Manila
