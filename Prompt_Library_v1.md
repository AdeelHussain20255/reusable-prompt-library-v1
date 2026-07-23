# 📦 Prompt Library v1

## 📐 Universal Template Blueprint

* **Role:** Senior Customer Care Specialist at `{{COMPANY_NAME}}`
* **Context:** `{{CUSTOMER_NAME}}` | `{{ISSUE_CATEGORY}}` | Policy: `{{POLICY_RULE}}`
* **Task:** Draft actionable support response
* **Format:** Subject + Salutation + Solution Paragraphs + Sign-off
* **Constraints:** Strict adherence to policy, tone=`{{TONE}}`, max 175 words

**Interactive Transcript:** [Claude Shared Thread](https://claude.ai/share/7896c36d-b2b9-4ad9-ab0d-ef50653bf2f7)

---

## 🧪 Test Prompts & Variable Configurations

### 📌 Prompt 1: Unexpected Billing Charge

**Variables:**
* **`{{COMPANY_NAME}}`:** CloudSync Pro
* **`{{CUSTOMER_NAME}}`:** Sarah
* **`{{ISSUE_CATEGORY}}`:** Double Charge Query
* **`{{CUSTOMER_MESSAGE}}`:** *"I was billed twice ($29.99) on my credit card this morning. Please fix this!"*
* **`{{POLICY_RULE}}`:** Duplicate charges are auto-refunded within 3-5 business days once verified.
* **`{{TONE}}`:** Empathetic and Reassuring

---

### 📌 Prompt 2: Feature Request Inquiry

**Variables:**
* **`{{COMPANY_NAME}}`:** DevFlow AI
* **`{{CUSTOMER_NAME}}`:** Marcus
* **`{{ISSUE_CATEGORY}}`:** Dark Mode Feature Request
* **`{{CUSTOMER_MESSAGE}}`:** *"Does your dashboard support dark mode? My eyes hurt working late."*
* **`{{POLICY_RULE}}`:** Dark mode is currently in beta releasing Q3; invite link can be provided upon request.
* **`{{TONE}}`:** Enthusiastic and Helpful

---

### 📌 Prompt 3: Account Lockout / Security Reset

**Variables:**
* **`{{COMPANY_NAME}}`:** SecureVault
* **`{{CUSTOMER_NAME}}`:** Alex
* **`{{ISSUE_CATEGORY}}`:** Password Reset Failure
* **`{{CUSTOMER_MESSAGE}}`:** *"I tried resetting my password three times and now my account is locked out!"*
* **`{{POLICY_RULE}}`:** Accounts auto-unlock after 30 minutes; support can issue a 1-time secure reset link manually.
* **`{{TONE}}`:** Urgent and Calm

---

### 📌 Prompt 4: Service Outage / Downtime Complaint

**Variables:**
* **`{{COMPANY_NAME}}`:** HostMatrix
* **`{{CUSTOMER_NAME}}`:** David
* **`{{ISSUE_CATEGORY}}`:** Server Disconnection
* **`{{CUSTOMER_MESSAGE}}`:** *"My website has been down for 20 minutes! I am losing customers."*
* **`{{POLICY_RULE}}`:** Region US-East-1 experienced a 15-minute outage, now fully resolved. Status page: status.hostmatrix.io.
* **`{{TONE}}`:** Apologetic and Direct

---

### 📌 Prompt 5: Subscription Cancellation & Refund Request

**Variables:**
* **`{{COMPANY_NAME}}`:** WriteFast
* **`{{CUSTOMER_NAME}}`:** Elena
* **`{{ISSUE_CATEGORY}}`:** Cancellation past 14-day limit
* **`{{CUSTOMER_MESSAGE}}`:** *"I forgot to cancel my trial and was charged for an annual plan yesterday. Can I get a full refund?"*
* **`{{POLICY_RULE}}`:** Full refunds allowed within 48 hours of trial conversion upon request.
* **`{{TONE}}`:** Understanding and Professional
