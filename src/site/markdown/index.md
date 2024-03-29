<h2>About</h2>

Tyrus is the open source
<a href="http://java.net/projects/websocket-spec">JSR 356 - Java API for WebSocket</a>
reference implementation
for easy development of WebSocket applications. WebSocket protocol defined by IETF
provides bi-directional communication between the server and the remote host. The
pros are mainly the ability to communicate both ways, low latency and small
communication overhead. Therefore Tyrus and WebSocket in general are suitable for web
applications that require sending a huge volume of relatively small messages like
online games or market ticker broadcasting.

The <a href="http://glassfish.java.net/public/GovernancePolicy.html">governance policy</a>
 is the same as the one used in the GlassFish project. We also use the same two licenses -
 <a href="http://glassfish.java.net/public/CDDL+GPL_1_1.html">CDDL 1.1 and GPL 2 with CPE</a>
  - so, you can pick which one suites your needs better.

The latest stable release of Tyrus is [1.12][deps].

<h2>Recent articles</h2>

<a href='https://blogs.oracle.com/PavelBucek/entry/tyrus_1_10' class='article'><span class='title' title='Pavel Bucek'>Tyrus 1.10</span> <span class='date'>Feb 12, 2015</span>
<p>Tyrus 1.10 is a maintenance relase, so unfortunately no cool new features to highlight, but we were able to add some
new examples – Shared collection and BTC Xchange...</p>
</a>

<a href='https://blogs.oracle.com/PavelBucek/entry/is_websocket_session_really_thread' class='article'><span class='title' title='Pavel Bucek'>Is WebSocket Session really thread safe?</span> <span class='date'>Feb 9, 2015</span>
<p>Todays article would be about one simple use-case of JSR-356: Java API for WebSocket. This was brought to my attention
by Mark Thomas, who started relatively long thread on the jsr356-experts mailing list. The described problem can be simplified
to following code...</p>
</a>

<a href='https://blogs.oracle.com/PavelBucek/entry/reducing_websocket_client_jar_size' class='article'><span class='title' title='Pavel Bucek'>Reducing WebSocket client jar size with ProGuard</span> <span class='date'>Jan 14, 2015</span>
<p>We already know there is a demand for standalone web socket client runnable even on different platforms than just Java
EE or Java SE – Tyrus publishes client runtime all-in-one bundles for Java 6 (works on Android!) and Java 7+ (takes advantage
of NIO API introduced in Java 7)...</p>
</a>

<p><a href="https://blogs.oracle.com/main/tags/tyrus">Older articles...</a></p>

---

<h2><a href="documentation/1.12/index/getting-started.html" class="headerlink"><img src="images/compass.png"/> Get Started</a></h2>

[Learn][quick] how to use Tyrus in your projects.


<h2><a href="documentation/1.12/user-guide.html" class="headerlink"><img src="images/docs.png"/> Documentation</a></h2>

[Read][full] Tyrus user guide.


<h2><a href="dependencies.html" class="headerlink"><img src="images/download.png"/> Download</a></h2>

Tyrus is distributed mainly via Maven and it offers some extra modules.
See our list of [dependencies][deps] for details.


<h2><a href="related.html" class="headerlink"><img src="images/connect.png"/> Related Projects</a></h2>

List of projects related to Tyrus.


<h2><a href="contribute.html" class="headerlink"><img src="images/settings.png"/> Contribute</a></h2>

[Learn][contpage] how you can contribute to the project.


## ![Blogs][blog] Developer Blogs
* Pavel\'s [blog][pavel]

[contpage]: contribute.html
[quick]: documentation/1.12/index/getting-started.html
[deps]: dependencies.html
[full]: documentation/1.12/user-guide.html

[pavel]: https://blogs.oracle.com/PavelBucek

[started]: images/compass.png
[download]: images/download.png
[contribute]: images/settings.png
[docs]: images/docs.png
[blog]: images/blog2.png
