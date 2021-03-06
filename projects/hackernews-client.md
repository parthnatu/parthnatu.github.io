---
layout: page
title: HackerNews Client
permalink: /projects/hacker-news-client
---

This started off with my introduction to [HackerNews](https://news.ycombinator.com/) and a need to create something tangible as a project.
Fresh out of my internship, I have certain degree of experience writing **`Java`**. It might not be the language that's "hip", but it runs the world. So this is what the project is:

**`hnfx - A JavaFX based cross-platform GUI client for HackerNews`**

I'm not sure what the structure of this page will be. I'm thinking of this like a scratchpad till the project reaches completion.

## Current status:
![image-title-here](/images/hacker-news-client/update-july-19-2019-screenshot.png){:class="img-responsive"}
-   19th July 2019 : 
    -   I am intrigued by asynchronously updating the ListView for the initial api call. Works well for now. I'll have to do some testing to make sure nothing is getting lost in the thread jungle.
    -   JavaFX's WebView engine is slow. Or it might be my internet connection. Not sure.
    -   I want to add Firefox as the engine. I'll try that.
    -   Watching my github commit grid show a dark green square makes me happy.
-   20th July 2019 : 
    -   Java 8's JavaFX WebView is [broken](https://bugs.openjdk.java.net/browse/JDK-8175802) as it cannot render modern fonts
    -   Will I need a JRE if I create an exe for Windows, dmg/pkg for Mac etc. ?
    -   I'll implement the data structure for showing the comment tree today
-   22nd July 2019 :
    -   Updated to Java 12. Fixed the WebView font rendering.
    -   I didn't need to create a data structure for the comment tree. Just created a separate method for populating the TreeView.
    -   I'm pretty sure I have screwed up the concurrency for the program. I need to understand and fix that.
    -   "based and redpilled". heh.
