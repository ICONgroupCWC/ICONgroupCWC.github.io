# ICON contribution guide.

## Stpes from set up to publishing.

- Clone the repo.
```bash
git clone https://github.com/ICONgroupCWC/ICONgroupCWC.github.io.git
```
- crete a new branch with your own name.
```bash
git checkout -b <your-name>
```

- Make sure that you setup quarto, the blogging system we use. [This Guide](https://quarto.org/docs/get-started/) is straight forward and easy to follow. Yo have two options. either you write in jupyter notebook or vscode.



- Inside the posts folder, create a either <post.ipynb> or <post>.qmd file, where post is the post name.
    - Note that: every thing will not be flat files inside posts, rather they will be in a folder with the category name for which the post belongs. Below, a defnition of what a category is, is given.

- Write your post in the file you created. Make sure that you follow the [quarto guide](https://quarto.org/docs/get-started/hello/jupyter.html) to write your post. Basically, it's a markdown file with some extra features.

- Render the post to see how it looks like. You can do that by running the following command in the terminal.
```bash
quarto render
```
- If you are happy with the post, then you can publish it. To do that, you need to push your changes to the remote repo. To do that, run the following commands.
```bash
git add .
git commit -m "your commit message"
git push origin <your-name>
```
All the above steps could be done using GitHub Desktop, which is a GUI for git. You can download it from [here](https://desktop.github.com/) or in vscode itself.

- Now, you need to create a pull request to merge your changes with the main branch. To do that, go to the repo page on GitHub and click on the pull request button. Then, click on the new pull request button. Make sure that you are merging your branch with the main branch. Then, click on create pull request. You can add a description to your pull request if you want. Then, click on create pull request again. Now, you have created a pull request. You can see the status of your pull request in the pull request tab in the repo page.

- Assign the pull request to two of the reviewers. The reviewer will review your post and give you feedback. You can see the feedback in the pull request tab. If there are any changes that you need to make, then make them and push them to the remote repo. The pull request will be updated automatically. If there are no changes, then the reviewer will merge your pull request with the main branch.

