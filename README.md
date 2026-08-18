Here is a clean, structured **README.md** tailored for the RocaRev landing page repository:

---

# RocaRev — Landing Page

A high-converting, single-page website for **RocaRev**. RocaRev offers custom, high-speed business websites for **$0 upfront** and monetizes by implementing an integrated revenue engine (missed-call text-back, AI chatbot, and automated review management).

---

## **Overview**

* **Brand**: RocaRev


* **Target Audience**: Service-based businesses losing revenue due to unhandled calls and slow follow-ups.


* **Core Value Proposition**: Custom website built free in 7 days to establish presence, followed by a 4-pillar system to capture, nurture, and automate client reviews.


* **Tech Stack**: Pure HTML5, CSS3, and modern Vanilla JavaScript (no external frameworks or dependencies).



---

## **Features & Architecture**

### **1. Core Page Sections**

* **Hero Section**: Value proposition headline, active offer banner ("4 slots left"), and CTA buttons.


* **Interactive Live Feed Stage**: Visual showcase demonstrating automated missed-call detection, text response, appointment booking, and Google Review requests in real time.


* **Proof Strip**: Key metrics (0 upfront, 7-day turnaround, <60s reply time, 24/7 coverage).


* **The Hard Truth**: Problem breakdown highlighting revenue leakage from missed calls and unhandled web traffic.


* **4-Pillar Revenue Architecture**:
1. **Presence**: Free custom conversion-focused website.


2. **Capture**: Automatic SMS reply within 60 seconds of a missed call.


3. **Nurture**: AI chatbot trained on business pricing and booking.


4. **Trust**: Automated post-job Google Review requests.




* **Partnership Model**: Explanation of how the free build and monthly revenue engine arrangement works.


* **Interactive Leak Calculator**: Dynamic client-side widget allowing business owners to project lost monthly/yearly revenue based on missed call volume, average ticket size, and closing rates.


* **Application Form**: Simple lead capture form for booking a build slot.



---

## **Design & Styling System**

The stylesheet uses a dark-themed CSS Custom Properties (Tokens) setup:

| Token | Hex Value / Usage | Description |
| --- | --- | --- |
| `--void` | `#0D0F12`<br> | Base background color

 |
| `--deck` | `#14181D`<br> | Container/Panel background

 |
| `--hv` | `#FFC233`<br> | High-vis amber for actions, recovered revenue, and highlights

 |
| `--leak` | `#FF4D4D`<br> | Accent red for lost revenue, missed calls, and warning states

 |
| `--chalk` | `#F0F3F6`<br> | Primary text color

 |
| `--silver` | `#8D97A3`<br> | Secondary/Body text color

 |

**Typography**:

* **Display Header**: `Anton`

* **Body Font**: `Inter`

* **Monospace Accent**: `Space Mono`


---

## **File Structure**

```text
.
├── index.html        # Single-file implementation containing HTML, inline CSS, and JS
└── README.md         # Documentation

```

---

## **Getting Started**

### **Local Development**

1. Clone or download the repository.
2. Open `index.html` directly in any web browser, or serve it using a lightweight local web server (e.g., Live Server in VS Code or Python's HTTP server):

```bash
# Python 3 local server
python3 -m http.server 8000

```

3. Visit `http://localhost:8000` in your browser.

---

## **Customization & Configuration**

* **Form Submission**: The application form (`#claimForm`) currently handles client-side validation and toggles a success state. Connect the `submit` listener in the `<script>` section to an API endpoint (e.g., GoHighLevel Webhook, Make.com, or Zapier) to process incoming leads.


* **Calculator Parameters**: The recovery rate default is set to `0.66` (66%) in the JS script. You can adjust this variable inside the script block to alter revenue projections.
