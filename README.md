# CV

This repo links the CV PDF file from Overleaf.

1. Create a project to edit your CV on Overleaf, e.g., `CV_edit`.
2. Create a second project to visualize your CV on Overleaf, e.g., `CV_viz`.
3. Import the output of the edit project into the visualization project:
   - Open your `CV_viz` project.
   - Click on "Add Files" -> "From another project" -> "Select a Project".
   - Choose your `CV_edit` project.
   - In the next step, select the output PDF file (e.g., `main.pdf`).
   - This will link the PDF from `CV_edit` into your `CV_viz` project, allowing you to visualize the latest compiled version.
4. Synchronize the visualization project with GitHub:
   - In Overleaf, go to the `CV_viz` project settings.
   - Under "Sync", choose "GitHub" and follow the instructions to connect to your GitHub repository.
   - Make sure that your GitHub repository is linked to the correct branch where you want the PDF file to be uploaded.
   - Once linked, any changes made in the `CV_edit` project and reflected in the `CV_viz` project will automatically update in the GitHub repository.

Now, any updates you make in the `CV_edit` project on Overleaf will be visualized in the `CV_viz` project and automatically synchronized to your GitHub repository.
