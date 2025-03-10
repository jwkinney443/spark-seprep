# Assignment 4

**Objective:**

This assignment aims to enhance your version control skills by guiding you through setting up GitHub repositories, creating files,
submitting pull requests, and establishing an upstream repository.

**Instructions:**

**1. GitHub Repository Setup:**

   - Work within the `DS219/spark-seprep/student-work/assignment-4` directory structure on GitHub.

**2. Forking the Main Repository:**

   - Create a fork of the `DS219/spark-seprep` repository.

**3. Cloning your Fork:**

   - Clone your fork of the `DS219/spark-seprep` repository.

   ```bash
   mkdir -p ~/github
   cd ~/github
   git clone git@github.com:yourgh-name/spark-seprep.git  # if your SSH key is set correctly in GH
   cd spark-seprep
   git remote -v
   git remote add upstream git@github.com:DS219/spark-seprep.git  # if your SSH key is set correctly in GH
   cd student-work/assignment-4 #<-this is where you'll add your files
   ```

**4. Create your File**

   - Create a markdown file in the `student-work/assignment-4/` folder with the following nomenclature: `yourname.md`. Take a look at the [example here.](../student-work/assignment-4/urvashimohnani.md) 
   - Add a header using `#` and add your name.
   - Then in normal text add an introduction with your favorite programming language and why.
   - Add another header under your introduction, `## Example code`
   - Underneath that, add a short example of your code, using "triple backticks" `````
   - Add a third header with `### Code Explanation` to describe the code and how to run it.
   - Make sure to preview your file to ensure the markdown format you used is correct (spaces and new lines are important in markdown).
   - Again, Use the [example](../student-work/urvashimohnani.md) to help you. You can view the `raw` format to see the text un-rendered.

   ```bash
   git checkout -b assignment-4-branch
   cd student-work/assignment-4/
   touch yourname.md
   # Open the document, add content, and save.
   # look at student-work/assignment-4/urvashimohnani.md for an example

   git add yourname.md
   git commit -m "[your name]: Assignment 4"
   git push origin assignment-4-branch
   ```

**5. Final PR to Main Upstream:**

   - Submit a pull request to the main upstream repository (`DS219/spark-seprep`) containing the changes to `student-work/yourname.md`.
   - Fill out this form https://forms.gle/CNgVQ8n4WPACyK9w5 to complete your submission!

**Important Notes:**

- Maintain clear and descriptive commit messages.
- Communicate effectively with your teammate if applicable.
- Thoroughly review your work during the pull request phase.
- Seek assistance from your instructor if any issues arise.

**Submission:**

- Complete a pull request within the GitHub repository.
- Ensure all steps are finished, including setting up upstream repositories, and submit the final pull request to the main upstream repository.

This assignment not only enhances GitHub collaboration skills but also emphasizes effective communication and teamwork. If you have questions or need clarification, contact your instructor. Good luck and happy collaborating!
