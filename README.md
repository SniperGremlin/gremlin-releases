# Gremlin — Installation Guide

---

## ⚠️ CRITICAL — How Gremlin knows when to write a letter

Gremlin only generates a GP letter if the treatment note contains the word **EPC** or **CDM**.

This is how Gremlin knows the appointment was an Enhanced Primary Care or Chronic Disease Management plan visit.

**You MUST include EPC or CDM somewhere in your treatment note — otherwise Gremlin will skip the patient and no letter will be created.**

Example — anywhere in your note will work:
> *"Patient presented for EPC review. Plantar fasciitis management..."*
> *"CDM plan visit — ongoing diabetic foot care..."*

If Gremlin skips a patient you expected a letter for, check that the note contains EPC or CDM.

---

## Before you start
- Windows 10 or 11 (64-bit)
- 8GB RAM minimum
- 10GB free disk space
- Stable internet connection (first install only — downloads ~4GB)

---

## Step 1 — Install the AI Engine

Download and run **[GremlinAISetup.exe](https://github.com/SniperGremlin/gremlin-releases/releases/download/v1.0/GremlinAISetup.exe)**.

> ⚠️ **Windows will show a security warning — this is normal.**
>
> When you see "Windows protected your PC":
> 1. Click **"More info"** (small text near the top)
> 2. A new button appears at the bottom — click **"Run anyway"**

The installer will:
- Download and install Ollama (the AI engine) — about 100MB
- Download the Mistral AI model — about 4GB
- This can take **10–30 minutes** depending on your internet speed
- A progress window will show you what's happening — just leave it open

✅ When it says **"All done!"** the AI engine is ready.

---

## Step 2 — Install Gremlin

Download **[Gremlin_Windows.zip](https://github.com/SniperGremlin/gremlin-releases/releases/download/v1.0/Gremlin_Windows.zip)** and extract it.

> **How to extract:**
> Right-click the zip file → **"Extract All"** → choose a location (Desktop is fine) → click **Extract**

Open the extracted folder and double-click **Gremlin.exe**.

> ⚠️ **Windows may show the same security warning again.**
> Same steps: click **"More info"** → **"Run anyway"**

---

## Step 3 — Enter your clinic details

On first launch, Gremlin will ask for:
- Your **Cliniko API key**
- Your **email address** and **app password**
- Your **clinic details** (name, phone, AHPRA number, etc.)

Once saved, Gremlin is ready to use.

> ### ⚠️ Gmail App Password — this is NOT your normal Gmail password
>
> An App Password is a special one-time code you generate from your Google account. Here's how:
>
> 1. Go to **myaccount.google.com**
> 2. Click **Security** on the left
> 3. Under "How you sign in to Google", click **2-Step Verification** (you must have this turned on)
> 4. Scroll to the bottom and click **App passwords**
> 5. Type a name (e.g. "Gremlin") and click **Create**
> 6. Google shows you a **16-character password** — copy this and paste it into Gremlin
>
> You only need to do this once.

---

## Every day after that

1. Open **Gremlin.exe**
2. Pick today's date
3. Click **Generate Letters**
4. Drafts appear in your email — ready to review and send

> ⚠️ **Reminder:** Gremlin only writes letters for patients whose treatment note contains **EPC** or **CDM**. If no letter is generated, check the note.

---

## Need help?

Contact your Gremlin administrator.
