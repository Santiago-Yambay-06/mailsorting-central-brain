# H-FARM College Central Brain - 90/10 Automation Architecture

## 🎯 The Core Mission: 90% Workload Reduction

The system is calibrated around a **90/10 operating rule**:
1. **~90% of all incoming student emails** are answered **100% automatically** without human intervention because the required guidelines, FAQs, event information, deadlines, and policies already exist in the single unified database.
2. **The remaining ~10%** are forwarded to human advisors at the **Student Office / respective department** exclusively when the Central Brain has **zero prior knowledge** about the topic or when personal discretion is required.
3. **The Self-Learning Flywheel:** When an advisor answers a novel question in that 10% queue, that answer is saved back into the Central Brain with a single click. From that moment forward, any student who asks that question is automatically answered in the 90% stream!

---

## 🔄 The 90/10 Operational Pipeline

```
                       ┌───────────────────────────────┐
                       │  Student Sends Inbound Email  │
                       └───────────────┬───────────────┘
                                       │
                                       ▼
                       ┌───────────────────────────────┐
                       │     Central Brain Matcher     │
                       │  (Vector + Keyword Retrieval) │
                       └───────────────┬───────────────┘
                                       │
                ┌──────────────────────┴──────────────────────┐
                ▼                                             ▼
     [Knowledge Exists in DB]                       [Zero Knowledge Found]
     ⚡ 90% Autonomous Path                         👤 10% Human Review Path
                │                                             │
                ▼                                             ▼
 ┌─────────────────────────────┐               ┌─────────────────────────────┐
 │ Immediate Branded Auto-Reply│               │ Sent to Student Office      │
 │ Sent to Student (< 2 sec)   │               │ Staff Escalation Queue      │
 └─────────────────────────────┘               └──────────────┬──────────────┘
                                                              │
                                                              ▼
                                               ┌─────────────────────────────┐
                                               │ Staff answers email & clicks│
                                               │ "Save to Central Brain"     │
                                               └──────────────┬──────────────┘
                                                              │
                                                              ▼
                                               ┌─────────────────────────────┐
                                               │ Now in DB: Future emails on │
                                               │ this topic are 100% AUTO!   │
                                               └─────────────────────────────┘
```

---

## 🧪 How to Test this in the Demo

Open [`H_Farm_Central_Brain_Demo.html`](file:///c:/Users/santi/OneDrive/Documentos/H-Farm%20Documents/H_Farm_Central_Brain_Demo.html) in your browser:

1. **Test the 90% Auto Path:**
   - Click **`[90% Auto] Sam Altman Keynote`** or **`[90% Auto] Enrollment Certificate`**.
   - Notice the status: **"90% Autonomous Path (Knowledge Found)"** — the email is dispatched instantly without human intervention.
2. **Test the 10% Human Path (Zero Knowledge):**
   - Click **`[10% Human] Zero-Knowledge Question`** (*"Can I charge my electric scooter inside the campus library?"*).
   - Notice how the Central Brain immediately identifies that there is zero prior data in the database, sends a polite automated receipt to the student, and routes the ticket to the **10% Human Review Queue**.
3. **Test the Self-Learning Flywheel:**
   - Switch to the **10% Human Review Queue** tab.
   - Review the student's question and click **"Send Reply & Permanently Teach Bot"**.
   - Switch back to the simulator and run the exact same electric scooter question again — **it is now 100% automatically answered in the 90% bucket!**
