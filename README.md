# Light in the Iron Cage
Light in the Iron Cage was created for the purpose of glorifying God and pointing the suffering to Him. As one who was formerly despairing in an [**Iron Cage**](https://kenpulsmusic.com/pilgrimsprogress28.html), I want to point others like me towards the healing light of Jesus through the Holy Spirit. 

Dear reader, I pray that you would be challenged and edified by my words and know the kindness of Christ more and more.

## Site Map
This blog is broken into three main types of posts:
- [The Pilgrim's Log](/content/posts/the-pilgrims-log/); where I talk about living the Christian life.
- [The Library](/content/posts/the-library); where I talk about literature and books.
- [The Ensemble](/content/posts/the-ensemble/); where I talk about music.

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.
