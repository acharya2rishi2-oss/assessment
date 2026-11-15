# Primary Curriculum Learning Portal (Grades 1–5)

An interactive, responsive storybook-style educational web portal designed for primary students in Nepal (Grades 1 to 5). It features engaging math and local curriculum activities with Devanagari typography, Nepali audio speech readers, and teacher assessment rubrics.

## 📂 File Structure & Denotation Convention
Files follow the standard denotation format: **`[Grade][Subject Code]LA[Learning Achievement].html`**

* **Grades:** `1` to `5`
* **Subject Codes:** 
  * `M` = Mathematics (e.g., `1MLA1.html`, `1MLA2.html`)
  * `S` = Serophero (मेरो सेरोफेरो)
  * `E` = English
  * `N` = Nepali
  * `LC` = Local Curriculum
* **Theme & Learning Achievement:** Numbered `1` to `30`.

## 🚀 Included Activities
1. **`index.html`** — The Master Page with 4 interactive dropdowns (Grade, Subject, Theme, Learning Achievement) that dynamically routes users to the corresponding activity or displays a friendly *"Coming Soon"* prompt if the file hasn't been uploaded yet.
2. **`1MLA1.html`** — Grade 1 Mathematics, Learning Achievement 1: **Spatial Explorer (स्थानिक ज्ञान खेल)** (Inside/Outside, Above/Below, Front/Behind, Near/Far, Left/Middle/Right).
3. **`1MLA2.html`** — Grade 1 Mathematics, Learning Achievement 2: **Devanagari Number Explorer (देवनागरी अङ्क खेल १ देखि १० सम्म)** (Counting, Comparing, Reading, and Writing with Teacher Assessment Box).

## 🛠️ How to Run Locally
1. Download or clone this repository into a local folder.
2. Open **`index.html`** in any modern web browser.
3. Select your desired Grade, Subject, Theme, and Learning Achievement, then click **Next**.

## 🌐 Hosting on GitHub Pages
1. Go to your GitHub Repository **Settings**.
2. Navigate to the **Pages** section on the left sidebar.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` (or `master`) branch and root folder (`/ (root)`), then click **Save**. Your portal will be live online!