# http://waz.ski/

## Managing Content

    $ octopress new draft "New Blog Post"
    $ octopress publish _drafts/new-blog-post.md

## Development

    $ jekyll serve

## Deployment

    $ jekyll build
    $ git commit [...]
    $ git push dokku master
