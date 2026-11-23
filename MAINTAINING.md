# Maintaining OCS Study Tools

## Page names

Keep published filenames stable so existing bookmarks and links continue to work.

| Display name | Published filename | Purpose |
| --- | --- | --- |
| OCS Study Hub | `index.html` | Main subject menu |
| Military History | `history.html` | History menu and offline downloads |
| POI Study | `military-history.html` | Instructor-aligned study and practice test |
| American Military History Reading Companion | `american-military-history.html` | Chapter review based on independent reading notes |

Edit the working HTML, preview it locally, and commit the edited file under the same name. If an older offline copy is already on someone's device, they need to download the updated file.

## From issue to live site

1. Open a GitHub issue with the need, scope, and a short acceptance checklist. The issue list is the backlog.
2. Make the change on a branch and preview the affected pages locally. Use a commit message that says what changed.
3. Open a pull request against the Pages publishing branch. Reference the issue as `Refs #123` so it stays open through the live check. Review the diff and record your local checks in the pull request.
4. Merge and check the Pages deployment in Actions. Open the live site and verify the issue's acceptance criteria. For study changes, download the affected HTML and test it offline.
5. Record the outcome in the issue, then close it. Record candidate-facing changes in the changelog. Use an optional GitHub Release to mark a milestone or preserve a specific offline copy.

### First backlog issue: Add Volume I, Chapters 3–4

As a candidate, I want to review Chapters 3 and 4 separately or in a mixed session so I can study the Revolution through independence.

- [ ] Chapters 3 and 4 are individually selectable and show only their own cards.
- [ ] Mixed Review includes both new chapters and still includes Chapters 1 and 2.
- [ ] New recall prompts connect specific events to a broader lesson, with references to the assigned reading.
- [ ] Pages deployment succeeds, History links work on the live site, and the downloaded companion works offline.
