# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system **osTicket**.

---

## **Video Demonstration**

- ### [YouTube: How to Create, Work, and Resolve Tickets Within osTicket](https://www.youtube.com/results?search_query=osticket+ticket+life+cycle)

---

## **Environments and Technologies Used**

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

---

## **Operating Systems Used**

- Windows 10 (21H2)

---

## **Ticket Lifecycle Stages**

1. **Intake**  
   The process of ticket creation and capturing the issue details.
2. **Assignment and Communication**  
   Assigning the ticket to the appropriate agent or department and maintaining communication with the end-user.
3. **Working the Issue**  
   Troubleshooting the issue and providing necessary updates within the system.
4. **Resolution**  
   Resolving the issue, closing the ticket, and sending resolution confirmation to the end-user.

---

## **Lifecycle Stages: Detailed Steps**

### **Step 1: Intake**

1. A user submits a new support request via:
   - The **client portal** (`http://localhost/osticket`).
   - **Email** (if configured).
2. The system assigns a unique **ticket number** to the request.
3. The user receives an automatic confirmation email (if auto-response is enabled).
4. The ticket appears in the **Open Tickets** queue for agents to review.

---

### **Step 2: Assignment and Communication**

1. Log in to the **Admin Panel** (`http://localhost/scp`) as an agent.
2. Review the **Open Tickets** queue and assign the ticket to the appropriate department or agent.
3. Leave internal notes for other team members, if needed.
4. Use the **Post Reply** option to communicate directly with the user and provide updates.
   - The user will receive an email notification of the update.
5. Change the ticket’s **status** as necessary (e.g., from "Open" to "In Progress").

---

### **Step 3: Working the Issue**

1. Review the ticket details and gather information related to the issue.
2. Perform necessary troubleshooting steps:
   - Remote into the user’s machine (if applicable).
   - Collaborate with other teams if the issue requires escalation.
3. Provide step-by-step updates in the **Ticket Thread** to keep the user informed.
4. If additional information is needed from the user, update the status to **Awaiting Response**.

---

### **Step 4: Resolution**

1. Once the issue is resolved:
   - Add a detailed **resolution note** in the **Internal Notes** section.
   - Inform the user via a final **Post Reply**.
2. Change the ticket status to **Resolved**.
3. If the user confirms the issue is resolved, the ticket can be closed.
4. If the user reopens the ticket or submits new details, review and address any follow-up concerns.

---

## **Final Notes and Best Practices**

- Set up **SLA (Service Level Agreement)** reminders to avoid overdue tickets.
- Use **canned responses** for common issues to improve response time.
- Regularly review the **Closed Tickets** queue to ensure resolution quality and collect feedback.
- If using email-based ticketing, check your **email logs** in case of failed delivery notifications.

---

## **Additional Resources**

- [osTicket Official Documentation](https://docs.osticket.com/)
- [osTicket Community Forums](https://forum.osticket.com/)
