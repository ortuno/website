TODO List
---

#### GENERAL RECOMMENDATIONS
- Before pushing any update in the website, please carefully review the use of English Language.
- For new points in this list, use this template:

```
- [ ] Activity Description.  _(CREATED: DayMonthYear; SORTED: DayMonthYear)_ (commit(s): []() )
```

# TODO LIST

- [ ] Create a post in the blog site about the use of GitHub:
[Source1](https://github.com/oliviaguest/neuroplausible/blob/master/_posts/2017-11-5-github.md),
[Source2](http://neuroplausible.com/github)
[Source3](https://simplystatistics.org/newposts/)
[Source4](https://github.com/mxochicale/usingGitHub)

- [ ] Collapse the biography of members using [js_collapse](https://www.w3schools.com/bootstrap/bootstrap_ref_js_collapse.asp)
 _(CREATED: 17Dec2017; SORTED: DayMonthYear)_ (commit(s): []() )

 using [post-submission](https://github.com/ML4MX/blogpost-submission) template.
  _(CREATED: 29November2017; SORTED: )_ (commit(s): []() )

- [ ] Add demo projects to the website using [projects-submission](https://github.com/ML4MX/project-submission)
template
_(CREATED: 29November2017; SORTED: )_ (commit(s): []() )


- [ ] Create either a google form or a new repository for the section of
[JOIN US](https://ml4mx.github.io/website/index.html#)
_(CREATED: 4December2017; SORTED: DayMonthYear)_ (commit(s): []() )


- [ ] Organise [RELEASES](https://github.com/ML4MX/website/blob/master/docs/RELEASES.md) of the website as [atom does](https://github.com/atom/atom/releases)
  _(CREATED: 4december2017; SORTED: )_ (commit(s): []() )

- [ ] Crate a logo for ML4MX. These are some [images references](https://github.com/ML4MX/website/tree/master/assets/images/logo). _(CREATED: 4 December 2017; SORTED: )_ (commit(s): []() )

- [ ] Set up a local site for testing and before push any updates.
[Source1](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/), [Source2](https://gist.github.com/jgravois/5e73b56fa7756fd00b89) _(CREATED: 4 December 2017; SORTED: )_ (commit(s): []() )

- [ ] Create a bilingual website. _(CREATED: October2017; SORTED: )_ (commit(s): []() )

- [ ] Create a twitter account with a username ML4MX.  The twitter account does not exist on _(CREATED: 29November2017; SORTED: )_ (commit(s): []() )



# SORTED LIST



- [x] The news tab is not working, make the same as in the blog.

For which, the
following
[solution](https://reachtarunhere.github.io/2016/01/06/multiple-blogs-on-single-jekyll-instance/)
was implemented. Specifically, news is considered as the secondary blog.
**RESULT** This posts all what is inside the path " posts", then this modification was added:

```
{% if news == 'news' %} at  <h2>BaseURL/News/index.html
.
.
.
{% endif %}
```

- [x] Have a blog and news posts in the website  [solution](https://stackoverflow.com/questions/14560687/multiple-blogs-in-single-jekyll-website/42196173#42196173). _(CREATED: 1November2017; SORTED: _29November2017_ )_ (commit(s): []() )


- [x] Create a gmail account so as to have a contact email for anyone who might be
interested in Machine Learning for Mexico. Can anyone help with this one?

   _contact.ML4MX@gmail.com_ (https://github.com/ekhar666) on _(CREATED: 18November2017; SORTED:18November2017 )_ (commit(s): [c](https://github.com/ML4MX/website/commit/9d9b21aec782b3a3f27d39402060c0c77ac8ccd0#diff-e02f7b5eb279990ed19ab57010bb36f6) )

- [x] Create path for project posts.  _(CREATED: 30November2017; SORTED: 4December2017 )_

- [x] Create a release or version list for the website. [RELEASES](https://github.com/ML4MX/website/blob/master/docs/RELEASES.md)
  _(CREATED: 30November2017; SORTED:4december2017 )_ (commit: [b6a4df4](https://github.com/ML4MX/website/commit/b6a4df40a32abeb2da85812270d474d532533169) )

- [x] Use the same size figures on the Mission, Vision and Objects and update the images
using more colourful and representative images.  _(CREATED: 30November2017; SORTED: )_ (commit(s): [b6a4df4](https://github.com/ML4MX/website/commit/b6a4df40a32abeb2da85812270d474d532533169) )


- [x] Incorporate the format of[ [members in ReScience] ](https://rescience.github.io/board/)
for the members of ML4MX as used in
_(CREATED: 29November2017; SORTED: )_ (commit(s): [059943b](https://github.com/ML4MX/website/commit/059943b3c8d139915dff8153efd1ba28bdb55028) )

- [x] Update areas of research and programming language experiences in profiles of the members. _(CREATED: DayMonthYear; SORTED: 17Dec2017)_ (commit(s): []() )



# EXTRA LIST

- [ ] Following the [White Papers](http://hamlyn.doc.ic.ac.uk/uk-ras/white-papers),
it is suggested to create white papers for different projects of the use of Machine
Learning in Mexico. The following references present some examples of the applications of Machine Learning which can be incorporated in the white papers.
- [What is the potential of machine learning over the next 5-10 years? And how can we develop this technology in a way that benefits everyone?](https://royalsociety.org/topics-policy/projects/machine-learning/). *  [source](https://twitter.com/royalsociety/status/858395767941328897)
- [Machine Learning for Healthcare](http://mucmd.org/)
- [Machine Learning for Healthcare and Life Sciences](https://www.research.ibm.com/haifa/dept/vst/mldm.shtml)
- [8 Ways Machine Learning Will Improve Education](http://www.gettingsmart.com/2015/11/8-ways-machine-learning-will-improve-education/)
- [Five levels of AI in public service](https://www.oxfordinsights.com/insights/2017/7/12/five-levels-of-ai-in-public-service)
- [Three Ways Machine Learning Will Disrupt Transportation](http://www.mccormick.northwestern.edu/news/articles/2016/10/three-ways-machine-learning-will-disrupt-transportation.html)
- [Machine-learning promises to shake up large swathes of finance](https://www.economist.com/news/finance-and-economics/21722685-fields-trading-credit-assessment-fraud-prevention-machine-learning)
- [Machine Learning in Finance – Present and Future Applications](https://www.techemergence.com/machine-learning-in-finance/)
- [the hottest machine learning startups in the UK](https://www.techworld.com/picture-gallery/startups/uk-ai-startups-watch-hottest-machine-learning-startups-in-uk-3645606/)
- [Open Data for Africa](http://dataportal.opendataforafrica.org/)
