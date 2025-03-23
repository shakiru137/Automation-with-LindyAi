# Automation-with-LindyAi

# 🤖 Building Agents with Lindy — Part One

## 🛠️ Tool Used: [Lindy.ai](https://lindy.ai)

**Lindy** is a no-code AI automation platform that enables users to build intelligent agents capable of handling repetitive and complex tasks across different industries.

---

## 🚀 Getting Started

### 1. Create a Lindy Account
- Visit [lindy.ai](https://lindy.ai)
- Click **“Sign up for free”**
- ⚠️ **Important:** If prompted for credit card details, **close the tab**, return to the [Lindy homepage](https://lindy.ai), and log in with your credentials.

Once logged in, you’ll be presented with the **workflow editor**, where you’ll begin building your AI agent.

---

## 📋 Prerequisite: Build a Job Board Google Form

Before creating your Lindy agent, you need a form and spreadsheet to capture job board entries.

### ➤ Step-by-step Guide:

1. Go to [Google Forms](https://forms.google.com)
2. Create a form with the following fields:
   - **Company Name** – Short Answer
   - **Position** – Short Answer
   - **Description** – Paragraph
   - **Requirements** – Paragraph

3. Click on **“Link to Sheets”**  
   Choose **“Create a new spreadsheet”**, name it something like `Job Board`, and click **Create**.

4. The spreadsheet will open automatically.  
   Click **Share** → **Copy Link** → Save it for later.

---

## 📄 Write Your CV in Google Docs

1. Visit [Google Docs](https://docs.google.com)
2. Create or paste your CV into a new document.  
   If your CV is in another format, import it or manually copy-paste the content.
3. **Save and copy the shareable link** to use later in the project.

📌 _Example CV: Emmanuel Ndayisaba (Rwanda)_

---

## ✅ What’s Next?

In the next part, we’ll dive into **building the Lindy AI agent** that can:
- Parse job form submissions
- Match candidate CVs
- And much more — all using a no-code workflow interface!

---

> 💡 _“Build smarter workflows, not harder. Let AI handle the routine.”_


# 🤖 Building Agents with Lindy — Part Two

> 💡 **Make sure you’ve completed [Part One](#) before starting this section!**  
> 💾 **Remember to save your work regularly to avoid losing progress.**

---

## 🧠 Objective

In this part, you'll build an intelligent automation agent using Lindy.ai that:
- Listens to new job entries from a Google Sheet.
- Uses your CV as context.
- Generates a personalized **Cover Letter** and **Custom CV** for each entry.

---

## ✅ Steps to Build Your Lindy Agent

### 1. Log in to [Lindy.ai](https://lindy.ai)
- Click **“Create New Lindy”**
- Then select **“Automation”**

---

### 2. Set the Trigger
Lindy will open a **Flow Editor**.

- Click **Select Trigger**
- Search for **Google Sheets**
- Choose **New Row Added**

This ensures the agent runs whenever a new job record is added to your linked Google Sheet.

#### 🔌 Connect Your Google Account
- When prompted, **connect your Google account** and grant permissions.

#### 🔗 Paste Your Google Sheet Link
- Use the **Spreadsheet URL or ID** you saved from Part One.

---

### 3. Upload Your CV as a Knowledge Base

- Click **“Search Knowledge Base”**
- Paste your **Google Docs CV link**

> 💡 _Alternatively, you can paste text manually by choosing “Text”._

- Click **“Add Google File”** and select your CV
- Click **Save** to close the window

---

### 4. Add Actions

Click the ➕ icon, then choose **Perform an Action** → **Google Docs** → **Create Document**

#### 📝 First Action: Create a Cover Letter

- **Folder:** Select a folder to save your documents
- **Prompt for Title:**


- **Prompt for Content:**


---

#### 📝 Second Action: Create a Custom CV

Add another action the same way:

- **Prompt for Title:**


- **Prompt for Content:**


> 🎯 Click on the **[row]** and **[results]** tokens and link them to your spreadsheet trigger and CV knowledge base from earlier.

---

## 🎉 That's It!

You’ve now built a Lindy agent that:
- Reads new job posts from Google Sheets
- References your CV
- Auto-generates a tailored Cover Letter and Custom CV!

---

## 🚀 What’s Next?
Explore more Lindy features like:
- Auto-emailing the documents
- Notifying you via Slack
- Connecting to job boards or CRMs

> 💬 _“Let your agent do the job-hunting while you focus on acing interviews!”_


# 🤖 Building Agents with Lindy — Part Three

> 💡 **Make sure you’ve completed [Part Two](#) before starting this section!**  
> 💾 **Don’t forget to save your work regularly to avoid losing progress.**

---

## 📬 Final Step: Email Yourself the Results

In this final step, you will configure your Lindy Agent to **send an email** containing links to the generated **Cover Letter** and **Custom CV** every time a new job entry is submitted.

---

### 1. Add the Email Action

- Click the ➕ icon on the last node in your Lindy workflow
- Choose **Perform an action**
- Select **Gmail** → **Send Email**

---

### 2. Set Up the Email Details

In the sidebar:

- Enter your email address as the recipient
- Provide a **prompt** for the body of the email, for example:




> 📌 While writing your prompt, Lindy will let you choose from previously generated documents (cover letter and CV) via a popup. Select them to correctly insert their links.

---

### 3. Save and Name Your Agent

- Click the top bar to **name your Agent** (e.g., “Job Auto-Apply Agent”)
- Hit **Save**

---

### 4. Test Your Automation 🎯

To test your agent:

1. Go to your **Google Form** and submit a job post.  
   Example:
   - Company: **TechNova**
   - Position: **Frontend Developer**
   - Description: “We are seeking…”
   - Requirements: “3+ years experience…”

2. After submitting, head back to **Lindy.ai** to see the triggered workflow.

3. Check your email inbox — you should receive a message with:
   - A personalized **Cover Letter**
   - A customized **CV**

---

### ✅ Output Example

Here’s what you should receive in your email:

- ✅ A professional email to the hiring manager
- ✅ Link to the generated Cover Letter (Google Docs)
- ✅ Link to the customized CV (Google Docs)

---

## 🎥 Video Tutorial (Optional)

_A full video walkthrough of this tutorial will be available here._  
_Link placeholder: [Watch the video](#)_

---

## 🚀 Want to Take This Further?

Building a career is no easy feat, but with **ALX** you can access all the tools and skills you need to get an edge.

### 🌟 Check out [AiCE](https://www.alxafrica.com/aice) — Your Career Accelerator

---

### 👏 Congratulations!

You’ve successfully built a **fully automated job application assistant** using **Lindy.ai**, **Google Forms**, **Google Sheets**, and **Gmail** — all without writing a single line of code!

Now you can:
- Submit job listings via a form
- Automatically generate tailored documents
- Email them instantly with zero manual effort

---


# 🤖 Building Agents with Lindy

This project demonstrates how to build an **AI-powered automation agent** using [Lindy](https://lindy.ai), a no-code automation platform that enables users to build intelligent workflows with ease.

---

## 🔧 Overview

In this 3-part project, we built a job application assistant that automates the following:

- Captures job announcements via a **Google Form**
- Writes a **customized cover letter**
- Rewrites your **CV** to match job requirements
- Drafts an **email to the hiring manager**
- Sends all documents and the email to your inbox

---

## ✅ Prerequisites

- A [Lindy](https://lindy.ai) account (Sign up for free)
- A Google account
- A CV saved as a Google Docs document
- A basic Google Form and Sheet setup

---

## 🧩 Part One: Setting Up the Environment

### 🔗 Tools Used:
- **Google Forms** – for job entries
- **Google Sheets** – to store form data
- **Google Docs** – for your CV
- **Lindy** – for AI automation

### 📝 Steps:
1. Create a Google Form with these fields:
   - Company Name (Short Answer)
   - Position (Short Answer)
   - Description (Paragraph)
   - Requirements (Paragraph)

2. Link the form to a new **Google Sheet**.

3. Write your CV in a **Google Doc** or copy/paste an existing one.

---

## ⚙️ Part Two: Building the Agent in Lindy

1. Go to [Lindy.ai](https://lindy.ai) → Click **"Create New Lindy"** → Select **Automation**.

2. **Set the Trigger**:  
   `Google Sheets → New Row Added`

3. **Search Knowledge Base**:  
   - Add your CV (Google Doc or paste text)

4. **Add Action**:  
   - `Google Docs → Create Document`  
     - **Title Prompt**:  
       `"Write a title in the format of 'Cover letter for < company name > : < position >'"`  
     - **Content Prompt**:  
       `"Write a customized cover letter based on the position, company, description, and requirements [row]"`

5. **Add Another Action**:  
   - `Google Docs → Create Document`  
     - **Title Prompt**:  
       `"CV for : < position >"`  
     - **Content Prompt**:  
       `"Update my CV from your knowledge base [results] based on the requirements in [row]"`

---

## 📧 Part Three: Email Notification

1. Click **"+" → Perform an Action → Gmail → Send Email**

2. **Set Email Prompt**:  
   `"Write a professional email to a hiring manager citing my qualifications and specify the following links cover letter link : [cover letter doc url], cv link: [cv doc url]"`

3. Save your work by naming your agent.

---

## 🚀 Test the Agent

- Fill out the Google Form with a job posting.
- Check Lindy or your email inbox to see the generated:
  - ✅ Cover Letter
  - ✅ Updated CV
  - ✅ Email draft to the hiring manager

---

## 🧠 Example Output

- [X Post 1](https://x.com/YusufShakiruOl2/status/1903178867491082684)
- [X Post 2](https://x.com/YusufShakiruOl2/status/1903178870158774732)
- [X Post 3](https://x.com/YusufShakiruOl2/status/1903178872801116453)

---

## 📽 Video Tutorial (Coming Soon)

---

## 🌟 Want to Learn More?

Check out **AiCE** – a program designed to help you build a career with cutting-edge AI skills.

---

## 📜 License

This project is for educational purposes as part of the **AI-Powered Automation Agents** challenge by ALX.

---

## 👤 Author

**Shakiru Oluwasegun Yusuf**  
[Twitter/X](https://x.com/YusufShakiruOl2)


