# Incident & Event Management Automation (Bash)

## 📌 Overview
This project automates the validation of incident and event statuses in a monitoring environment.
It ensures that events are properly closed when their corresponding incidents are resolved.

## ⚙️ How It Works
- Reads incident statuses from `ticket_status.txt`
- Maps incidents to events using `events_tickets.txt`
- Prompts the user to enter an incident number
- If the incident is closed, the script:
  - Closes the related event
  - Writes the result to `events_status.txt`
  - Prints the event status to the console

## 🛠️ Technologies Used
- Bash / Shell Scripting
- Linux
- File Processing
- Automation

## ▶️ Usage
```bash
./close_events.sh
