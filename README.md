# 2020 Spring "Advanced fMRI analysis 2" at SKKU GBME (graduate course)


<br>

- Lecturer: Choong-Wan Woo, Ph.D. Assistant professor (GBME).
- Office: N-center, 86335
- Web: [Cocoan lab](http://cocoanlab.github.io)
- E-mail: waniwoo@skku.edu
- Class: Fri 12:00-2:45PM (the location will be announced later)
- Office hours: Fri 15:00-16:00, you can book a time in advance through [https://choongwanwoo.youcanbook.me](https://choongwanwoo.youcanbook.me)

<br>

## Download
You can download the class materials using the following command line:

	$ git clone https://github.com/wanirepo/advancedfmrianalysis_2019fall

Once you clone the github repository, you can just type the following command to get the updated github repository:

	$ git pull
	
Or you can download the repository as a zip file or you can also use [GitHub Desktop](https://desktop.github.com). The class materials will be uploaded (e.g., lecture slides, assignments) before each class. 

There is a good github tutorial: [https://rogerdudler.github.io/git-guide/index.html](https://rogerdudler.github.io/git-guide/index.html)

## What are the aims of this course?

The functional neuroimaging, esp. functional Magnetic Resonance Imaging (fMRI), has revolutionalized how we study human brain functions, human cognition, and behaviors. It enables us to study fine-grained neural dynamics and representations that give rise to adaptive human behaviors and cognitions. The powerful imaging methods and neuroimaging data had called for better analysis methods and approaches, and thanks to recent advances in statistical and computational methods (including machine learning), more researchers are developing and applying more advanced analysis methods to neuroimaging data. However, using more advanced methods itself does not make the study better automatically, and sometimes advanced methods make research worse by sacrificing the interpretability, robustness, and reproducibility of the research findings. These advanced methods should be used very carefully with a critical mind to actually help make research better. 

The idea of opening this class began with the 2019 OHBM meeting, where I saw a lot of advanced new analysis methods that I wasn't aware of, meaning that the field is rapidly changing (in terms of the analysis methodology), and we need to put efforts to know what kinds of analysis methods are being developed and used. We need to analyze them with critical eyes to know strengths and weaknesses of these new methods. Otherwise, we will stuck! Using them is one thing, but more importantly, we need to know the methods to understand the science behind the technology better and to know where the field is heading.  

Let's do this process together! I believe in a collective intelligence, and through the class, I hope we can do it together. 


## Course format and expectations

This class uses the flipped classroom format, which means that you will study the content in advance by watching video lectures related to the topic each week. We might not have video lectures for some weeks, and in that case, you will read one or two papers. 

We will make a list of the analysis methods we want to cover in the first class, and each student will be assigned to one method. The leader student should provide: 1) key papers that used the methods, 2) video lecture links (if available), 3) presentation in the class (focused on the method), 4) example data and codes (these will be uploaded to our class github repository). 

Before the class, all students are required to read each week's key papers and watch the video lectures (if there is any). In the class, the leader student has to give a presentation first, and also provides a hands-on experience.


## Evaluation

This class will use the absolute evaluation.

1. Attendance (30%)
2. Presentation/hands-on (40%)
5. Participation (30%)


## Schedule

Week  | Topic | Video lecture | Reading | Codes 
------| ----- | ----- | ----- | -------
Week 1 (3/13) | Class overview | 
Week 2 (3/20) | TBD | | | |
Week 3 (3/27) | TBD | | | |
Week 4 (4/3) | TBD | | | |
Week 5 (4/10) | TBD | | | |
Week 6 (4/17) | TBD | | | |
Week 7 (4/24) | TBD | | | |
Week 8 (5/1) | Mid-term | | | |
Week 9 (5/8) | TBD | | | |
Week 10 (5/15) | No class (conference) | | | |
Week 11 (5/22) | TBD | | | |
Week 12 (5/29) | TBD | | | |
Week 13 (6/5) | TBD | | | |
Week 14 (6/12) | TBD | | | |
Week 15 (6/19) | Final | | | |

_Note._ Weekly plan described above can be adjusted as our class develops.

## Potential topics

