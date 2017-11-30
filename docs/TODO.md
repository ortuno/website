TODO List
---


# CONTENT

- [ ] Create a post in the blog site about the use of GitHub [Source1](https://github.com/oliviaguest/neuroplausible/blob/master/_posts/2017-11-5-github.md),
[Source2](http://neuroplausible.com/github)
 using [post-submission](https://github.com/ML4MX/blogpost-submission) template.
- [ ] Add demo projects to the website using [projects-submission](https://github.com/ML4MX/project-submission)
template
- [ ] Incorporate the format for the
members of ML4MX as used in [the members in ReScience](https://rescience.github.io/board/)
- [ ] Review the use of English Language in the website.

# WEBSITE
- [ ] Create a release or version list for the website.  _30November2017_
- [ ] Create path for project posts.  _30November2017_
- [ ] Use the same size figures on the Mission, Vision and Objects and update the images
using more colourful and representative images.  _30November2017_

- [ ] Create a bilingual webpage
- [ ] Create a twitter account with a username ML4MX.  The twitter account does not exist on _29November2017_


# EXTRA

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




# DONE



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
_29November2017_


- [x] THEN, with this [solution](https://stackoverflow.com/questions/14560687/multiple-blogs-in-single-jekyll-website/42196173#42196173),
the problem of having  blog and news posts in the website were solved.
_29November2017_


- [x] Create a gmail account so as to have a contact email for anyone who might be
interested in Machine Learning for Mexico. Can anyone help with this one?

   _contact.ML4MX@gmail.com_  [commit](https://github.com/ML4MX/website/commit/9d9b21aec782b3a3f27d39402060c0c77ac8ccd0#diff-e02f7b5eb279990ed19ab57010bb36f6) by [@ekhar666](https://github.com/ekhar666) on _18November2017_
