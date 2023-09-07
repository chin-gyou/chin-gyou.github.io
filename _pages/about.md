---
permalink: /
redirect_from: 
  - /about/
  - /about.html
---

I'm a machine learning scientist at Amazon Alexa AI leading the contextual question-answering project for shopping. I developed the full training pipeline of the system from scratch including pre-training, data collection/annotation and active/continuous learning. The developed shopping QA system has been applied over Amazon apps, webpages and Alexa devices serving hundreds of millions of users.

I obtained my PhD degree from Saarland University/Max Planck Institute for Informatics in Germany under the supervision of [Dietrich Klakow](https://scholar.google.de/citations?user=_HtGYmoAAAAJ) and [Gerhard Weikum](https://people.mpi-inf.mpg.de/~weikum/). My research focused on conversational AI, controllable text generation and deep latent variable models. The PhD thesis is available [here](https://publikationen.sulb.uni-saarland.de/bitstream/20.500.11880/32106/1/combinepdf.pdf). During my PhD phase, I also spent 1 year in Japan, working with Prof. [Akiki Aizawa](https://scholar.google.com/citations?user=JQy5hPoAAAAJ) from the university of Tokyo/NII, Prof. [Kentaro Inui](http://www.cl.ecei.tohoku.ac.jp/~inui/) and Prof. [Jun Suzuki](http://www.fai.cds.tohoku.ac.jp/members/js/) from Tohuku University/RIKEN AIP. Before that, i obtained my bachelor degree from Nanjing University.

News
======
- I will join [Eastern Institute of Technology](https://www.eias.ac.cn/?lang=en) as an assistant professor from November, 2023. We run joint collaborated Phd programs with Shanghai Jiaotong University, Hong Kong University of Science and Technology and The Hong Kong Polytechnic University. Students will be awarded with degrees from our collaborated universities. I'm constantly looking for talented students to join my lab as potential interns, PhDs or post docs. If you're interested, please [send me an email](mailto:isky1994@gmail.com).
- Our [paper](https://aclanthology.org/2023.acl-long.796.pdf) on weak supervision has won the special theme paper award at ACL 2023.
- Our [paper](https://aclanthology.org/2023.acl-industry.12.pdf) on cross-lingual product question answering has been accepted by the industry track of ACL 2023. The dataset xPQA has been released [here](https://github.com/amazon-science/contextual-product-qa/).

Research Interests
======
The recent rapid development of LLMs have shown that the model performance can be steadily improved as the growing model and data size. Moving forward, my mission to explore to which extend LLMs can lead us towards the goal and how my expertise could help reduce the gap. With this in mind, I plan on pushing forward in the following research areas:
- Interpretability and Explainability: From probabilistic answer generator to logical thinker
- Cross-lingual generalization: From English-centric to multilingual expert
- Domain Specialization: From general to domain expert

I believe that future LLMs show follow these three paths to become truly usable and reliable intelligent agents. My research statement can be found [here](../files/Research_statement.pdf).

Awards
======
- Special Theme Paper Award at ACL 2023
- Chinese government award for outstanding students abroad, 2020 
- Best Demo paper Award at COLING 2020
- Google NLP Summit Grant, 2019
- International Max Planck Research School Fellowship, 2017 
- Outstanding Graduate/Outstanding Bachelor Thesis of Nanjing University, 2015
- National Scholarship and Outstanding Student of Nanjing University, 2013

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
