# Azure Blob Trigger Function

This project uses **Azure Functions** to automatically trigger a Python function whenever a file is uploaded to an Azure Blob container.

## 🔧 Services Used
- Azure Functions
- Azure Blob Storage
- Azure Portal
- GitHub (for deployment)

## 📂 Project Structure

```
azure-blob-trigger-function/
├── function_app/
│   ├── __init__.py
│   ├── function.json
│   └── requirements.txt
├── host.json
└── README.md
```

## 🚀 How It Works
- Upload any file to your blob container named `slogs`.
- The Azure Function will automatically trigger and log file details (name and size).

## 🐙 GitHub Deployment

### Step 1: Upload to GitHub
1. Create a new GitHub repository.
2. Upload the contents of this folder.
3. Push it using Git or GitHub web UI.

### Step 2: Connect GitHub to Azure Function
1. Go to your Function App in Azure Portal.
2. Open **Deployment Center**.
3. Choose **GitHub** as source.
4. Select your repo and branch.
5. Click **Finish**.

Azure will automatically deploy your code.

---

Created by: rajfunction (Azure Function App Name)
