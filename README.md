# 🚀 Assignee — College Assignment & PPT Digital Studio

Assignee is a 100% independent academic assistance & presentation design platform for college students.

* **Founder & Admin:** **Dushyant Yadav**
* **Admin WhatsApp / Phone:** **+91 9772223152**
* **UPI ID:** **9772223152@paytm**

---

## 💰 Official Pricing & Operating Rules

* **Text Assignments:** **₹120 / page** (180–200 words, single-spaced, 12pt font). **Minimum: 2 pages.**
* **PowerPoint Presentations (PPT):** **₹80 / slide** (custom visual design, charts, speaker notes). **Minimum: 3 slides.**
* **Revisions:** Flat **₹60 every time** a post-delivery revision is requested.
* **Strict Lead-Time & Page Turnaround Caps:**
  - **Minimum Notice:** All orders must be placed at least **2 days (48 hours)** before the deadline.
  - **2-Day Turnaround:** Maximum **5 pages** accepted.
  - **3-Day Turnaround:** Maximum **3 pages** accepted as text.

---

## 🔔 Live On-Site Admin Notification & Acceptance Workflow

1. **Client Submits Brief (Zero Upfront Payment):**
   - The client enters their Full Name, WhatsApp Number, College Delivery Email, Topic, and Rubric Guidelines.
   - No payment is made upfront.
2. **Instant In-Website Notification for Admin Dushyant Yadav:**
   - **Audio Chime:** Dual-tone synthesized chime alerts the admin immediately.
   - **Floating Alert Banner:** Slides down in the top-right corner with student name, service, and quote.
   - **Admin Bell Badge:** Displays the count of pending incoming orders in the header.
   - **Order Acceptance Queue:** Click **"Admin Desk"** in the top navbar to open the slide-out console.
3. **Acceptance Decision:**
   - Admin reviews the topic, rubric, and deadline.
   - Clicking **"Accept Order (Send UPI info)"** automatically marks the order accepted and opens WhatsApp to the student with pre-formatted UPI payment instructions for the 80% advance (`₹[Amount]` to `9772223152@paytm`).
   - If capacity is full, clicking **"Decline"** marks the order declined and offers a polite WhatsApp message.
4. **80% Advance Transfer:**
   - Student transfers the 80% advance via UPI to Dushyant Yadav and shares the receipt screenshot on WhatsApp.
   - Assigned specialist immediately begins drafting the work.
5. **Delivery & 20% Balance:**
   - Plagiarism-checked deliverables (.docx, .pdf, or .pptx) are emailed 1–2 hours before deadline.
   - Client verifies and settles the final 20% balance via UPI.

---

## 📂 Project Location & Files

```text
C:\assignee/
├── index.html       # Complete, standalone storefront, pricing calculator & Admin Desk
└── README.md        # Operations manual & configuration guide
```

---

## ⚡ Live Configuration (Ready Out of the Box)

In [`index.html`](file:///C:/assignee/index.html):

```javascript
const CONFIG = {
  ADMIN_NAME: "Dushyant Yadav",
  ADMIN_PHONE: "9772223152",
  PAGE_RATE: 120,          // ₹120 per page
  SLIDE_RATE: 80,          // ₹80 per slide
  REVISION_RATE: 60,       // ₹60 flat per revision
  RUSH_MULTIPLIER: 1.5,
  RUSH_THRESHOLD_HOURS: 20,
  MIN_NOTICE_HOURS: 4,
  ADVANCE_RATIO: 0.80,
  UPI_ID: "9772223152@paytm",
  WHATSAPP_NUMBER: "919772223152"
};
```

---

## 🌐 Deploy to GitHub Pages (Separate Repo)

1. Create a new GitHub repository named `assignee`.
2. Push the contents of `C:\assignee` to your new repository.
3. Turn on **GitHub Pages** under repository **Settings** > **Pages** (`main` branch, `/ root`).
4. Your site will be live at:
   ```text
   https://<your-username>.github.io/assignee/
   ```
