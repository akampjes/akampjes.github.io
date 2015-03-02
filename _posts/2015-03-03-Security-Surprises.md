---
layout: post
title: Security Surprises in your Favourite Framework
---

Only two days after my talk at [Ruby and Rails Melbourne](/Railsec-TLDR/) I gave a talk, in tandium with Mike Haworth at [Auckland OWASP day](https://www.owasp.org/index.php/OWASP_New_Zealand_Day_2015) conference. The talk is based on the premise that we rely on our web development frameworks provide security by default and we find it suprising when we have security holes that our framework didn't prevent for us.

<script async class="speakerdeck-embed" data-id="cf7763a163fd4674aea628aa172be641" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>

Much to myself and Mike's amusement, the day after the conference, [Egor Homakov](https://twitter.com/homakov) found a [few vulnerabilities](http://sakurity.com/blog/2015/02/28/openuri.html) in ruby's OpenURI combining a few of the things that we talked about in this very talk.

We didn't add heaps references within the talk slides so if you have any questions I'd be glad to answer them.
