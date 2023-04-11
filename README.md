# Hugo notes and commands

## Start local Hugo Server
From the __PersonalBlog__ folder run:
```
hugo server
```
Then open http://localhost:1313/ from your web browser.

## Add blog entry
From the __PersonalBlog__ folder run:
```
hugo new posts/my-first-post.md
```

This will create a new markdown file in __content/posts__ for you to write your post. 

More info at: https://gohugo.io/getting-started/quick-start/#add-content

## Change blog theme
From the __PersonalBlog__ folder run:
```
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```