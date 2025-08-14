# xyz

# Question 1: JIRA Automation Rule

## Objective
Create a **JIRA automation rule** that:
1. Uses a **Trigger** (e.g., Issue Created or Issue Transitioned).
2. Performs an **Action** to either:
   - Assign the ticket to the QA Lead, OR
   - Send an email notification to the QA Lead.

---

## 1. Tools Used
- **JIRA Cloud** (can also work with JIRA Server)
- **Web Browser**: Google Chrome / Mozilla Firefox
- **Screenshot Tool**: Snipping Tool / Lightshot / built-in OS tool
- **GitHub** for repository hosting

---

## 2. Steps to Create the Automation Rule

### Step 1 – Access Automation Settings
1. Open your JIRA project.
2. Click **Project Settings** in the left-hand menu.
3. Select **Automation**.
4. Click **Create Rule**.

---

### Step 2 – Add Trigger
- Select **Issue Created** as the trigger.
- Click **Save**.

*(Alternative)*  
If you want the rule to run on a workflow change:
- Select **Issue Transitioned** and choose the required transition (e.g., “To Ready for QA”).

---

### Step 3 – Add Action

#### Option A – Assign to QA Lead
1. Add an **Assign issue** action.
2. Set **Assignee** to the QA Lead (e.g., `qa.lead.username`).
3. Click **Save**.

#### Option B – Send Email to QA Lead
1. Add a **Send Email** action.
2. Set **Recipient** to QA Lead’s email address.
3. Subject example:
