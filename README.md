# et_devsecops_myscript_config

This repository contains configuration scripts and utilities used for automating remote server tasks using Jenkins pipelines.

## 📄 Project Overview

- Syncs latest committed scripts to remote servers
- Executes Python automation scripts
- Updates crontab to schedule scripts at regular intervals

## 🛠 Folder Structure

et_devsecops_myscript_config/ 
├── scripts/ 
│ 
├── config_script.py 
│ 
├── data_fetch.py 
└── configs/ 
└── settings.yaml


## 🚀 How It Works

1. Jenkins pipeline checks out this repository.
2. The latest pushed file is transferred securely to the remote server.
3. The script is executed remotely.
4. A crontab entry is updated for periodic execution.

## 🔧 Requirements

- Python 3.x installed on the remote server
- Jenkins server configured with GitHub Token and SSH key

## 👨‍💻 Author

Maintained by Abdullah bin Amin

---
