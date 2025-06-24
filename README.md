**Roo Modes**

Copy the .roomodes in your project or update your global roomode and add the contents of custom_modes.yaml

This version adds Brainstormer, Product Manager (PRD Generator) and Engineering Manager (Task Generator).

**Instructions**
1. Create a docs and a file called initialRequirements.md in the folder.

2. Write all your ideas in the initialRequirements.md. Add a section for technical assumptions. Give as much information as you know.

3. Change Roo Mode to Brainstormer and start a task with this prompt 
```
Help me brainstorm @docs/initialInitialRequirements.md
```

4. Brainstormer will create a docs/expandedRequirements.md file. Review the file. Make changes, if necessary. Re-run Brainstormer pointing the docs/expandedRequirements.md, if necessary.

5. Change Roo Mode to Product Manager (PRD Generator) and start a task with this prompt
```
Use @docs/expandedRequirements.md
```

6. Product Manager (PRD Generator) will create a docs/prd-[product-name].md file. Review the file. Make changes, if necessary.

7. Change Roo Mode to Engineering Manager (Task Generator) and create a task with this prompt
```
Use @docs/prd-[product-name].md as PRD document.
```
8. Let it cook.

9. If it stops, create a new task with prompt
```
Proceed
```

10. Change Roo Mode to Code and create a new task with prompt
```
Read @tasks/feature-[featur-name].md, implement @tasks/tasks-[sub-task number]-[sub task name].md
```

11. Confirm the task was completed and in working order. You will need to do vibe coding if it is not working upto spec until satisfied.

12. When task is truly completed, execute a prompt in the current task
```
Update task completed in @tasks/tasks-[sub-task number]-[sub task name].md and commit the code changes.
```


