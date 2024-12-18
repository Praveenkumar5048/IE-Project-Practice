# IE CODE Project expo 2024-25
## Project Mentees, add your weekly works/tasks to your respective folders 

## **Instructions for Adding Your Work**

### **1. Fork the Repository**
- Navigate to the [original repository](https://github.com/original-username/repository-name) on GitHub.
- Click the **Fork** button in the top-right corner to create a copy of the repository under your GitHub account.

### **2. Clone Your Forked Repository**
- Copy the URL of your forked repository (e.g., `https://github.com/your-username/repository-name.git`).
- Open a terminal and run the following command to clone the repository:
  ```bash
  git clone https://github.com/your-username/repository-name.git
  ```
- Navigate to the cloned repository directory:
  ```bash
  cd repository-name
  ```

### **3. Add the Original Repository as Upstream**
- To keep your fork updated with changes from the original repository, add it as a remote:
  ```bash
  git remote add upstream https://github.com/Sagarshivalingappaathani/IE-Project-Practice.git
  ```

### **4. Make Changes**
- Make the necessary changes or additions in your local repository using your preferred code editor.
- Stage the changes:
  ```bash
  git add .
  ```
- Commit the changes with a meaningful message:
  ```bash
  git commit -m "Add a meaningful commit message"
  ```

### **6. Push Changes to Your Fork**
- Push your branch to your forked repository on GitHub:
  ```bash
  git push origin main
  ```

### **7. Push Changes to Original Repository (Method 1)**
- To keep your fork in sync with the original repository:
  ```bash
  git push upstream main
  ```

### **8. Push Changes to Original Repository (Method 2 -- Create a Pull Request)**
- Go to your forked repository on GitHub.
- Click the **Compare & pull request** button.
- Fill out the details:
  - Provide a clear title for your pull request.
  - Add a brief description of the changes you’ve made.
- Submit the pull request.
