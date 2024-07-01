World model  Learning Resources
====================================

.. image:: https://img.shields.io/github/stars/Tony-Hou/world-model-resources.svg
   :target: https://github.com/Tony-Hou/world-model-resources/stargazers
   :alt: GitHub stars


.. image:: https://img.shields.io/github/forks/Tony-Hou/world-model-resources.svg?color=blue
   :target: https://github.com/Tony-Hou/world-model-resources/network
   :alt: GitHub forks


.. image:: https://img.shields.io/github/license/Tony-Hou/world-model-resources.svg?color=blue
   :target: https://github.com/Tony-Hou/world-model-resources/blob/master/LICENSE
   :alt: License


.. image:: https://awesome.re/badge-flat2.svg
   :target: https://awesome.re/badge-flat2.svg
   :alt: Awesome


.. image:: https://img.shields.io/badge/benchmark_results-pink
   :target: https://github.com/Minqi824/ADBench
   :alt: Benchmark


----

`World model <https://x.com/ylecun/status/1759933365241921817>`_
Lecun gave a very good definition. World model is an exciting yet challenging field,
which aims to make AI systems learn and reason like animals and humans. 


**This repository collects**:


#. Books & Academic Papers 
#. Online Courses and Videos
#. World model Datasets
#. Open-source and Commercial Libraries/Toolkits
#. Key Conferences & Journals


**More items will be added to the repository**.
Please feel free to suggest other key resources by opening an issue report,
submitting a pull request, or dropping me an email @ (hljzzu@gmail.com).
Enjoy reading!

BTW, you may find my `[GitHub] <https://github.com/Tony-Hou>`_ and
`[world model papers] <https://scholar.google.com/citations?user=WLN3QrAAAAAJ&hl=en>`_ useful
especially ` library <>`_ and ` benchmark <>`_.

----

Table of Contents
-----------------


* `1. Books & Tutorials & Benchmarks <#1-books--tutorials--benchmarks>`_

  * `1.1. Books <#11-books>`_
  * `1.2. Tutorials <#12-tutorials>`_
  * `1.3. Benchmarks <#13-benchmarks>`_

* `2. Courses/Seminars/Videos <#2-coursesseminarsvideos>`_
* `3. Toolbox & Datasets <#3-toolbox--datasets>`_

  * `3.1.  <#31>`_
  * `3.2. world  <#32->`_
  * `3.3. Datasets <#35-datasets>`_

* `4. Papers <#4-papers>`_

  * `4.1. Overview & Survey Papers <#41-overview--survey-papers>`_
  * `4.2. Key Algorithms <#42-key-algorithms>`_


* `5. Key Conferences/Workshops/Journals <#5-key-conferencesworkshopsjournals>`_

  * `5.1. Conferences & Workshops <#51-conferences--workshops>`_
  * `5.2. Journals <#52-journals>`_


----


1. Books & Tutorials & Benchmarks
---------------------------------

1.1. Books
^^^^^^^^^^

`World model <https://openreview.net/pdf?id=BZ5a1r-kVsf>`_ 
by Yann LeCun: 
A **must-read** for people in the field of world model. 



1.2. Tutorials
^^^^^^^^^^^^^^

