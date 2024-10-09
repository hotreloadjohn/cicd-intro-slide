---
title: Introduction to GitHub Actions for Beginners
author: John Ng
date: "2024-05-01"
theme: seriph
---

# Continuous Integration and Continuous Delivery (CI/CD)

---

# Agenda

1. Introduction to CI/CD
2. Benefits of Implementing CI/CD
3. Key Concepts and Terminologies
4. Popular CI/CD Tools
5. Building a CI/CD Pipeline
6. Best Practices

---

# What is CI/CD?

### Continuous Integration (CI)

- Integrate code changes into a shared repository frequently.
- Each integration is verified by an automated build and tests.

<br>

### Continuous Delivery (CD)

- Extension of CI ensuring code can be released at any time.
- Automate delivery to selected environments.

<!--
This means that instead of waiting to combine all the changes at the end of a project or at the end of the day, developers integrate their code multiple times throughout the day.

After each code integration we need to ensures that the new code does not break the existing functionality and meets the required quality standards. not anyhow share your code that affects your team.

CD ensuring that the application is always in a deployable state.

Explain environments, dev, staging(test), production
-->

---

# Why CI/CD Matters

- **Accelerates Software Delivery**
- **Improves Code Quality**
- **Enhances Collaboration**
- **Reduces Risks**
- **Increases Customer Satisfaction**

<!--
- Accelerates Software Delivery
  - This means your users get new features and improvements more frequently, keeping your product competitive and responsive to user needs.

- Improves Code Quality
  - Catching bugs early prevents them from becoming bigger problems later. It ensures that the code is of high quality and reduces the chances of bugs making it to production.

- Enhances Collaboration
  - Frequent integration fosters better communication and teamwork. It ensures that everyone’s work is aligned and reduces the likelihood of integration issues.

- Reduces Risks
  - Smaller changes are easier to test and debug. This also minimizes the risk of introducing significant bugs and makes the development process more manageable.

- Increases Customer Satisfaction
  - Regular updates show customers that the product is actively maintained and improved. It ensures that their feedback is addressed quickly, leading to higher satisfaction and loyalty.
-->

---

# Key Concepts

- **Version Control Systems (VCS)**
    - <span style="color: red;">Git & GitHub</span>
- **Build Automation**
    - <span style="color: red;">GitHub Actions</span>
- **Automated Testing**
    - <span style="color: red;">Playwright</span>
- **Pipeline**
    - Automated processes delivering software from dev to production using GitHub

---

# Continuous Integration (CI)

**Main Practices:**

- **Frequent Commits**

  - Integrate code into shared repository multiple times a day.

- **Automated Builds**

  - Commit may be triggered by an automated build. (if any)

- **Automated Testing**

  - Run unit, integration, and other tests automatically. 

**Goals:**

- Detect integration errors early.
- Reduce time spent debugging.

---

# Continuous Delivery (CD)

**Extension of CI**

- Keep code in a deployable state at all times.

**Automated Deployments**

- Deploy to staging environments automatically.

**Testing in Production-like Environments**

- Validate software in real-like conditions.

**Manual Release Approval**

- Business decision to deploy to production.

**Goals:**

- Minimize deployment risks.
- Deliver features quickly and reliably.

---

# Other Popular CI/CD Tools

- **Jenkins**

  - Open-source automation server.

- **GitLab CI/CD**

  - Integrated with GitLab repositories.

- **CircleCI**

  - Cloud-based CI/CD platform.

- **Travis CI**

  - Hosted continuous integration service.

- **Azure DevOps**

  - Microsoft's integrated DevOps services.

- **AWS CodePipeline**

  - Continuous delivery service on AWS.

---

# Anatomy of a CI/CD Pipeline

1. **Source Code Management**

   - Code is committed to the repository.

2. **Build**

   - Compile code and resolve dependencies.

3. **Test**

   - Execute automated tests.

4. **Deploy**

   - Deploy to staging/production environments.

5. **Monitor**

   - Monitor performance, collect logs and metrics.

---

# Building a CI/CD Pipeline

1. **Set Up Version Control**

   - Use Git or another VCS.

2. **Choose CI/CD Tool**

   - Select per project needs.

3. **Write Build Scripts**

   - Automate build processes.

4. **Create Automated Tests**

   - Develop comprehensive test suites.

5. **Configure Pipeline**

   - Define stages, triggers, workflows.

6. **Set Up Environments**

   - Prepare staging, testing, production environments.

7. **Implement Deployment Automation**

   - Use Docker, Kubernetes, or cloud services.

---

# Best Practices for CI/CD

- **Commit Code Frequently**

  - Small changes are easier to integrate.

- **Maintain a Single Source Repository**

  - Promotes collaboration and transparency.

- **Automate Everything**

  - From builds to deployments.

- **Keep Builds Fast**

  - Provide quick feedback.

---

# Best Practices for CI/CD (2)

- **Fail Fast and Fix Fast**

  - Quickly detect and address issues.

- **Use Production-like Environments**

  - Reduce surprises upon deployment.

- **Monitor and Alert**

  - Implement robust monitoring and alerting.

- **Security Integration**

  - Incorporate security into the pipeline (DevSecOps).

---
layout: cover
class: text-center
---
# Thank You!

---
