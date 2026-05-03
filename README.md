# Shooting-tracker
**App to help track range qualifications**

## Qualification Tracker V15

### ⚠️ Data & Privacy Notice
*   **Offline & Private:** This application does not sync to a cloud server. All data is stored locally in your device's browser `localStorage`. 
*   **Data Persistence:** V15 features improved persistence logic; however, clearing your browser cache may delete your data.
*   **Install as an App:** Open this page in your mobile browser, tap the **Share** icon (iOS) or **Menu** icon (Android), and select **"Add to Home Screen"** to use it as a standalone app.

---

## What it Is
The **Qualification Tracker** is a high-speed, mobile-responsive tool designed for Range OICs, NCOICs, and lane safeties. It allows for the management of complex shooting rosters with multiple qualification requirements (e.g., Day, Night, and CBRN) in one unified interface.

## Key Features
*   **Detailed Analytics Breakout:** View pass/fail/pending counts for every specific qualification type individually, in addition to the overall "Fully Qualified" unit status.
*   **Custom Qualification Types:** Dynamically add as many qualification events as needed. Set unique passing thresholds for each (e.g., 23 for Day, 5 for CBRN).
*   **Persistent Configuration:** Your Range Location, Event Name, and Date are now saved to the device, ensuring the exported CSV filename remains consistent even after a page refresh.
*   **Smart Form Clearing:** The roster entry form auto-clears all fields (including Rank, Unit, and Company) after each entry to prevent "ghost data" and accidental duplicate inputs.
*   **Enhanced Mobile Scaling:** Features a "stacking" table design optimized for one-handed use on smartphones.

---

## How it Works

### 1. Range Setup & Naming
Enter your **Range/Location** and **Event Type**. The app automatically generates a professional filename (e.g., `M4_Qual_Range_4_2026-05-03.csv`) for your exports. 

### 2. Define Qualification Standards
Under **"Add Qualification Type,"** enter a label and a minimum passing score. 
*   *Example:* Label "Day", Threshold "23". 
*   Adding a type creates a new column across the entire roster and a new analytics card in the Breakout section.

### 3. Build Your Roster
Input personnel details. The "Add Soldier" button remains disabled until all required fields are filled. Upon clicking, the form resets and focuses back on the "First Name" field for rapid-fire data entry.

### 4. Record & Track
*   **Live Scoring:** Type scores directly into the table. The "Pass/Fail/Pending" status updates instantly.
*   **Fully Qualified Status:** A soldier only moves to "Fully Qualified" once they have passed **every** defined qualification type.
*   **Detailed Breakouts:** Check the **Type Breakout** cards to see exactly how many shooters still need to cycle through specific lanes (e.g., how many shooters are "Open" for Night Fire).

### 5. Backup & Reporting
*   **Save Backup:** Download a `.json` file containing your entire setup and roster.
*   **Load Backup:** Import data from another device or a previous day.
*   **Export for Excel:** Generates a formatted `.csv` report including individual scores and pass/fail status strings for easy filing with S-3.

---

**Pro-Tip for Range Officers:** When switching between multiple lanes or devices, use the **Save Backup File** frequently. If you are using an iOS device, this is the most reliable way to ensure data is preserved across long periods of inactivity.
