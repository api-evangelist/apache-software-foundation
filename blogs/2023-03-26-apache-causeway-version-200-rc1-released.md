---
title: "Apache Causeway version 2.0.0-RC1 Released"
url: "/isis/entry/apache-causeway-version-2-0"
date: "2023-03-26T18:36:22+00:00"
author: ""
feed_url: "https://blogsarchive.apache.org/feed.xml"
---
<p>T<span style="color: rgb(34, 34, 34); font-family: Arial, Helvetica, sans-serif; font-size: small;">he Apache Causeway team is pleased to announce the release of Apache Causeway 2.0.0-RC1.</span></p>
<p><br style="color: rgb(34, 34, 34); font-family: Arial, Helvetica, sans-serif; font-size: small;" /><span style="color: rgb(34, 34, 34); font-family: Arial, Helvetica, sans-serif; font-size: small;">The main highlight is the change of name (to the new name 'causeway', from the old name 'isis'), which means that all Maven artifacts as well as package names have changed.&nbsp; The migration notes [1] explain how to update your code; if you need assistance then reach out through the mailing list [2] or our slack channel [3] because we can explain how to tackle change in stages.</span>
<div style="color: rgb(34, 34, 34); font-family: Arial, Helvetica, sans-serif; font-size: small;"><br />
<div>In addition, there are a small number of new features in this release, as well as numerous improvements and bug fixes.&nbsp; The new features include:<br /><br />* a new PageRenderSubscriber SPI provides callbacks to track the time taken to render a page (CAUSEWAY-3373)</div>
<div>* a new service to generate HTML documentation based on the domain model (CAUSEWAY-3328)<br /></div>
<div>
<div>* the simplification of the view model lifecycle by allowing injected dependencies to be specified as constructor parameters (CAUSEWAY-3293)<br /></div>
<div>* a new BackgroundService that allows actions to be executed via a Quartz job (CAUSEWAY-3267)</div>
<div>* allowing SAFE semantics actions to be invoked with only VIEWING permission (CAUSEWAY-3358)</div>
<p><br />Full release notes are available on the Apache Causeway website at [4].<br /><br />You can access this release directly from the Maven central repo [5].<br />Alternatively, download the release and build it from source [6].<br /><br />Enjoy!<br /><br />--The Apache Causeway team<br /><br />[1]&nbsp;<a href="https://causeway.apache.org/relnotes/2.0.0-RC1/2023/2.0.0-RC1/mignotes.html" style="color: rgb(17, 85, 204);" target="_blank">https://causeway.apache.org/relnotes/2.0.0-RC1/2023/2.0.0-RC1/mignotes.html</a></div>
<div>[2]&nbsp;<a href="https://causeway.apache.org/docs/2.0.0-RC1/support/mailing-list.html" style="color: rgb(17, 85, 204);" target="_blank">https://causeway.apache.org/docs/2.0.0-RC1/support/mailing-list.html</a></div>
<div>[3]&nbsp;<a href="https://causeway.apache.org/docs/2.0.0-RC1/support/slack-channel.html" style="color: rgb(17, 85, 204);" target="_blank">https://causeway.apache.org/docs/2.0.0-RC1/support/slack-channel.html</a></div>
<div>[4]&nbsp;<a href="https://causeway.apache.org/relnotes/2.0.0-RC1/about.html" style="color: rgb(17, 85, 204);" target="_blank">https://causeway.apache.org/relnotes/2.0.0-RC1/about.html</a><br />[5]&nbsp;<a href="https://search.maven.org/" style="color: rgb(17, 85, 204);" target="_blank">https://search.maven.org</a><br />[6]&nbsp;<a href="https://causeway.apache.org/docs/2.0.0-RC1/downloads/how-to.html" style="color: rgb(17, 85, 204);" target="_blank">https://causeway.apache.org/docs/2.0.0-RC1/downloads/how-to.html</a></div>
</div>
