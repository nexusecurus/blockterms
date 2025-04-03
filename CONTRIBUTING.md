# Contributing to the NexuSecurus BlockXicon

We welcome contributions to expand the **NexuSecurus BlockXicon**. If you’d like to add a new term or make changes to an existing one, please follow these detailed guidelines.

## How to Contribute

### **1. Fork the Repository**

If you haven’t done so already, fork the repository to your own GitHub account by clicking the **Fork** button in the top-right corner of the repository page.

This creates a copy of the repository under your account where you can make changes without affecting the original project.

### **2. Clone the Repository**

Once you've forked the repository, clone it to your local machine to make your changes:

```bash
git clone https://github.com/your-username/blockxicon.git
cd blockxicon
```

Replace `your-username` with your GitHub username.

### **3. Create a New Branch for Your Changes**

It's important to make changes in a new branch. This keeps your work isolated and makes it easier to submit changes.

```bash
git checkout -b add-your-term
```

Replace `add-your-term` with a descriptive name for the branch, such as the term you plan to add.

### **4. Add Your Term to the Glossary**

Open the `glossary.md` file in a text editor of your choice and locate the correct alphabetical position for your new term. Make sure to **add your term in the correct alphabetical location**. If your term isn’t positioned properly, the PR may be rejected.

Your term should be formatted as follows:

```markdown
### YourTerm
Description of your term goes here. Please provide a clear, concise, and informative definition without using HTML tags. Make sure there are **no empty lines** between paragraphs in the description.
```

Use proper spelling, grammar, and punctuation to ensure the definition is professional and easy to understand.

### **5. Commit Your Changes**

Once you've added the new term or updated the glossary, commit your changes:

```bash
git add blockxicon/glossary.md
git commit -m "Added new term: YourTerm"
```

### **6. Push Your Changes**

Push your changes to your forked repository:

```bash
git push origin add-your-term
```

This uploads your changes to the branch you created.

### **7. Open a Pull Request**

Now, go to your forked repository on GitHub. You should see a banner asking if you'd like to submit a pull request. Click on **Compare & pull request**.

- Provide a clear and concise description of the changes you made.
- Make sure your PR is directed to the main repository's `main` branch.

Once you've reviewed your PR, click **Create pull request**. This will notify the NexuSecurus team that your changes are ready for review.

---

## **Using GitHub.com Directly (No Terminal)**

If you're not comfortable using the terminal, you can make changes directly from the GitHub website. Follow these steps:

### **1. Fork the Repository**

Click the **Fork** button in the top-right corner of the repository page. This creates a copy of the repository under your GitHub account.

### **2. Navigate to the `glossary.md` File**

Go to your forked repository on GitHub and navigate to `blockxicon/glossary.md`. Click the pencil icon (edit) to begin making changes.

### **3. Edit the File**

- **Add your term** in the correct alphabetical position.
- Use the following format:

```markdown
### YourTerm
Description of your term goes here. Please provide a clear, concise, and informative definition without using HTML tags. Make sure there are **no empty lines** between paragraphs in the description.
```

Make sure your changes are neat, clear, and fit within the accepted categories (listed below).

### **4. Commit Your Changes**

Once you're happy with the changes, scroll down to the **Commit changes** section. Add a meaningful commit message, such as "Added new term: YourTerm," and click **Commit changes**.

### **5. Create a Pull Request**

After committing your changes, GitHub will show a banner asking if you want to create a pull request. Click on **Pull Request**.

- Add a description of the changes you made in the PR.
- Make sure the PR is directed to the main repository's `main` branch.

Click **Create pull request** to submit it.

---

## Accepted Terms

We are currently accepting the following types of terms:

- Blockchain-related terms
- Active mining pool names
- Active validator names
- CEX and DEX exchange names
- Blockchain network names (active or inactive)
- Known scammers
- Important personalities in blockchain creation
- Important dates in blockchain history

Make sure that the term you're adding fits one of the categories above.

---

## **PR Review Process**

Once your pull request is submitted, it will be reviewed by NexuSecurus personnel. We will ensure that:

- The term is placed in the correct alphabetical order.
- The description follows our guidelines and doesn't include HTML tags.
- The term fits within the accepted categories listed above.

### **Possible Outcomes of the Review**:
- **Approved**: If everything looks good, your PR will be merged into the main repository.
- **Requested Changes**: If there are issues with your PR, we may ask for changes. Please address the feedback, and push the changes to your branch.
- **Rejected**: If the PR doesn't meet the guidelines or is irrelevant, it will be closed.

---

## Conflict Resolution

In the event of conflicts during the pull request process:

- Follow standard Git conflict resolution practices. Typically, this involves running the following commands:

```bash
git pull origin main
```

- This will merge the changes from the main repository into your branch. If conflicts arise, resolve them manually by editing the files.
- After resolving conflicts, commit and push the changes.

If you need assistance with resolving conflicts, refer to the [Git conflict resolution guide](https://git-scm.com/docs/git-merge#_conflict_resolution).

---

## Code of Conduct

By contributing to this project, you agree to adhere to the **NexuSecurus Code of Conduct**. We strive to create a welcoming and respectful environment for all contributors.

---

## Thank You!

We are excited to have you contribute to the **NexuSecurus BlockXicon**! Together, we can build the largest and most comprehensive glossary for blockchain and crypto on the internet.
