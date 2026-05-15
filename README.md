## 📬 Contact Form Automation — n8n Workflow

An end-to-end automation built with **n8n** that handles contact form submissions — captures data into a Google Sheet and instantly sends a confirmation email to the submitter.

---

## 🚀 What It Does

When a user fills out the contact form popup:

1. **Form Popup** triggers on submission
2. **Google Sheets** — contact details (name, email, message) are saved automatically
3. **Email Notification** — a confirmation/notification email is sent to the provided email address instantly

No manual follow-up needed. Zero code required to run.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| [n8n](https://n8n.io) | Workflow automation engine |
| Google Sheets | Store contact form submissions |
| SMTP / Email Node | Send automated emails |
| Webhook / Form Trigger | Capture form submissions |

---

## ⚙️ How to Import & Run

### Prerequisites
- n8n installed locally or on a cloud instance ([n8n install guide](https://docs.n8n.io/getting-started/installation/))
- A Google account (for Sheets access)
- SMTP credentials (Gmail, SendGrid, etc.)

### Steps

1. **Clone this repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/n8n-contact-form-automation.git
   ```

2. **Open n8n** and go to **Workflows → Import from File**

3. **Select `workflow.json`** from this repo

4. **Set up credentials** in n8n:
   - Google Sheets OAuth2 — connect your Google account
   - SMTP / Email — add your email credentials

5. **Activate the workflow** and test by submitting the form

---

## 📊 Output Example

After a form submission:

- ✅ A new row appears in Google Sheets with name, email, message, and timestamp
- ✅ An email is delivered to the submitted address within seconds

---

## 💡 Use Cases

- Portfolio contact pages
- Event registration forms
- Lead capture forms for small businesses
- Customer support intake

---

## 🔧 Customization Ideas

- Add a **Slack notification** when a new submission arrives
- Connect to **Notion** or **Airtable** instead of Google Sheets
- Add **spam filtering** logic before saving
- Trigger a **CRM entry** (HubSpot, Pipedrive) on submission

---

## 👤 Author

**Nikhil Jankar**  

---

## 📄 License

This project is open source 