We have 11 weeks!

- Non-linear dimension reduction methods (e.g., [UMAP](https://www.biorxiv.org/content/biorxiv/early/2018/09/06/409987.full.pdf), isomap, t-sne etc.)
- Linear dimension reduction methods (e.g., Non-negative matrix factorization)
- Shared response model 
- Activity flow over resting-state networks (Michael Cole lab [link](http://www.colelab.org/)) 
- NLP or Topic modeling
- Different methods in network analysis (e.g., [multilayer community detection](https://www.pnas.org/content/112/37/11678))
- Multivariate pattern dependence ([Anzellotti et al., 2017](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005799))
- Distance correlation and representational connectivity analysis ([Geerlings et al., 2016](https://www.ncbi.nlm.nih.gov/pubmed/27114055) and [Nili et al., 2014](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003553))
- Temporal communities by trajectory clustering ([Thompson1 et al., 2019](https://www.biorxiv.org/content/10.1101/617027v1.abstract))
- Deep transfer learning [link](https://arxiv.org/pdf/1907.01953.pdf)
- Introducing neuroimaging analysis platforms: [Neuroscout](https://alpha.neuroscout.org/), [fMRIprep](https://fmriprep.readthedocs.io/en/stable/), [MRIQC](https://mriqc.readthedocs.io/en/stable/), [fMRIDenoise](https://github.com/nbraingroup/fmridenoise), [Neurolearn](http://neuro-learn.org/)
- Stepwise connectivity combined with gradient mapping ([Hong et al., 2019](https://www.nature.com/articles/s41467-019-08944-1))
- Personalized parcellation methods (Glasser's 2016 Nature, Gordon's 2017 Neuron, Cole lab [CAB-NP](https://github.com/ColeLab/ColeAnticevicNetPartition), CIFTIFY, etc.)
- Introducing multiple parcellations (using atlas_obj in canlab tools; e.g., SPM anatomy toolbox, SUIT, Yeo group, Constable group, Brainnetome, etc.)
- Surface analysis pipeline
- DTI analysis
- Data visualization

and more

(Covered topics)
- Representational similarity analysis [tutorial](https://github.com/cocoanlab/khbm2019_RSA_tutorial)
- Interpreting machine learning models [tutorial](https://github.com/cocoanlab/interpret_ml_neuroimaging)
- Gradient mapping ([Hong et al. 2019](https://www.nature.com/articles/s41467-019-08944-1))
- Inter-subject FC (ISFC) [Nastase et al., 2019](https://www.biorxiv.org/content/10.1101/741975v1)
- Hyperalignment [Manning's Hypertools](https://hypertools.readthedocs.io/en/latest/) 
- Hidden Markov Model
- ICA/PCA
- Nipype and fMRIprep
- Basics of network analysis


#### See some existing awesome tutorials

- [MIND2017](https://mindsummerschool.org/2017/08/13/multiscale-network-dynamics.html)
- [MIND2018](https://mindsummerschool.org/2018/07/30/narratives-and-naturalistic-contexts.html)
- [Neurohackademy2018](https://www.youtube.com/playlist?list=PLO3l0PnUGHYEqA7rFQT2jM6jxsaC2XiHh)
- [Neurohackademy2019](https://www.youtube.com/results?search_query=NeuroHackademy+2019)
- [Mumfordbrainstats](https://www.youtube.com/channel/UCZ7gF0zm35FwrFpDND6DWeA)

## Full references

TBA

<!--### Week 3

Kriegeskorte, N., Mur, M., & Bandettini, P. (2008). Representational similarity analysis - connecting the branches of systems neuroscience. Frontiers in Systems Neuroscience, 2(November), 4.

Nili, H., Wingfield, C., Walther, A., Su, L., Marslen-Wilson, W., & Kriegeskorte, N. (2014). A Toolbox for Representational Similarity Analysis. PLoS Computational Biology, 10(4), e1003553.

### Week 4

Kohoutová, L., Heo, J., Cha, S., Moon, T., Lee, S., Wager, T. D., & Woo, C. -W. (under review) Interpreting machine learning models in neuroimaging: Towards a unified framework
-->
