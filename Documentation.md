 DevOps Internship – Task 4 Documentation

Task Title:

Build a Version-Controlled DevOps Project with Git
 Objective:

To manage a DevOps project using Git best practices including version control, branching, commits, and documentation.

Tools Used:

* Git – for version control
* GitHub – for remote repository hosting and collaboration

Repository Structure:

task-4/
├── app.js
├── main.sh
├── .gitignore
├── README.md
├── documentation.md
└── feature-branches/


 Git Workflow Followed:

1. Repository Initialization

   * Initialized local repo with `git init`
   * Connected to GitHub using `git remote add origin`

2. Branching Strategy

   * Created the following branches:

     * `main` – production/stable branch
     * `dev` – development integration branch
     * `feature/login`, `feature/ui` – feature-specific branches

3. Commit Best Practices

   * Commits made with clear, descriptive messages.
   * Example: `git commit -m "Add login script and auth logic"`

4. Pull Requests & Merges

   * Feature branches were merged into `dev` using pull requests.
   * `dev` merged into `main` after testing and validation.

5. .gitignore Usage

   * Added common ignored files like `node_modules/`, `.env`, and temporary Word backups (`~$filename.docx`)

6. Tagging

   * Created Git tags to mark significant releases using:

     ```bash
     git tag -a v1.0 -m "Initial working version"
     git push origin v1.0
     ```

Documentation Process:

* All tasks were documented using Markdown in `README.md` and `documentation.md`.
* Markdown includes headings, code snippets, and task breakdowns.
