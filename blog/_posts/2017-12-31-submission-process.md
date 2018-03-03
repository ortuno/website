---
title: Submission Process
layout: post
---

# Overview
Our goal for ML4MX is to increase the transparency and to improve the reproducibility
and openness of any project of Machine Learning for Mexico. With this in mind,
ML4MX has adopted the submission process for blog entries and projects of 
the peer-reviewed journal  [ReScience](https://rescience.github.io/write/).

Submitted entries are first considered by any of the [members](https://ml4mx.github.io/website/members.html) 
of the editorial board, who may decide to reject the submission (mainly because 
it has already been replicated and is publicly available), or assign it to 
two reviewers for further review and tests. The reviewers evaluate the code and 
the accompanying material in continuous interaction with the authors through 
the Pull Request discussion section. If both reviewers managed to run the code 
and obtain the same results as the ones advertised in the accompanying material,
the submission is accepted. If any of the two reviewers cannot replicate
the results before the deadline, the submission is rejected and authors
are encouraged to resubmit an improved version later. 

# Criteria for Publication
To be considered for publication in ML4MX, any given submission must satisfy the following criteria:
	* Replicability  
	* Rigorous methodology  
	* Original source code  
	* Substantial evidence for replication of the original results  

# Open Access

ML4MX applies the Creative Commons Attribution (CC BY) license to all works we publish. 
Under the CC BY license, authors retain ownership of the copyright for their article, 
but authors allow anyone to download, reuse, reprint, modify, distribute, and/or copy 
articles in ML4MX, so long as the original authors and source are cited. 
No permission is required from the authors or the publishers.

# How to submit?

1. Create a [github](https://github.com) account

2. [Fork](https://help.github.com/articles/fork-a-repo/) the [blogpost submission](https://github.com/ML4MX/blogpost-submission) repository

3. Clone this new repository into your desktop environment

   ```
   $ git clone https://github.com/YOUR-USERNAME/blogpost-submission
   ```

4. Create a branch (the branch name should be author names separated with dashes)

   ```
   $ git checkout -b AUTHOR1-AUTHOR2-...-AUTHORN-YEAR
   ```

5. Add your code & article (see [author guidelines](https://rescience.github.io/write)) and commit your changes:

   ```
   $ git commit -a -m "Some comment"
   ```

6. [Push](https://help.github.com/articles/pushing-to-a-remote/) to github

   ```
   $ git push origin AUTHOR1-AUTHOR2-...-AUTHORN-YEAR
   ```

7. Issue a [pull request](https://help.github.com/articles/using-pull-requests/) (PR) to
[blogpost-submission](https://github.com/ML4MX/blogpost-submission) (click on compare and pull request) and then
add the title containing author(s) name and follow the template that will appear once you opened the pull request:


  ```
  **AUTHOR**

  Dear Editors,

  I request a review for the following blog post:

  ### Original article

  **Title:**  
  **Author(s):**  
  **Keywords**:  
  **Repository**:  

  ### Potential reviewers
  <!-- If you know potential reviewers, you can tell us here -->
  <!-- You can look at http://rescience.github.io/board for the -->
  <!-- list of registered reviewers (but you can propose others) -->

  ---

  **EDITOR**

  * [ ] Editor acknowledgement ( [@githubusername](https://github.com/username) )
  * [ ] Reviewer 1 ([@githubusername](https://github.com/username) )
  * [ ] Reviewer 2 ([@githubusername](https://github.com/username) )
  * [ ] Review 1 decision [accept/reject]
  * [ ] Review 2 decision [accept/reject]
  * [ ] Editor decision [accept/reject]
  ```

8. You can suggest reviewers from [editorial board](https://ml4mx.github.io/website/members.html).

9. Answer questions and requests made in the Pull Request conversation page.

You can have a look at previous submissions at [ReScience-submission](https://github.com/ReScience/ReScience-submission/pulls)


# Preparation of the material
The structure of a submission is:

```
+ README.md
+ article
|  | author(s)-YEAR.md
|  | author(s)-YEAR.bib
|  | LICENSE.md (CC-BY 4.0)
|  | ...
|  + ...
+ code
|  | README.md
   | LICENSE.md (to be chosen)
|  | ...
|  + ...
+ data
|  | README.md
|  | LICENSE.md (CC 0)
|  | ...
|  + ...
+ notebook
   | README.md
   | LICENSE.md (to be chosen)
   |
   + ...
```

* A ```top README.md``` file that will be displayed when a reader enters your submission directory (once published)
* An ```author(s)-YEAR.md``` file that introduces the original paper, explains the technical details 
	of the replication and gives the evidence for the replication of the original results.
* A ```code``` directory that contains the commented code for the replication.
* A ```data``` directory that contains any data necessary to run the code.
* A ```notebook``` directory that may contain notebooks if relevant.
* Don’t forget to choose a license for the code repository. 
	You’re free to choose whatever open license you prefer (see 
	[the Debian Free Software Guidelines](https://www.debian.org/social_contract#guidelines)) 
	but you need to choose one.
* In the ```code/README.md``` and ```notebook/README.md``` files, include information on the platform 
	that was used to generate the results according to our [platform instructions](https://rescience.github.io/platform/).

# Rerences

[[1] ReScience: Overview of the submission process](https://rescience.github.io/write/)
