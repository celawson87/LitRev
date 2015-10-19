# LitRev
McMahon Lab Literature Review Blog

[Link to website](http://mcmahonlab.github.io/LitRev/)

# LitRev
McMahon Lab Literature Review Blog

[Link to website](http://mcmahonlab.github.io/LitRev/)

## How to contribute

## Installation
1. Fork this repo.
2. Clone your version of this repo.
3. Navigate to the repo.
```
cd LitRev
```
4. Install bundler.  You may have to use 'sudo'.
```
gem install bundler
bundle install
```
5. (At some point) Add the upstream remote.
```
git remote add upstream https://github.com/McMahonLab/LitRev
```

##  How to create a blog post
**Always update your fork and local copy first** - pull (or Fetch+merge) from upstream (gh-pages branch) and then push to origin.

### Create your own post
1. Copy the template from the `_drafts` to `_posts`.  Rename the file to be relevant to the article you are reviewing.
Example:
```
cp _drafts/YYYY-MM-DD-subject.md _posts/<YYYY-MM-DD-topic>.md
```
Replace `<YYYY-MM-DD-topic>` with the current date and topic (should include the journal abbreviation, first author, and year).
Example for blog post on Sept. 10th, 2015 reviewing an article in _ISME_ with the first author _Stevens_ that was published in _2014_ the file would be called.
`2015-09-10-isme-stevens-2014.md`
2. Fill in the header information for your post.
  - Change the Title
  - Update the date to the current date
  - Replace 'tag1' and 'tag2' with tags related to your post.  Feel free to add additional tags as well
3. Write your post, replacing the 'POST GOES HERE' line.
    For help with markdown see [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
4. Check your work in the browser. (Optional, see below for instructions)
5. Add and commit your changes
6. Push to your fork(origin) and make a pull request to the upstream fork.

### Checking your work in the browser
1. From the root of the repo serve the site.
```
bundle exec jekyll serve
```
2. Check the site in your browser at http://127.0.0.1:4000/LitRev/
