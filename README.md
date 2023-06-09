# javascriptjam.com

The new and improved [JavaScript Jam](https://www.javascriptjam.com/) website built with Astro and deployed on Edgio 🚀

## Sitemap

- [Home Page](#home-page)
- [About](#about)
- [Composability Summit](#composability-summit)
- [Newsletter Archive](#newsletter-archive)
- [Videos](#videos)

## Home Page

Subscribe

Subscribe with email `input` and `button`.

Links to:
- Composability Summit
- JavaScript Jam Live
- JavaScript Jam Podcast

Explore:
- JavaScript Jam Live Archive
- Newsletter Archives

Latest Articles:

- Figure out later!!!

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>JavaScript Jam</title>
    <meta
      name="description"
      content="The podcast, newsletter, and community for frontend and full-stack developers. Presented by Edgio."
    />
  </head>

  <body>
    <div></div>
    <div></div>
    <section></section>
    <div></div>
  </body>
</html>
```

### Navigation Bar

```html
<body>
  <div>
    <nav>
      <div>
        <a aria-label="logo" href="https://www.javascriptjam.com">
          <img src="https://javascriptjam.com/content/images/2023/02/Group-13.png">
        </a>
      </div>

      <div>
        <div>
          <span>Hamburger SVG</span>
          <ul>
            <li>
              <a href="https://www.javascriptjam.com/">Home</a>
            </li>
            <li>
              <a href="https://www.javascriptjam.com/about/">About</a>
            </li>
            <li>
              <a href="https://www.javascriptjam.com/composability-summit/">Composability Summit</a>
            </li>
            <li>
              <a href="https://www.javascriptjam.com/newsletter/">Newsletter Archive</a>
            </li>
            <li>
              <a href="https://www.javascriptjam.com/videos/">Videos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</body>
```

### Main Content

```html
<body>
  <div>
    <div>
      <div>
        <div>
          <h1>JavaScript Jam</h1>
          <h5>The podcast and community for frontend and full-stack developers.</h5>
          <p>Join a thriving community of developers creating their stack from digital building blocks.</p>
          <p>Subscribe now to receive full access to Composability Summit 2022.</p>
        </div>

        <div>
          <form>
            <div>
              <div>
                <input type="email" required="true" placeholder="Email address">
                <button type="submit">
                  <span>Subscribe</span><span>Submitting...</span>
                </button>
              </div>
              <p></p>
            </div>

            <div>
              <p><b>Thank you for subscribing!</b></p>
              <p>Please check your inbox for a link to confirm your email address.</p>
            </div>
          </form>
        </div>
      </div>

      <div>YouTube Embed</div>
    </div>
    <div>
      <a href="/composability-summit/">
        <div>🧱</div>
        <h2>Composability Summit</h2>
        <p>Get access to all summit content including 25+ Speakers.</p>
      </a>
      <a href="/javascript-jam-live/">
        <div>🎙️</div>
        <h2>JavaScript Jam Live on Twitter Spaces</h2>
        <p>View the archive of our live QA, open mic, and industry interviews.</p>
      </a>
      <a href="/podcast/">
        <div>🎧</div>
        <h2>JavaScript Jam Video Podcast</h2>
        <p>A podcast for frontend and full-stack developers.</p>
      </a>
    </div>

    <div>
      <div>
        <h2>Explore</h2>

        <hr>

        <a href="/javascript-jam-live">
          <div>🗄️</div>
          <div>
            <b>JavaScript Jam Live Archive</b>
            <div>Browse all of the previous live sessions.</div>
          </div>
        </a>
        <a href="/newsletter/">
          <div>📰</div>
          <div>
            <b>Newsletter Archives </b>
            <div>Read the archives and subscribe here.</div>
          </div>
        </a>
      </div>

      <div>
        <h2>Latest Articles</h2>
        <hr>
        <div>
          <div>
            <div></div>
            <a href="">Title</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>
```

### Subscribe Button

```html
<body>
  <section>
    <div>
      <div>
        <h2>&#128140; Subscribe to JavaScript Jam</h2>
        <p>Join a growing community of developers. Every monday we share valuable insight, tips, and news surrounding JavaScript and modern web development. We are also live on Twitter Spaces every Wednesday at 12pm PST.</p>
      </div>

      <div>
        <form>
          <div>
            <input type="email" required="true" placeholder="Email address">
            <button type="submit">
              <span>Subscribe</span><span>Submitting...</span>
            </button>
            <p></p>
          </div>
          <div>
            <p><b>Thank you for subscribing!</b></p>
            <p>Please check your inbox for a link to confirm your email address.</p>
          </div>
        </form>
      </div>
    </div>
  </section>
</body>
```

### Footer

```html
<body>
  <div>
    <div>
      <div>
        <div>&copy; JavaScript Jam 2023.</div>
      </div>

      <div>
        <ul>
          <li>
            <a href="https://twitter.com/@javascriptjam">Twitter SVG</a>
          </li>
          <li>
            <a href="https://www.youtube.com/channel/UCoOajN1o9uLi1sEHoTpIbUg">YouTube SVG</a>
          </li>
          <li>
            <a href="/rss/">RSS SVG</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</body>
```

## About

### About this site

JavaScript Jam is an online publication launched by the Community Growth team at Edgio. If you subscribe today, you'll get full access to the website as well as email newsletters about new content when it's available. Your subscription makes this site possible, and allows JavaScript Jam to continue to exist. Thank you!

### Fresh content, delivered

Stay up to date with new content sent straight to your inbox! No more worrying about whether you missed something because of a pesky algorithm or news feed.

### Meet people like you

Join a community of other subscribers who share the same interests.

## Composability Summit

### If you Build & Deploy, you’ll love Composability

On July 27th – 29th, 2022 we held the Composability Summit and it was a grand success. View talks from over 25 speakers

### All posts by date

Component with Composability Summit episodes.

```

```

## Newsletter Archive

### The podcast & community for frontend and full-stack developers

A weekly summary of the best and most important articles, podcasts, and videos about JavaScript, web development, and performance.

Subscribe button.

Component hitting YouTube API to fetch episodes from YouTube account:

```

```

### Read past issues

Component with Newsletter articles.

```

```

## Videos

### The show for frontend and full-stack developers
