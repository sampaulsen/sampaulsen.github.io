# Minimal Mistakes remote theme starter

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

## Basic Setup

- Install [Git](https://git-scm.com/download/win)
- Create a folder to store your sites files. For example, `~/Desktop/GitWebsite/`
- Open the command prompt
- Navigate to your site folder: `cd /Desktop/GitWebsite/`
- Clone this repository: `git clone https://github.com/jamessutton1/jamessutton1.github.io.git`
- Customize files with markdown as needed!
- Update website with following commands (Run these from the `~/Desktop/GitWebsite/` folder)
- `git add --all`
- `git commit -m "some comment"`
- `git push -u origin master`
- Your domain, [**jamessutton1.github.io**](https://jamessutton1.github.io/) should be ready in a minute!

[**Markdown refrence**](https://kramdown.gettalong.org/quickref.html)

[**Documentation**](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)

[**Example Files**](https://github.com/mmistakes/minimal-mistakes/tree/master/docs)

## Programming Guide

- All of text is markdown. Use [**Markdown refrence**](https://kramdown.gettalong.org/quickref.html)
- `_config.yml` sets global site variables
- `index.html` is homepage settings
- `_pages/about.md` is about page settings
- `_posts` contains all posts. The date in file name sets the post's "post date." You can add subfolders to this folder for organization.
- All images go in `/assets/images/`. Try to keep image size under 2 MB for quick loading. You can also link images. See [post examples](https://github.com/mmistakes/minimal-mistakes/tree/master/docs/_posts). When viewing `.md` files in GitHub, click the Raw button to view it as plaintext code. 
- I added a site icon that appears in the tab on mobile and desktop. If you want to change these, delete all of the image files in the root folder. Create a new image set [Here](https://favicon.io/). Extract the download and copy the photos to the root website directory.
- Paste the html code snippet given by the Favicon generator into this file `/_includes/custom.html`. Mine was

~~~ html
<!-- start custom head snippets -->
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
<!-- end custom head snippets -->
~~~

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
