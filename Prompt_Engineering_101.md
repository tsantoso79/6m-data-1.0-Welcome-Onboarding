# **🛠️ Workshop: Setting Up Your Cloud Environment**

For this course, we will use **Google Colab**. It allows you to write and execute Python in your browser, with zero configuration required, free of charge.

## **Step 1: Accessing Colab**

1. Navigate to [colab.research.google.com](https://colab.research.google.com/).  
2. Sign in with your Google Account.

## **Step 2: Creating Your First Notebook**

1. Click on **File** \> **New Notebook**.  
2. You will see a cell ready for code.  
3. Rename the notebook (click the title "Untitled0.ipynb" at the top) to: `DS4_Class1_YourName.ipynb`.

## **Step 3: Hello World (The Sanity Check)**

Type the following code into the first cell and press the **Play** button (or `Shift + Enter`):

```
print("Hello, Data Science Class!")
x = 5
y = 10
print(f"The sum is: {x + y}")
```

If you see the output `The sum is: 15`, your environment is ready\!

## **Step 4: Connecting to Data (Mounting Drive)**

*We will do this often to access datasets.*

1. Click the **Folder** icon on the left sidebar.  
2. Click the **Mount Drive** icon (folder with Google Drive logo).  
3. Run the permission cell that appears.  
4. Verify you can see a folder named `drive`.

## **🛑 Troubleshooting**

* **"Runtime Disconnected":** Check your internet connection. Click "Reconnect" at the top right.  
* **"Quota Exceeded":** (Rare for text data) Ensure you aren't using a GPU runtime unnecessarily. Go to *Runtime \> Change runtime type* and ensure "Hardware accelerator" is set to *None* for today.