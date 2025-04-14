# 🗂️ Automated Document Approval Workflow using Power Automate & SharePoint

## 💡 Project Overview
This project automates the document approval process using **Microsoft Power Automate**, integrated with **SharePoint Online** and **Microsoft Teams**.

Whenever a document is uploaded to a SharePoint document library, an approval request is automatically sent to the team. Upon approval, the document is moved to a final folder, and a notification is sent via Teams — eliminating the need for manual follow-ups and ensuring efficient document management.

---

## ⚙️ How the Flow Works

1. **Trigger - File Upload**
   - When a file is uploaded to a designated **SharePoint Document Library**, the flow is automatically triggered.

2. **Approval Request**
   - An approval card is sent to the team via **Microsoft Teams**.
   - Team members can approve or reject the document directly from the Teams interface.

3. ✅ **If Approved**
   - The document is automatically moved from the `Pending Approval` folder to the `Final Approved` folder in SharePoint.
   - A notification is sent to the document owner (or you) on Microsoft Teams confirming the approval.

4. ❌ **If Rejected**
   - A rejection message is sent to the document uploader.
   - The document remains in the `Pending Approval` folder for further updates or revisions.

---

## 🧰 Tech Stack

- 💼 Microsoft Power Automate  
- 🗃️ SharePoint Online  
- 💬 Microsoft Teams  
- 🌐 Office 365 Environment

---

## 💼 Use Case

- Simplified and reliable document approval process.
- Increased transparency and accountability in document handling.
- Automated notifications and document sorting.
- Reduced manual tracking efforts.

---

## 🚀 Outcome

This flow helped:
- Save valuable team time by automating document routing.
- Ensure all approvals are properly logged and communicated.
- Keep the SharePoint library organized and updated without manual intervention.
- Deliver instant updates to stakeholders via Teams.

---

## 🏷️ Tags

`Power Automate` `SharePoint` `Microsoft Teams` `Workflow Automation` `Document Management`

---

## 📣 About the Author

Designed and built by **Nandan Vallamdasu** — passionate about automating business processes and enhancing team collaboration using the Microsoft Power Platform.

---