===================================================== ============================================  =====  ============================  ==========================================================================================================================================================================
Tutorial Title                                        Venue                                         Year   Ref                           Materials
===================================================== ============================================  =====  ============================  ==========================================================================================================================================================================
Data mining for anomaly detection                     PKDD                                          2008   [#Lazarevic2008Data]_         `[Video] <http://videolectures.net/ecmlpkdd08_lazarevic_dmfa/>`_
Outlier detection techniques                          ACM SIGKDD                                    2010   [#Kriegel2010Outlier]_        `[PDF] 
===================================================== ============================================  =====  ============================  ==========================================================================================================================================================================


1.3. Benchmarks
^^^^^^^^^^^^^^^

**News**: We just released a 36-page, the most comprehensive `anomaly detection benchmark paper <https://www.andrew.cmu.edu/user/yuezhao2/papers/22-preprint-adbench.pdf>`_.
The fully `open-sourced ADBench <https://github.com/Minqi824/ADBench>`_ compares 30 anomaly detection algorithms on 55 benchmark datasets.


=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Data Types     Paper Title                                                                                        Venue                         Year   Ref                           Materials
=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Time-series    Revisiting Time Series Outlier Detection: Definitions and Benchmarks                               NeurIPS                       2021   [#Lai2021Revisiting]_         `[PDF] <https://openreview.net/pdf?id=r8IvOsnHchr>`_, `[Code] <https://github.com/datamllab/tods/tree/benchmark>`_

=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


----

2. Courses/Seminars/Videos
--------------------------

**Coursera Introduction to Anomaly Detection (by IBM)**\ :
`[See Video] <https://www.coursera.org/learn/ai/lecture/ASPv0/introduction-to-anomaly-detection>`_

**Get started with the Anomaly Detection API (by IBM)**\ :
`[See Website] <https://developer.ibm.com/learningpaths/get-started-anomaly-detection-api/>`_

**Practical Anomaly Detection by appliedAI Institute**\:
`[See Website] <https://transferlab.ai/trainings/practical-anomaly-detection/>`_, `[See Video] <https://www.youtube.com/watch?v=sEoMIDARpJ0&list=PLz6xKPm1Bnd6cDDgct3MDhNWJuPXzsmyW>`_, `[See GitHub] <https://github.com/aai-institute/tfl-training-practical-anomaly-detection>`_

**Coursera Real-Time Cyber Threat Detection and Mitigation partly covers the topic**\ :
`[See Video] <https://www.coursera.org/learn/real-time-cyber-threat-detection>`_

**Coursera Machine Learning by Andrew Ng also partly covers the topic**\ :


* `Anomaly Detection vs. Supervised Learning <https://www.coursera.org/learn/machine-learning/lecture/Rkc5x/anomaly-detection-vs-supervised-learning>`_
* `Developing and Evaluating an Anomaly Detection System <https://www.coursera.org/learn/machine-learning/lecture/Mwrni/developing-and-evaluating-an-anomaly-detection-system>`_

**Udemy Outlier Detection Algorithms in Data Mining and Data Science**\ :
`[See Video] <https://www.udemy.com/outlier-detection-techniques/>`_

**Stanford Data Mining for Cyber Security** also covers part of anomaly detection techniques\ :
`[See Video] <http://web.stanford.edu/class/cs259d/>`_

----

3. Toolbox & Datasets
---------------------

3.1. Multivariate Data
^^^^^^^^^^^^^^^^^^^^^^

[**Python**] `Python Outlier Detection (PyOD) <https://github.com/yzhao062/pyod>`_\ : PyOD is a comprehensive and scalable Python toolkit for detecting outlying objects in multivariate data. It contains more than 20 detection algorithms, including emerging deep learning models and outlier ensembles.

[**Python**, **GPU**] `TOD: Tensor-based Outlier Detection (PyTOD) <https://github.com/yzhao062/pytod>`_: A general GPU-accelerated framework for outlier detection.

[**Python**] `Python Streaming Anomaly Detection (PySAD) <https://github.com/selimfirat/pysad>`_\ : PySAD is a streaming anomaly detection framework in Python, which provides a complete set of tools for anomaly detection experiments. It currently contains more than 15 online anomaly detection algorithms and 2 different methods to integrate PyOD detectors to the streaming setting.

[**Python**] `Scikit-learn Novelty and Outlier Detection <http://scikit-learn.org/stable/modules/outlier_detection.html>`_. It supports some popular algorithms like LOF, Isolation Forest, and One-class SVM.

[**Python**] `Scalable Unsupervised Outlier Detection (SUOD) <https://github.com/yzhao062/suod>`_\ : SUOD (Scalable Unsupervised Outlier Detection) is an acceleration framework for large-scale unsupervised outlier detector training and prediction, on top of PyOD.

[**Julia**] `OutlierDetection.jl <https://github.com/OutlierDetectionJL/OutlierDetection.jl>`_\ : OutlierDetection.jl is a Julia toolkit for detecting outlying objects, also known as anomalies.

[**Java**] `ELKI: Environment for Developing KDD-Applications Supported by Index-Structures <https://elki-project.github.io/>`_\ :
ELKI is an open source (AGPLv3) data mining software written in Java. The focus of ELKI is research in algorithms, with an emphasis on unsupervised methods in cluster analysis and outlier detection. 

[**Java**] `RapidMiner Anomaly Detection Extension <https://github.com/Markus-Go/rapidminer-anomalydetection>`_\ : The Anomaly Detection Extension for RapidMiner comprises the most well know unsupervised anomaly detection algorithms, assigning individual anomaly scores to data rows of example sets. It allows you to find data, which is significantly different from the normal, without the need for the data being labeled.

[**R**] `CRAN Task View: Anomaly Detection with R <https://github.com/pridiltal/ctv-AnomalyDetection>`_\ : This CRAN task view contains a list of packages that can be used for anomaly detection with R.

[**R**] `outliers package <https://cran.r-project.org/web/packages/outliers/index.html>`_\ : A collection of some tests commonly used for identifying outliers in R.

[**Matlab**] `Anomaly Detection Toolbox - Beta <http://dsmi-lab-ntust.github.io/AnomalyDetectionToolbox/>`_\ : A collection of popular outlier detection algorithms in Matlab.


3.2. Time Series Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

[**Python**] `TODS <https://github.com/datamllab/tods>`_\ : TODS is a full-stack automated machine learning system for outlier detection on multivariate time-series data.

[**Python**] `skyline <https://github.com/earthgecko/skyline>`_\ : Skyline is a near real time anomaly detection system.

[**Python**] `banpei <https://github.com/tsurubee/banpei>`_\ : Banpei is a Python package of the anomaly detection.

[**Python**] `telemanom <https://github.com/khundman/telemanom>`_\ : A framework for using LSTMs to detect anomalies in multivariate time series data.

[**Python**] `DeepADoTS <https://github.com/KDD-OpenSource/DeepADoTS>`_\ : A benchmarking pipeline for anomaly detection on time series data for multiple state-of-the-art deep learning methods.

[**Python**] `NAB: The Numenta Anomaly Benchmark <https://github.com/numenta/NAB>`_\ : NAB is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications.

[**Python**] `CueObserve <https://github.com/cuebook/CueObserve>`_\ : Anomaly detection on SQL data warehouses and databases.

[**Python**] `Chaos Genius <https://github.com/chaos-genius/chaos_genius>`_\ : ML powered analytics engine for outlier/anomaly detection and root cause analysis.

[**R**] `CRAN Task View: Anomaly Detection with R <https://github.com/pridiltal/ctv-AnomalyDetection>`_\ : This CRAN task view contains a list of packages that can be used for anomaly detection with R.

[**R**] `AnomalyDetection <https://github.com/twitter/AnomalyDetection>`_\ : AnomalyDetection is an open-source R package to detect anomalies which is robust, from a statistical standpoint, in the presence of seasonality and an underlying trend.

[**R**] `anomalize <https://cran.r-project.org/web/packages/anomalize/>`_\ : The 'anomalize' package enables a "tidy" workflow for detecting anomalies in data.


3.3. Graph Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

[**Python**] `Python Graph Outlier Detection (PyGOD) <https://github.com/pygod-team/pygod/>`_\ : PyGOD is a Python library for graph outlier detection (anomaly detection). It includes more than 10 latest graph-based detection algorithms


3.4. Real-time Elasticsearch
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

[**Open Distro**] `Real Time Anomaly Detection in Open Distro for Elasticsearch by Amazon <https://github.com/aws/random-cut-forest-by-aws>`_\ : A machine learning-based anomaly detection plugins for Open Distro for Elasticsearch. See `Real Time Anomaly Detection in Open Distro for Elasticsearch <https://opendistro.github.io/for-elasticsearch/blog/odfe-updates/2019/11/real-time-anomaly-detection-in-open-distro-for-elasticsearch/>`_.

[**Python**] `datastream.io <https://github.com/MentatInnovations/datastream.io>`_\ : An open-source framework for real-time anomaly detection using Python, Elasticsearch and Kibana.


3.5. Datasets
^^^^^^^^^^^^^

**ELKI Outlier Datasets**\ : https://elki-project.github.io/datasets/outlier

**Outlier Detection DataSets (ODDS)**\ : http://odds.cs.stonybrook.edu/#table1

**Unsupervised Anomaly Detection Dataverse**\ : https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OPQMVF

**Anomaly Detection Meta-Analysis Benchmarks**\ : https://ir.library.oregonstate.edu/concern/datasets/47429f155

**Skoltech Anomaly Benchmark (SKAB)**\ : https://github.com/waico/skab


----


4. Papers
---------

4.1. Overview & Survey Papers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Papers are sorted by the publication year.

======================================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                                             Venue                         Year   Ref                           Materials
======================================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
A survey of outlier detection methodologies                                                                             ARTIF INTELL REV              2004   [#Hodge2004A]_                `[PDF] <https://www-users.cs.york.ac.uk/vicky/myPapers/Hodge+Austin_OutlierDetection_AIRE381.pdf>`_
Anomaly detection: A survey                                                                                             CSUR                          2009   [#Chandola2009Anomaly]_       `[PDF] <https://www.vs.inf.ethz.ch/edu/HS2011/CPS/papers/chandola09_anomaly-detection-survey.pdf>`_
A meta-analysis of the anomaly detection problem                                                                        Preprint                      2015   [#Emmott2015A]_               `[PDF] <https://arxiv.org/pdf/1503.01158.pdf>`_
On the evaluation of unsupervised outlier detection: measures, datasets, and an empirical study                         DMKD                          2016   [#Campos2016On]_              `[HTML] <https://link.springer.com/article/10.1007/s10618-015-0444-8>`_, `[SLIDES] <https://imada.sdu.dk/~zimek/InvitedTalks/TUVienna-2016-05-18-outlier-evaluation.pdf>`_
A comparative evaluation of unsupervised anomaly detection algorithms for multivariate data                             PLOS ONE                      2016   [#Goldstein2016A]_            `[PDF] <http://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0152173&type=printable>`_
A comparative evaluation of outlier detection algorithms: Experiments and analyses                                      Pattern Recognition           2018   [#Domingues2018A]_            `[PDF] <https://www.researchgate.net/publication/320025854_A_comparative_evaluation_of_outlier_detection_algorithms_Experiments_and_analyses>`_
Research Issues in Outlier Detection                                                                                    Book Chapter                  2019   [#Suri2019Research]_          `[HTML] <https://link.springer.com/chapter/10.1007/978-3-030-05127-3_3>`_
Quantitative comparison of unsupervised anomaly detection algorithms for intrusion detection                            SAC                           2019   [#Falcao2019Quantitative]_    `[HTML] <https://dl.acm.org/citation.cfm?id=3297314>`_
Progress in Outlier Detection Techniques: A Survey                                                                      IEEE Access                   2019   [#Wang2019Progress]_          `[PDF] <https://ieeexplore.ieee.org/iel7/6287639/8600701/08786096.pdf>`_
Deep learning for anomaly detection: A survey                                                                           Preprint                      2019   [#Chalapathy2019Deep]_        `[PDF] <https://arxiv.org/pdf/1901.03407.pdf>`_
Anomalous Instance Detection in Deep Learning: A Survey                                                                 Tech Report                   2020   [#Bulusu2020Deep]_            `[PDF] <https://arxiv.org/pdf/2003.06979.pdf>`_
Anomaly detection in univariate time-series: A survey on the state-of-the-art                                           Preprint                      2020   [#Braei2020Anomaly]_          `[PDF] <https://arxiv.org/pdf/2004.00433.pdf>`_
Deep Learning for Anomaly Detection: A Review                                                                           CSUR                          2021   [#Pang2020Deep]_              `[PDF] <https://arxiv.org/pdf/2007.02500.pdf>`_
A Comprehensive Survey on Graph Anomaly Detection with Deep Learning                                                    TKDE                          2021   [#Ma2021A]_                   `[PDF] <https://arxiv.org/pdf/2106.07178.pdf>`_
Revisiting Time Series Outlier Detection: Definitions and Benchmarks                                                    NeurIPS                       2021   [#Lai2021Revisiting]_         `[PDF] <https://openreview.net/pdf?id=r8IvOsnHchr>`_, `[Code] <https://github.com/datamllab/tods/tree/benchmark>`_
A Unified Survey on Anomaly, Novelty, Open-Set, and Out-of-Distribution Detection: Solutions and Future Challenges      Preprint                      2021   [#Salehi2021A]_               `[PDF] <https://arxiv.org/pdf/2110.14051.pdf>`_
Self-Supervised Anomaly Detection: A Survey and Outlook                                                                 Preprint                      2022   [#Hojjati2022Self]_           `[PDF] <https://arxiv.org/pdf/2205.05173.pdf>`_
Weakly supervised anomaly detection: A survey                                                                           Preprint                      2023   [#Jiang2023weakly]_           `[PDF] <https://arxiv.org/abs/2302.04549>`_, `[PDF] <https://github.com/yzhao062/wsad>`_
======================================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================

4.2. Key Algorithms
^^^^^^^^^^^^^^^^^^^

All these algorithms are available in `Python Outlier Detection (PyOD) <https://github.com/yzhao062/pyod>`_.

====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================
Abbreviation          Paper Title                                                                                        Venue                              Year   Ref                          Materials
====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================
kNN                   Efficient algorithms for mining outliers from large data sets                                      ACM SIGMOD Record                  2000   [#Ramaswamy2000Efficient]_   `[PDF] <https://webdocs.cs.ualberta.ca/~zaiane/pub/check/ramaswamy.pdf>`_
KNN                   Fast outlier detection in high dimensional spaces                                                  PKDD                               2002   [#Angiulli2002Fast]_         `[PDF] <https://www.researchgate.net/profile/Clara_Pizzuti/publication/220699183_Fast_Outlier_Detection_in_High_Dimensional_Spaces/links/542ea6a60cf27e39fa9635c6.pdf>`_
LOF                   LOF: identifying density-based local outliers                                                      ACM SIGMOD Record                  2000   [#Breunig2000LOF]_           `[PDF] <http://www.dbs.ifi.lmu.de/Publikationen/Papers/LOF.pdf>`_
IForest               Isolation forest                                                                                   ICDM                               2008   [#Liu2008Isolation]_         `[PDF] <https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf>`_
OCSVM                 Estimating the support of a high-dimensional distribution                                          Neural Computation                 2001   [#Scholkopf2001Estimating]_  `[PDF] <http://users.cecs.anu.edu.au/~williams/papers/P132.pdf>`_
AutoEncoder Ensemble  Outlier detection with autoencoder ensembles                                                       SDM                                2017   [#Chen2017Outlier]_          `[PDF] <http://saketsathe.net/downloads/autoencode.pdf>`_
COPOD                 COPOD: Copula-Based Outlier Detection                                                              ICDM                               2020   [#Li2020COPOD]_              `[PDF] <http://www.andrew.cmu.edu/user/yuezhao2/papers/20-icdm-copod.pdf>`_
ECOD                  Unsupervised Outlier Detection Using Empirical Cumulative Distribution Functions                   TKDE                               2022   [#Li2021ECOD]_               `[PDF] <https://www.andrew.cmu.edu/user/yuezhao2/papers/22-tkde-ecod.pdf>`_
====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================

4.3. Graph & Network Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  =============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                          Year   Ref                           Materials
=================================================================================================  =============================  =====  ============================  ==========================================================================================================================================================================
Graph based anomaly detection and description: a survey                                            DMKD                           2015   [#Akoglu2015Graph]_           `[PDF] <https://arxiv.org/pdf/1404.4679.pdf>`_
Anomaly detection in dynamic networks: a survey                                                    WIREs Computational Statistic  2015   [#Ranshous2015Anomaly]_       `[PDF] <https://onlinelibrary.wiley.com/doi/pdf/10.1002/wics.1347>`_
Outlier detection in graphs: On the impact of multiple graph models                                ComSIS                         2019   [#Campos2019Outlier]_         `[PDF] <http://www.comsis.org/pdf.php?id=wims-8671>`_
A Comprehensive Survey on Graph Anomaly Detection with Deep Learning                               TKDE                           2021   [#Ma2021A]_                   `[PDF] <https://arxiv.org/pdf/2106.07178.pdf>`_
=================================================================================================  =============================  =====  ============================  ==========================================================================================================================================================================


4.4. Time Series Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Outlier detection for temporal data: A survey                                                      TKDE                          2014   [#Gupta2014Outlier]_          `[PDF] <https://www.microsoft.com/en-us/research/wp-content/uploads/2014/01/gupta14_tkde.pdf>`_
Detecting spacecraft anomalies using lstms and nonparametric dynamic thresholding                  KDD                           2018   [#Hundman2018Detecting]_      `[PDF] <https://arxiv.org/pdf/1802.04431.pdf>`_, `[Code] <https://github.com/khundman/telemanom>`_
Time-Series Anomaly Detection Service at Microsoft                                                 KDD                           2019   [#Ren2019Time]_               `[PDF] <https://arxiv.org/pdf/1906.03821.pdf>`_
Revisiting Time Series Outlier Detection: Definitions and Benchmarks                               NeurIPS                       2021   [#Lai2021Revisiting]_         `[PDF] <https://openreview.net/pdf?id=r8IvOsnHchr>`_, `[Code] <https://github.com/datamllab/tods/tree/benchmark>`_
Graph-Augmented Normalizing Flows for Anomaly Detection of Multiple Time Series                    ICLR                          2022   [#Dai2022Graph]_               `[PDF] <https://openreview.net/pdf?id=45L_dgP48Vd>`_, `[Code] <https://github.com/EnyanDai/GANF>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.5. Feature Selection in Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

================================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                                       Venue                         Year   Ref                           Materials
================================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Unsupervised feature selection for outlier detection by modelling hierarchical value-feature couplings            ICDM                          2016   [#Pang2016Unsupervised]_      `[PDF] <https://opus.lib.uts.edu.au/bitstream/10453/107356/4/DSFS_ICDM2016.pdf>`_
Learning homophily couplings from non-iid data for joint feature selection and noise-resilient outlier detection  IJCAI                         2017   [#Pang2017Learning]_          `[PDF] <https://www.ijcai.org/proceedings/2017/0360.pdf>`_
================================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.6. High-dimensional & Subspace Outliers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

==================================================================================================  ============================  =====  ============================  =======================================================================================================================================================================================================
Paper Title                                                                                         Venue                         Year   Ref                           Materials
==================================================================================================  ============================  =====  ============================  =======================================================================================================================================================================================================
A survey on unsupervised outlier detection in high-dimensional numerical data                       Stat Anal Data Min            2012   [#Zimek2012A]_                `[HTML] <https://onlinelibrary.wiley.com/doi/abs/10.1002/sam.11161>`_
Learning Representations of Ultrahigh-dimensional Data for Random Distance-based Outlier Detection  SIGKDD                        2018   [#Pang2018Learning]_          `[PDF] <https://arxiv.org/pdf/1806.04808.pdf>`_
Reverse Nearest Neighbors in Unsupervised Distance-Based Outlier Detection                          TKDE                          2015   [#Radovanovic2015Reverse]_    `[PDF] <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.699.9559&rep=rep1&type=pdf>`_, `[SLIDES] <https://pdfs.semanticscholar.org/c8aa/832362422418287ff56793c780b425afa93f.pdf>`_
Outlier detection for high-dimensional data                                                         Biometrika                    2015   [#Ro2015Outlier]_             `[PDF] <http://web.hku.hk/~gyin/materials/2015RoZouWangYinBiometrika.pdf>`_
==================================================================================================  ============================  =====  ============================  =======================================================================================================================================================================================================


4.7. Outlier Ensembles
^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Outlier ensembles: position paper                                                                  SIGKDD Explorations           2013   [#Aggarwal2013Outlier]_       `[PDF] <https://pdfs.semanticscholar.org/841e/ce7c3812bbf799c99c84c064bbcf77916ba9.pdf>`_
Ensembles for unsupervised outlier detection: challenges and research questions a position paper   SIGKDD Explorations           2014   [#Zimek2014Ensembles]_        `[PDF] <http://www.kdd.org/exploration_files/V15-01-02-Zimek.pdf>`_
An Unsupervised Boosting Strategy for Outlier Detection Ensembles                                  PAKDD                         2018   [#Campos2018An]_              `[HTML] <https://link.springer.com/chapter/10.1007/978-3-319-93034-3_45>`_
LSCP: Locally selective combination in parallel outlier ensembles                                  SDM                           2019   [#Zhao2019LSCP]_              `[PDF] <https://epubs.siam.org/doi/pdf/10.1137/1.9781611975673.66>`_
Adaptive Model Pooling for Online Deep Anomaly Detection from a Complex Evolving Data Stream       KDD                           2022   [#Yoon2022ARCUS]_             `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3534678.3539348>`_, `[Github] <https://github.com/kaist-dmlab/ARCUS>`_, `[Slide] <https://drive.google.com/file/d/1JhrnEj1vScqGy69cfNUpfTjQYZh-vj_D/view>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================

4.8. Outlier Detection in Evolving Data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                         Venue                         Year   Ref                           Materials
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
A Survey on Anomaly detection in Evolving Data: [with Application to Forest Fire Risk Prediction]   SIGKDD Explorations           2018   [#Salehi2018A]_               `[PDF] <http://www.kdd.org/exploration_files/20-1-Article2.pdf>`_
Unsupervised real-time anomaly detection for streaming data                                         Neurocomputing                2017   [#Ahmad2017Unsupervised]_     `[PDF] <https://www.researchgate.net/publication/317325599_Unsupervised_real-time_anomaly_detection_for_streaming_data>`_
Outlier Detection in Feature-Evolving Data Streams                                                  SIGKDD                        2018   [#Manzoor2018Outlier]_        `[PDF] <https://www.andrew.cmu.edu/user/lakoglu/pubs/18-kdd-xstream.pdf>`_, `[Github] <https://cmuxstream.github.io/>`_
Evaluating Real-Time Anomaly Detection Algorithms--The Numenta Anomaly Benchmark                    ICMLA                         2015   [#Lavin2015Evaluating]_       `[PDF] <https://arxiv.org/pdf/1510.03336.pdf>`_, `[Github] <https://github.com/numenta/NAB>`_
MIDAS: Microcluster-Based Detector of Anomalies in Edge Streams                                     AAAI                          2020   [#Bhatia2020MIDAS]_           `[PDF] <https://www.comp.nus.edu.sg/~sbhatia/assets/pdf/midas.pdf>`_, `[Github] <https://github.com/bhatiasiddharth/MIDAS>`_
NETS: Extremely Fast Outlier Detection from a Data Stream via Set-Based Processing                  VLDB                          2019   [#Yoon2019NETS]_              `[PDF] <http://www.vldb.org/pvldb/vol12/p1303-yoon.pdf>`_, `[Github] <https://github.com/kaist-dmlab/NETS>`_, `[Slide] <https://drive.google.com/file/d/1wqKJZhEE4nTWe0zODu21ejgPDsDA_xaF/view?usp=sharing>`_
Ultrafast Local Outlier Detection from a Data Stream with Stationary Region Skipping                KDD                           2020   [#Yoon2020STARE]_             `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3394486.3403171>`_, `[Github] <https://github.com/kaist-dmlab/STARE>`_, `[Slide] <https://drive.google.com/file/d/11y7Gs703SKJBkPZ4nKKgua__dHXXMbkV/view?usp=sharing>`_
Multiple Dynamic Outlier-Detection from a Data Stream by Exploiting Duality of Data and Queries     SIGMOD                        2021   [#Yoon2021MDUAL]_             `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3448016.3452810>`_, `[Github] <https://github.com/kaist-dmlab/MDUAL>`_, `[Slide] <https://drive.google.com/file/d/1wmkkKCAcF9Dk8Wg49WnJF4U--lbtWy9J/view>`_
Adaptive Model Pooling for Online Deep Anomaly Detection from a Complex Evolving Data Stream        KDD                           2022   [#Yoon2022ARCUS]_             `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3534678.3539348>`_, `[Github] <https://github.com/kaist-dmlab/ARCUS>`_, `[Slide] <https://drive.google.com/file/d/1JhrnEj1vScqGy69cfNUpfTjQYZh-vj_D/view>`_
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.9. Representation Learning in Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                         Venue                         Year   Ref                           Materials
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Learning Representations of Ultrahigh-dimensional Data for Random Distance-based Outlier Detection  SIGKDD                        2018   [#Pang2018Learning]_          `[PDF] <https://arxiv.org/pdf/1806.04808.pdf>`_
Learning representations for outlier detection on a budget                                          Preprint                      2015   [#Micenkova2015Learning]_     `[PDF] <https://arxiv.org/pdf/1507.08104.pdf>`_
XGBOD: improving supervised outlier detection with unsupervised representation learning             IJCNN                         2018   [#Zhao2018Xgbod]_             `[PDF] <http://www.andrew.cmu.edu/user/yuezhao2/papers/18-ijcnn-xgbod.pdf>`_
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.10. Interpretability
^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Explaining Anomalies in Groups with Characterizing Subspace Rules                                  DMKD                          2018   [#Macha2018Explaining]_       `[PDF] <https://www.andrew.cmu.edu/user/lakoglu/pubs/18-pkdd-journal-xpacs.pdf>`_
Beyond Outlier Detection: LookOut for Pictorial Explanation                                        ECML-PKDD                     2018   [#Gupta2018Beyond]_           `[PDF] <https://www.andrew.cmu.edu/user/lakoglu/pubs/18-pkdd-lookout.pdf>`_
Contextual outlier interpretation                                                                  IJCAI                         2018   [#Liu2018Contextual]_         `[PDF] <https://arxiv.org/pdf/1711.10589.pdf>`_
Mining multidimensional contextual outliers from categorical relational data                       IDA                           2015   [#Tang2015Mining]_            `[PDF] <http://www.cs.sfu.ca/~jpei/publications/Contextual%20outliers.pdf>`_
Discriminative features for identifying and interpreting outliers                                  ICDE                          2014   [#Dang2014Discriminative]_    `[PDF] <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.706.5744&rep=rep1&type=pdf>`_
Sequential Feature Explanations for Anomaly Detection                                              TKDD                          2019   [#Siddiqui2019Sequential]_    `[HTML] <https://dl.acm.org/citation.cfm?id=3230666>`_
Beyond Outlier Detection: Outlier Interpretation by Attention-Guided Triplet Deviation Network     WWW                           2021   [#Xu2021Beyond]_              `[PDF] <https://jiansonglei.github.io/files/21WWW.pdf>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.11. Outlier Detection with Neural Networks
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                         Venue                         Year   Ref                           Materials
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Detecting spacecraft anomalies using lstms and nonparametric dynamic thresholding                   KDD                           2018   [#Hundman2018Detecting]_      `[PDF] <https://arxiv.org/pdf/1802.04431.pdf>`_, `[Code] <https://github.com/khundman/telemanom>`_
MAD-GAN: Multivariate Anomaly Detection for Time Series Data with Generative Adversarial Networks   ICANN                         2019   [#Li2019MAD]_                 `[PDF] <https://arxiv.org/pdf/1901.04997.pdf>`_, `[Code] <https://github.com/LiDan456/MAD-GANs>`_
Generative Adversarial Active Learning for Unsupervised Outlier Detection                           TKDE                          2019   [#Liu2019Generative]_         `[PDF] <https://arxiv.org/pdf/1809.10816.pdf>`_, `[Code] <https://github.com/leibinghe/GAAL-based-outlier-detection>`_
Deep Autoencoding Gaussian Mixture Model for Unsupervised Anomaly Detection                         ICLR                          2018   [#Zong2018Deep]_              `[PDF] <http://www.cs.ucsb.edu/~bzong/doc/iclr18-dagmm.pdf>`_, `[Code] <https://github.com/danieltan07/dagmm>`_
Deep Anomaly Detection with Outlier Exposure                                                        ICLR                          2019   [#Hendrycks2019Deep]_         `[PDF] <https://arxiv.org/pdf/1812.04606.pdf>`_, `[Code] <https://github.com/hendrycks/outlier-exposure>`_
Unsupervised Anomaly Detection With LSTM Neural Networks                                            TNNLS                         2019   [#Ergen2019Unsupervised]_     `[PDF] <https://arxiv.org/pdf/1710.09207.pdf>`_, `[IEEE] <https://ieeexplore.ieee.org/document/8836638>`_,
Effective End-to-end Unsupervised Outlier Detection via Inlier Priority of Discriminative Network   NeurIPS                       2019   [#Wang2019Effective]_         `[PDF] <https://papers.nips.cc/paper/8830-effective-end-to-end-unsupervised-outlier-detection-via-inlier-priority-of-discriminative-network.pdf>`_ `[Code] <https://github.com/demonzyj56/E3Outlier>`_
Fascinating Supervisory Signals and Where to Find Them: Deep Anomaly Detection with Scale Learning  ICML                          2023   [#Xu2023Fascinating]_         `[PDF] <https://arxiv.org/abs/2305.16114>`_, `[Code] <https://github.com/xuhongzuo/scale-learning>`_ 
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.12. Active Anomaly Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                         Venue                         Year   Ref                           Materials
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Active learning for anomaly and rare-category detection                                             NeurIPS                       2005   [#Pelleg2005Active]_          `[PDF] <http://papers.nips.cc/paper/2554-active-learning-for-anomaly-and-rare-category-detection.pdf>`_
Outlier detection by active learning                                                                SIGKDD                        2006   [#Abe2006Outlier]_            `[PDF] <https://www.researchgate.net/profile/Naoki_Abe2/publication/221653343_Outlier_detection_by_active_learning/links/5441464a0cf2e6f0c0f60abb.pdf>`_
Active Anomaly Detection via Ensembles: Insights, Algorithms, and Interpretability                  Preprint                      2019   [#Das2019Active]_             `[PDF] <https://arxiv.org/pdf/1901.08930.pdf>`_
Meta-AAD: Active Anomaly Detection with Deep Reinforcement Learning                                 ICDM                          2020   [#Zha2020Meta]_               `[PDF] <https://arxiv.org/pdf/2009.07415.pdf>`_
A3: Activation Anomaly Analysis                                                                     ECML-PKDD                     2020   [#Sperl2021A3]_               `[PDF] <https://arxiv.org/pdf/2003.01801>`_, `[Code] <https://github.com/Fraunhofer-AISEC/A3>`_
==================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.13. Interactive Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Learning On-the-Job to Re-rank Anomalies from Top-1 Feedback                                       SDM                           2019   [#Lamba2019Learning]_         `[PDF] <https://epubs.siam.org/doi/pdf/10.1137/1.9781611975673.69>`_
Interactive anomaly detection on attributed networks                                               WSDM                          2019   [#Ding2019Interactive]_       `[PDF] <http://www.public.asu.edu/~jundongl/paper/WSDM19_GraphUCB.pdf>`_
eX2: a framework for interactive anomaly detection                                                 IUI Workshop                  2019   [#Arnaldo2019ex2]_            `[PDF] <http://ceur-ws.org/Vol-2327/IUI19WS-ESIDA-2.pdf>`_
Tripartite Active Learning for Interactive Anomaly Discovery                                       IEEE Access                   2019   [#Zhu2019Tripartite]_         `[PDF] <https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8707963>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.14. Outlier Detection in Other fields
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

============== =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Field          Paper Title                                                                                        Venue                         Year   Ref                           Materials
============== =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
**Text**       Outlier detection for text data                                                                    SDM                           2017   [#Kannan2017Outlier]_         `[PDF] <https://epubs.siam.org/doi/pdf/10.1137/1.9781611974973.55>`_
============== =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.15. Outlier Detection Applications
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

========================    =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Field                       Paper Title                                                                                        Venue                         Year   Ref                           Materials
========================    =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
**Security**                A survey of distance and similarity measures used within network intrusion anomaly detection       IEEE Commun. Surv. Tutor.     2015   [#WellerFahy2015A]_           `[PDF] <https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6853338>`_
**Security**                Anomaly-based network intrusion detection: Techniques, systems and challenges                      Computers & Security          2009   [#GarciaTeodoro2009Anomaly]_  `[PDF] <http://dtstc.ugr.es/~jedv/descargas/2009_CoSe09-Anomaly-based-network-intrusion-detection-Techniques,-systems-and-challenges.pdf>`_
**Finance**                 A survey of anomaly detection techniques in financial domain                                       Future Gener Comput Syst      2016   [#Ahmed2016A]_                `[PDF] <http://isiarticles.com/bundles/Article/pre/pdf/76882.pdf>`_
**Traffic**                 Outlier Detection in Urban Traffic Data                                                            WIMS                          2018   [#Djenouri2018Outlier]_       `[PDF] <http://dss.sdu.dk/assets/fpd-lof/outlier-detection-urban.pdf>`_
**Social Media**            A survey on social media anomaly detection                                                         SIGKDD Explorations           2016   [#Yu2016A]_                   `[PDF] <https://arxiv.org/pdf/1601.01102.pdf>`_
**Social Media**            GLAD: group anomaly detection in social media analysis                                             TKDD                          2015   [#Yu2015Glad]_                `[PDF] <https://arxiv.org/pdf/1410.1940.pdf>`_
**Machine Failure**         Detecting the Onset of Machine Failure Using Anomaly Detection Methods                             DAWAK                         2019   [#Riazi2019Detecting]_        `[PDF] <https://webdocs.cs.ualberta.ca/~zaiane/postscript/DAWAK19.pdf>`_
**Video Surveillance**      AnomalyNet: An anomaly detection network for video surveillance                                    TIFS                          2019   [#Zhou2019AnomalyNet]_        `[IEEE] <https://ieeexplore.ieee.org/document/8649753>`_, `Code <https://github.com/joeyzhouty/AnomalyNet>`_
========================    =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.16. Automated Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
AutoML: state of the art with a focus on anomaly detection, challenges, and research directions    Int J Data Sci Anal           2022   [#Bahri2022automl]_           `[PDF] <https://www.researchgate.net/publication/358364044_AutoML_state_of_the_art_with_a_focus_on_anomaly_detection_challenges_and_research_directions>`_
AutoOD: Automated Outlier Detection via Curiosity-guided Search and Self-imitation Learning        ICDE                          2020   [#Li2020AutoOD]_              `[PDF] <https://arxiv.org/pdf/2006.11321.pdf>`_
Automatic Unsupervised Outlier Model Selection                                                     NeurIPS                       2021   [#Zhao2020Automating]_        `[PDF] <https://www.andrew.cmu.edu/user/yuezhao2/papers/21-neurips-metaod.pdf>`_, `[Code] <https://github.com/yzhao062/MetaOD>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.17. Machine Learning Systems for Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This section summarizes a list of systems for outlier detection, which may
overlap with the section of tools and libraries.

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
PyOD: A Python Toolbox for Scalable Outlier Detection                                              JMLR                          2019   [#Zhao2019PYOD]_              `[PDF] <https://www.jmlr.org/papers/volume20/19-011/19-011.pdf>`_, `[Code] <https://github.com/yzhao062/pyod>`_
SUOD: Accelerating Large-Scale Unsupervised Heterogeneous Outlier Detection                        MLSys                         2021   [#Zhao2021SUOD]_              `[PDF] <https://arxiv.org/pdf/2003.05731.pdf>`_, `[Code] <https://github.com/yzhao062/suod>`_
TOD: Tensor-based Outlier Detection                                                                Preprint                      2021   [#Zhao2021TOD]_               `[PDF] <https://arxiv.org/pdf/2110.14007.pdf>`_, `[Code] <https://github.com/yzhao062/pytod>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================



4.18. Fairness and Bias in Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
A Framework for Determining the Fairness of Outlier Detection                                      ECAI                          2020   [#Davidson2020A]_             `[PDF] <https://web.cs.ucdavis.edu/~davidson/Publications/TR.pdf>`_
FAIROD: Fairness-aware Outlier Detection                                                           AIES                          2021   [#Shekhar2021FAIROD]_         `[PDF] <https://arxiv.org/pdf/2012.03063.pdf>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================



4.19. Isolation-Based Methods
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  =============================  ==============================================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                            Materials
=================================================================================================  ============================  =====  =============================  ==============================================================================================================================================================================================
Isolation forest                                                                                   ICDM                          2008   [#Liu2008Isolation]_           `[PDF] <https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf>`_
Isolation‐based anomaly detection using nearest‐neighbor ensembles                                  Computational Intelligence    2018   [#Bandaragoda2018Isolation]_   `[PDF] <https://www.researchgate.net/publication/322359651_Isolation-based_anomaly_detection_using_nearest-neighbor_ensembles_iNNE>`_, `[Code] <https://github.com/zhuye88/iNNE>`_
Extended Isolation Forest                                                                          TKDE                          2019   [#Hariri2019Extended]_         `[PDF] <https://arxiv.org/pdf/1811.02141.pdf>`_, `[Code] <https://github.com/sahandha/eif>`_
Isolation Distributional Kernel: A New Tool for Kernel based Anomaly Detection                     KDD                           2020   [#Ting2020Isolation]_          `[PDF] <https://arxiv.org/pdf/2009.12196.pdf>`_, `[Code] <https://github.com/IsolationKernel/Codes/tree/main/IDK>`_
Deep Isolation Forest for Anomaly Detection                                                        TKDE                          2023   [#Xu2023Deep]_                 `[PDF] <https://arxiv.org/abs/2206.06602>`_, `[Code] <https://github.com/xuhongzuo/deep-iforest>`_
=================================================================================================  ============================  =====  =============================  ==============================================================================================================================================================================================



4.20. Emerging and Interesting Topics
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Clustering with Outlier Removal                                                                    TKDE                          2019   [#Liu2018Clustering]_         `[PDF] <https://arxiv.org/pdf/1801.01899.pdf>`_
Real-World Anomaly Detection by using Digital Twin Systems and Weakly-Supervised Learning          IEEE Trans. Ind. Informat.    2020   [#Castellani2020Siamese]_     `[PDF] <https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9179030>`_
SSD: A Unified Framework for Self-Supervised Outlier Detection                                     ICLR                          2021   [#Sehwag2021SSD]_             `[PDF] <https://openreview.net/pdf?id=v5gjXpmR8J>`_, `[Code] <https://github.com/inspire-group/SSD>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


----

5. Key Conferences/Workshops/Journals
-------------------------------------

5.1. Conferences & Workshops
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Key data mining conference **deadlines**, **historical acceptance rates**, and more
can be found `data-mining-conferences <https://github.com/yzhao062/data-mining-conferences>`_.


`ACM International Conference on Knowledge Discovery and Data Mining (SIGKDD) <http://www.kdd.org/conferences>`_. **Note**: SIGKDD usually has an Outlier Detection Workshop (ODD), see `ODD 2021 <https://oddworkshop.github.io/>`_.

`ACM International Conference on Management of Data (SIGMOD) <https://sigmod.org/>`_

`The Web Conference (WWW) <https://www2018.thewebconf.org/>`_

`IEEE International Conference on Data Mining (ICDM) <http://icdm2018.org/>`_

`SIAM International Conference on Data Mining (SDM) <https://www.siam.org/Conferences/CM/Main/sdm19>`_

`IEEE International Conference on Data Engineering (ICDE) <https://icde2018.org/>`_

`ACM InternationalConference on Information and Knowledge Management (CIKM) <http://www.cikmconference.org/>`_

`ACM International Conference on Web Search and Data Mining (WSDM) <http://www.wsdm-conference.org/2018/>`_

`The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD) <http://www.ecmlpkdd2018.org/>`_

`The Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD) <http://pakdd2019.medmeeting.org>`_

5.2. Journals
^^^^^^^^^^^^^

`ACM Transactions on Knowledge Discovery from Data (TKDD) <https://tkdd.acm.org/>`_

`IEEE Transactions on Knowledge and Data Engineering (TKDE) <https://www.computer.org/web/tkde>`_

`ACM SIGKDD Explorations Newsletter <http://www.kdd.org/explorations>`_

`Data Mining and Knowledge Discovery <https://link.springer.com/journal/10618>`_

`Knowledge and Information Systems (KAIS) <https://link.springer.com/journal/10115>`_

----

References
----------

.. [#Abe2006Outlier] Abe, N., Zadrozny, B. and Langford, J., 2006, August. Outlier detection by active learning. In *Proceedings of the 12th ACM SIGKDD international conference on Knowledge discovery and data mining*, pp. 504-509, ACM.

.. [#Aggarwal2013Outlier] Aggarwal, C.C., 2013. Outlier ensembles: position paper. *ACM SIGKDD Explorations Newsletter*\ , 14(2), pp.49-58.

.. [#Ahmed2016A] Ahmed, M., Mahmood, A.N. and Islam, M.R., 2016. A survey of anomaly detection techniques in financial domain. *Future Generation Computer Systems*\ , 55, pp.278-288.





