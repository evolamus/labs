# EvoLaMus labs
Lab assignments for the Evolution of Language & Music course.

Website: [evolamus.github.io/labs](https://evolamus.github.io/labs/)

## Making edits
To make edits in the lab assignments and publish them to the website, you need to:
1. Clone this repository locally:
   ```
   git clone git@github.com:evolamus/labs.git
   cd labs
   ```
2. Install [jupyter-book](https://jupyterbook.org/)
   ```
   pip install -U jupyter-book

   ```
3. Make sure your local files are up-to-date with the ones in this repository:
   ```
   git pull
   ```
4. \*Make the changes to the local files on your computer\*
5. Rebuild the book:
   ```
   jupyter book build
   ```
6. Add, commit and push the changes to this repository:
   ```
   git add *
   git commit -m 'some edits'
   git push
   ```
7. Typically the changes should be live after a few minutes. If you don't see the changes, try opening the website in an incognito window; if the changes do show up there, it should be fine. If not, check the [Actions tab](https://github.com/evolamus/labs/actions) of this repository for build fails.

Steps 1 and 2 only need to be done once; then repeat steps 3 through 7 anytime you want to make new edits.
