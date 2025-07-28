# Reflection: Automated Project Setup and API Data Fetcher

## What was the goal of this project?
The goal of this project was to write a shell script that automates the setup of a project directory structure and fetches data from an external API. The script should organize the data in a clean format using `jq` and store it for later use.

## What did I learn while doing this?
- Use basic shell scripting in Linux.
- Work with `curl` to fetch data from APIs.
- Use `jq` to process JSON data in a clean and structured format.
- Create and manage file paths using shell commands like `mkdir`, `touch`, `mv`, and `chmod`.
- Understand and fix common errors like missing directories or command not found.

## What challenges did I face?
At first, I got an error saying "`No such file or directory`" when trying to save the JSON data. I realized the target folder must exist before writing to it. I also faced an issue with `.git` and directory structure, but I resolved it by carefully organizing folders and using `shopt -s extglob`.

## What commands/tools did I use?
- `mkdir`, `mv`, `touch`, `chmod` — for file and permission management
- `curl` — to fetch data silently
- `jq` — to filter and structure the JSON data
- `bash` — to run and write shell scripts
- `git` — to track the project and push to GitHub

## How do I feel about this project?
This project helped me understand Linux scripting better and gave me hands-on experience with real-world tools like `curl`, `jq`, and `git`. I feel more confident working with command-line interfaces now.

## What would I improve next time?
Next time, I would:
- Add error handling to the script for API failures.
- Include logging to track script runs.
- Try scheduling the script using `cron` for automation.


