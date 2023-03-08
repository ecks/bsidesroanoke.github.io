# bsidesroanoke.github.io

A site covering the BSides Roanoke Page.

## Developing locally


1. Start a new branch
2. Make desired changes
3. Test changes locally using jekyll-serve container in the director this repository is in: (*Using alpine, because latest did no work as of March 1st. Feel free to explore other versions.*)

   1. On Linux/Mac:

          docker run -it --rm -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve:alpine

   2. On Windows command line:

          docker run -it --rm -p 4000:4000 -v %cd%:/site bretfisher/jekyll-serve:alpine

4. Commit and push branch
5. Create a PR to merge changes into main.
6. Get approval from another BSides Roanoke member, in order to merge to main.
7. Github actions will take care of publishing the website.

### Adding a new post

Follow main steps above.  The desired change will start with copying a file from

Remember that Aaron is the boss of all changes, check with him first