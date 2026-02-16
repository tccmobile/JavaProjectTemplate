# Java Project Template

Welcome! This is a template repository for the Intro to Java Course. Use this template to create your own Java projects.

## 📋 How to Use This Template

### Option 1: Using GitHub Web Interface (Recommended for Beginners)

1. Click the green **"Use this template"** button at the top of this repository
2. Choose a name for your repository (e.g., `java-assignment-1`)
3. Select **Public** or **Private** visibility
4. Click **"Create repository from template"**
5. Your own copy of this template is now ready to use!

### Option 2: Clone the Repository

If you prefer to clone it directly:

```bash
git clone https://github.com/tccmobile/JavaProjectTemplate.git
cd JavaProjectTemplate
```

## 🚀 Running Your Code in GitHub Codespaces

### Starting Codespaces

1. Go to your repository on GitHub
2. Click the green **"Code"** button
3. Select the **"Codespaces"** tab
4. Click **"Create codespace on main"**
5. Wait for your Codespace to load (this may take 1-2 minutes on first run)

### Running Your Java Program

In the Codespaces terminal, use Maven to run your program:

```bash
mvn clean compile exec:java
```

You should see:
```
Hello, World!
```

## 🐛 Debugging Your Code

### Setting Breakpoints

1. Open `src/main/java/HelloWorld.java` in your editor
2. Click on the line number where you want to pause execution (a red dot will appear)
3. Go to the **Run and Debug** view (click the play icon with a bug on the left sidebar)
4. Click **"Run and Debug"** or press `F5`
5. Your code will run and pause at the breakpoint

### Viewing Variables

When your code pauses at a breakpoint:
- **Local Variables** panel shows all variables in the current scope
- Hover over any variable in the code to see its current value
- Use the **Debug Console** to type expressions and check values

### Step Through Code

- **Step Over** (F10): Execute the current line and move to the next
- **Step Into** (F11): Step into function calls
- **Step Out** (Shift+F11): Exit the current function
- **Continue** (F5): Resume execution until the next breakpoint

## 📁 Project Structure

```
JavaProjectTemplate/
├── src/
│   └── main/
│       └── java/
│           └── HelloWorld.java    ← Your Java code goes here
├── pom.xml                         ← Maven configuration file
├── .vscode/
│   ├── launch.json                ← Debugger configuration
│   └── settings.json              ← VS Code settings
├── .gitignore                      ← Tells Git which files to ignore
└── README.md                       ← This file
```

## 🛠️ Adding More Java Files

1. Create new `.java` files in the `src/main/java/` directory
2. Make sure your class names match your filenames
3. Run with Maven: `mvn clean compile exec:java -Dexec.mainClass="YourClassName"`

## 📝 Maven Commands

- **Compile:** `mvn clean compile` - Compiles all Java files
- **Run:** `mvn exec:java -Dexec.mainClass="HelloWorld"` - Runs a specific class
- **Clean:** `mvn clean` - Removes compiled files

## ❓ Troubleshooting

**"Command not found: mvn"**
- Maven might still be installing. Wait a moment and try again.

**"Cannot find symbol"**
- Check that your Java file is in the correct directory: `src/main/java/`
- Verify the class name matches the filename

**Debugger won't start**
- Make sure you're using Java 11 or later
- Check the VS Code Debug Console for error messages

## 💡 Tips

- Always test your code in Codespaces before submitting
- Use meaningful variable names
- Add comments to explain your code
- Keep your code organized in separate methods

## 🆘 Need Help?

- Check the course materials and lecture notes
- Review the Java documentation: https://docs.oracle.com/javase/tutorial/
- Ask questions in the course discussion forum

---

Happy coding! 🎉