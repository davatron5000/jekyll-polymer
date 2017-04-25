# Jekyll + Polymer

Little confusing here, but using [Polymer 2.0](https://www.polymer-project.org/2.0/start/install-2-0) for Web Components and Jekyll to build and serve pages. Could be slightly redundant to something like `polymer serve` but hey, I wanted to play with Polymer in an existing workflow and simulate a full functioning client website.

```
gem install jekyll
npm install -g polymer-cli@next
npm install -g bower
bower install Polymer/polymer#^2.0.0-rc.7
jekyll serve
```