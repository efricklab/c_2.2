## ✅ **2.2 Lab - Hello World in C (GitHub Codespaces Version)**

### **Introduction**

In this lab, you will write, compile, and run your first C program in **GitHub Codespaces**. Codespaces gives you a cloud-based development environment with `gcc` already installed, so you can start coding right away with no local setup.

---

### **Objectives**

By the end of this lab, you will:

1. Open and use a GitHub Codespace.
2. Create and save a C program.
3. Compile and run the C program using the terminal.
4. Modify and rerun the program to see changes.

---

### **Lab Steps**

---

### ✅ Step 1: Open the Codespace

1. Go to your GitHub repository.
2. Click the green **Code** button → Select **Codespaces** → Click **Create codespace on main**.

---

### ✅ Step 2: Create Your First C Program

1. In the Codespaces editor, click the **Explorer** icon on the left sidebar.

2. Right-click the folder (or click “New File”) and name the file: `hello_world.c`

3. Verify the following code:

   ```c
   #include <stdio.h>

   int main() {
       // This is a simple C program that prints "Hello, World!"
       printf("Hello, World!\n");
       return 0;
   }
   ```

4. Save the file with `Ctrl+S` or `Cmd+S`.

---

### ✅ Step 3: Compile the Program Using gcc

1. Open the terminal from the top menu: **Terminal > New Terminal**

2. In the terminal, run:

   ```bash
   gcc hello_world.c -o hello_world
   ```

3. Confirm the executable was created:

   ```bash
   ls
   ```

   You should see `hello_world` listed.

---

### ✅ Step 4: Run the Program

1. In the terminal, run the compiled program:

   ```bash
   ./hello_world
   ```

2. ✅ **Expected Output:**

   ```
   Hello, World!
   ```

---

### ✅ Step 5: Modify and Re-run the Program

1. Open `hello_world.c` in the editor again.

2. Change the `printf` line to:

   ```c
   printf("Welcome to C programming in GitHub Codespaces!\n");
   ```

3. Save the file.

4. Recompile and rerun:

   ```bash
   gcc hello_world.c -o hello_world
   ./hello_world
   ```

5. ✅ **Expected Output:**

   ```
   Welcome to C programming in GitHub Codespaces!
   ```

---

### ✅ Summary

In this lab, you successfully used GitHub Codespaces to:

* Write a basic C program
* Compile it using `gcc`
* Run it in the terminal
* Modify and recompile to observe changes

You're now ready to move on to more advanced C programming concepts, all in the cloud.
