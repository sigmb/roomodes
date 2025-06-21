**Roo Modes**

Follow https://github.com/shariqriazz/maestro to install latest .roomodes

This version added Brainstormer and Project Brief mode which help expand ideas.

**Instructions**
1. Create a docs and a file called initialRequirements.md in the folder.

2. Write all your ideas in the initialRequirements.md. Add a section for technical assumptions. Give as much information as you know.

3. Change Roo Mode to Brainstormer and start a task with this prompt 
```
Help me brainstorm @docs/initialInitialRequirements.md
```

4. Brainstormer will create a docs/expandedRequirements.md file. Review the file. Make changes, if necessary. Re-run Brainstormer pointing the docs/expandedRequirements.md, if necessary.

5. Change Roo Mode to Project Brief and start a task with this prompt
```
Help me structure my thoughts in @docs/expandedRequirements.md
```

6. Project Brief will create a docs/projectBrief.md file. Review the file. Make changes, if necessary.

7. Change Roo Mode to Maestro and create a task with this prompt
```
Start with @docs/projectBrief.md
```
8.. Let it cook.

9. If it stops, create a new task with prompt
```
Proceed
```

