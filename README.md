# docker-ejre

### About

This project create docker images for Oracle Java SE Embedded 8u51.

All image are based on Busybox with 32 bits (and 64 bits) libs (see docker-busybox-lib32).

ejdk is the unzip version of ejdk-8u51-linux-i586.tar.gz available (with login) on [Oracle](http://www.oracle.com/technetwork/java/embedded/embedded-se/downloads/index.html)

Create a docker image for each profile (see Compact Profiles [JEP 161](http://openjdk.java.net/jeps/161) ) :
  - ofayau/ejre:8-compact1
  - ofayau/ejre:8-compact2
  - ofayau/ejre:8-compact3
  - ofayau/ejre:8-jre

### About size

```shell
REPOSITORY                   TAG                 IMAGE ID            CREATED             VIRTUAL SIZE
ofayau/ejre                  8-compact1          824a6f1a0ade        4 minutes ago       39.31 MB
ofayau/ejre                  8-compact3          a9fbe6b90034        4 minutes ago       48.79 MB
ofayau/openjdk-compact       8-compact1          ca87cefd33e5        27 hours ago        47.08 MB
ofayau/openjdk-compact       jre                 d57e311758e2        29 hours ago        66.38 MB
ofayau/j2me                  latest              f56c31b1cc20        26 hours ago        21.73 MB
```

### Welcome to GitHub Pages.
This automatic page generator is the easiest way to create beautiful pages for all of your projects. Author your page content here [using GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/), select a template crafted by a designer, and publish. After your page is generated, you can check out the new `gh-pages` branch locally. If you’re using GitHub for Mac or GitHub for Windows, simply sync your repository and you’ll see the new branch.

### Designer Templates
We’ve crafted some handsome templates for you to use. Go ahead and click 'Continue to layouts' to browse through them. You can easily go back to edit your page before publishing. After publishing your page, you can revisit the page generator and switch to another theme. Your Page content will be preserved.

### Creating pages manually
If you prefer to not use the automatic generator, push a branch named `gh-pages` to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.

### Authors and Contributors
You can @mention a GitHub username to generate a link to their profile. The resulting `<a>` element will link to the contributor’s GitHub Profile. For example: In 2007, Chris Wanstrath (@defunkt), PJ Hyett (@pjhyett), and Tom Preston-Werner (@mojombo) founded GitHub.

### Support or Contact
Having trouble with Pages? Check out our [documentation](https://help.github.com/pages) or [contact support](https://github.com/contact) and we’ll help you sort it out.

