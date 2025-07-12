# Webring

a webring for friends.
code based on [ringfairy](https://github.com/k3rs3d/ringfairy) and [roboring](https://github.com/stellophiliac/roboring/)

# join

1. choose a slug for your site (a unique identifier)

2. add the webring links to your site:

```html
<a href="https://404salad.github.io/webring/YOUR_SLUG/previous"> <- </a>
<a href="https://404salad.github.io/webring">webring</a>
<a href="https://404salad.github.io/webring/YOUR_SLUG/next"> -> </a>
```

3. submit a pull request adding yourself to websites.json

4. entries should have the name of your site, your slug, a short description, your site link, your rss feed (if applicable), and a contact link (such as an email or social media)

here's an example entry:

```json
{
"name": "Example Website",
"slug": "example",
"about": "example site",
"url": "https://example.com/",
"rss": "https://example.com/index.xml",
"owner": "person@example.com"
}
```


## 🔮 What is a Webring?

A webring is a collection of websites linked together in a loop. Each website contains links to the previous and next websites in the ring. If you navigate far enough, eventually you end up back where you started! 

<img src="https://upload.wikimedia.org/wikipedia/commons/9/97/Webringwork.png" width="512" alt="Webring example graphic"/>

Webrings were popular in the early days of the internet as a way for website owners to promote each other's content and encourage community engagement. 

This is a tool for anyone who has some kind of personal website or blog and wishes to connect with others. You can use it to grow your own online community from scratch!

---

That's it!  
Happy linking 🌐
