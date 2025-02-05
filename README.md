# 📌 Performance Testing Report - Contact List App
## 🔗 Links
- **App URL:** [Thinking Tester Contact List](https://thinking-tester-contact-list.herokuapp.com/)
- **API Documentation:** [Postman API Docs](https://documenter.getpostman.com/view/4012288/TzK2bEa8#abe537df-fccc-4ee6-90d2-7513e3024d6b)

## 📝 Documentation
[Performance Testing Report](https://drive.google.com/file/d/1CiZ8XpVBCVPT7vy0mhUgfD7akJluQj-B/view?usp=sharing)

## 📽️ Video 
[Video demo](https://youtu.be/k2uUKwCy1n4)


## 📖 Introduction
### 🎯 Purpose
This document contains the **Performance Testing Report** for the **Contact List App**. The purpose of this testing is to measure system performance under specific load conditions and ensure that the system can handle the specified number of users efficiently.

### 📌 Scope
| Feature               | Description                      |
|----------------------|--------------------------------|
| **Login User**      | Authenticate with API          |
| **Get Contact List** | Retrieve the contact list      |
| **Update Contact**   | Update contact information     |
| **Add Contact**      | Add a new contact              |
| **Get Contact**      | Get contact by ID              |
| **Delete Contact**   | Delete a contact               |
| **Add User**        | Register a new user            |

### 🔥 Types of Performance Testing
- **Load Testing**

## 🛠 Tools Used
- 🚀 **Apache JMeter** (v5.6.3)
- 📨 **Postman**


## 🎯 Scenario
### 🔍 Test Cases
| Test Case        | Method | Endpoint            | Description                       |
|-----------------|--------|--------------------|----------------------------------|
| **Login User**  | POST   | `/users/login`      | Authenticate with API           |
| **Get Contacts List** | GET | `/contacts/`      | Retrieve the contact list       |
| **Add Contact** | POST   | `/contacts`        | Add a new contact               |
| **Get Contact** | GET    | `/contacts/{id}`   | Get contact by ID               |
| **Update Contact** | PATCH | `/contacts/{id}` | Update contact information      |
| **Delete Contact** | DELETE | `/contacts/{id}` | Delete a contact               |

---

### 🚀 How to Run the Tests
#### Using JMeter
1. Open **Apache JMeter (5.6.3)**
2. Import the **JMX test script**
3. Configure the **Thread Group** (e.g., number of users, ramp-up time)
4. Run the test and analyze the results in the **View Results Tree**

#### Using Postman
1. Import the API collection using the provided **Postman API Documentation**
2. Run each request manually or use **Postman Runner**
3. Analyze response times and system behavior under load

---

### 📊 Results & Analysis
The results of the performance testing will be documented based on:
- **Response Time** 📉
- **Throughput** ⚡
- **Error Rate** ❌
- **System Stability** 🏗

Stay tuned for detailed **Performance Test Results**! 📊🚀
