\# Session 2 Reflection



\## Q1. How do Issues and pull requests together support change control?



Issues and pull requests help developers manage software changes in an organised way. An Issue records the problem or requested change, while a pull request proposes the solution for review. In my exercise, Issue #1 requested a traceability note template, and Pull Request #2 submitted the file for review. Linking them using "Closes #1" helps maintain traceability and automatically closes the Issue after merging.



\## Q2. Why did the conflict in Part 4 happen, and how could a team reduce such conflicts?



The conflict happened because Branch A and Branch B changed the same line in the same file differently. Branch A changed the deployment target to staging, while Branch B changed it to production. Git could not automatically decide which version should be kept. A team can reduce conflicts by communicating regularly, pulling the latest changes before starting work, and avoiding unnecessary changes to the same files.



\## Q3. What would be lost if people merged straight into main without a pull request?



Merging directly into main without a pull request would reduce opportunities for code review and discussion. Mistakes or bugs could enter the main branch without being checked by another developer. The team would also lose a clear record of review comments, suggestions and approval decisions. Pull requests help improve software quality and make changes easier to track.

