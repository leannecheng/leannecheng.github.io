---
name: LRC Streaming Snapshots
tools: [Python, Streamlit, Pandas, Altair, Google Drive API]
image: ../assets/photos/StreamingPreview.png
description: An interactive dashboard and uploader that automate cleaning and visualizing language streaming data, saving staff hours every term and revealing patterns in resource usage across departments.
weight: 1
---

# LRC Streaming Snapshots

#### Summer 2025
---
<div style="display: flex; justify-content: center; align-items: center; gap: 2rem; margin: 0.5rem 0; flex-wrap: wrap;">
  <img src="../assets/photos/StreamingDash.png" alt="LRC Streaming Dashboard Preview" width="1000" style="max-width: 95%; border-radius: 24px; box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);" />
</div>

**LRC Streaming Snapshots** is a commissioned tool I built for the University of Michigan’s Language Resource Center. It automates the cleanup and visualization of streaming media checkout data, revealing which departments use movies and shows to support language teaching.

Before this project, streaming data was never visualized, and staff spent **up to 12 hours every term** manually cleaning spreadsheets to get even basic summaries. Now, they can upload a file and get **clean, interactive charts in seconds**, helping them make faster, data-driven decisions about resource allocation and program support.

---

## What It Does

- Tracks streaming activity across terms  
- Filters by department and course level  
- Highlights top departments by student usage and reservations  
- Provides interactive, easy-to-read charts  
- Fetches updated data automatically from Google Drive  

---

## Data Uploader

I also built a web uploader so staff can drop in new term files, automatically clean the data, and update the dashboard. This tool ensures the dashboard stays up to date and eliminates repetitive manual work.

---

<div style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; margin: 2rem 0;">
  <img src="../assets/photos/StreamingUploader.png" alt="Uploader Screenshot" width="800" style="max-width: 95%; border-radius: 16px; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);" />
</div>

---

## Tools Used

**Python**, **Streamlit**, **Pandas**, **Altair**, **Google Drive API**, **Git & GitHub**

---

<p class="text-center">
  {% include elements/button.html link="https://lrc-streaming.streamlit.app/" text="View Dashboard" %}
  {% include elements/button.html link="https://github.com/leannecheng/LRC-Streaming-Uploader" text="View Uploader Repo" %}
</p>
