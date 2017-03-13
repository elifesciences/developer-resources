**Inside eLife: Resources for developers**

eLife is an initiative that aims to help scientists accelerate discovery by operating a platform for research communication that encourages and recognises the most responsible behaviours in science. eLife, the online open-access journal for life sciences and biomedical research, was the first step in this mission.

We invest heavily in software development so that the potential for improvements in the digital communication of new research can start to be realised. Our products are available open-source with permissive licensing to enable others to adopt, use and build on the work we do to accelerate discovery and transform research communication. 

Developers can find out more about each of our products, and how they can reuse them, here. We welcome feedback on our resources by email to [innovation@elifesciences.org](mailto:innovation@elifesciences.org).

**eLife API**

Scientific manuscripts that have been accepted following peer review are published online as articles available both in HTML and PDF format. All articles published with eLife are open-access and licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/). eLife content can be accessed, searched and reused via our public API. The RAML specification is at [https://github.com/elifesciences/api-raml](https://github.com/elifesciences/api-raml).

Of particular use for searching the complete body of work published with eLife, or corpus, are:
```
curl -v [https://prod--gateway.elifesciences.org/articles](https://prod--gateway.elifesciences.org/articles)

curl -v [https://prod--gateway.elifesciences.org/search?for=cell](https://prod--gateway.elifesciences.org/search?for=cell)
```
**eLife corpus**

The full corpus is also available to download in XML and JSON from github:

[https://github.com/elifesciences/elife-article-xml](https://github.com/elifesciences/elife-article-xml) 

[https://github.com/elifesciences/elife-article-json](https://github.com/elifesciences/elife-article-json) 

The size of the corpus grows daily. For an up-to-date estimation of the download size for each of the above, please refer to the size attribute via the Github API here: [https://api.github.com/repos/elifesciences/elife-article-](https://api.github.com/repos/elifesciences/elife-article-json)xml [https://api.github.com/repos/elifesciences/elife-article-json](https://api.github.com/repos/elifesciences/elife-article-json…)

We occasionally update a number of articles in addition to appending new ones, so the corpus may be refreshed as well as expanded.

**eLife Lens**

Lens provides a novel way of looking at content on the web. It is designed to make life easier for researchers, reviewers, authors and readers. Lens is a stand-alone web component that can be embedded into any web page. The code for Lens is open-source and available under the BSD-2-Clause license. Learn more at [https://elifesciences.org/elife-news/elife-sciences-introduces-elife-lens](https://elifesciences.org/elife-news/elife-sciences-introduces-elife-lens).

Documentation: [https://github.com/elifesciences/lens](https://github.com/elifesciences/lens) 

Try it out: [http://lens.elifesciences.org/](http://lens.elifesciences.org/)

**eLife Continuum**

eLife Continuum is the platform that we use to manage the publishing and hosting of our research content. It is composed of a set of software components that form a publishing and article-hosting system. Continuum has been made available for any interested party to use, to encourage the adoption of open, online and continuous publishing. The platform can be used in its entirety, or users can exploit its individual components within their own platform. The code for eLife Continuum is open-source and available under the MIT license. To find out more, see the comprehensive documentation at [https://github.com/elifesciences/elife-continuum-documentation](https://github.com/elifesciences/elife-continuum-documentation), which includes links to the code. Explore further at [https://elifesciences.org/elife-news/materials-publishers-elife-continuum](https://elifesciences.org/elife-news/materials-publishers-elife-continuum).

**Other resources**

For developers building on eLife resources using PHP, our software development kit may be useful: [https://github.com/elifesciences/api-sdk-php](https://github.com/elifesciences/api-sdk-php)




