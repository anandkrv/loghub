<p align="center"> <a href="https://github.com/logpai"> <img src="https://github.com/logpai/logpai.github.io/blob/master/img/logpai_logo.jpg" width="500" height="125"/>  </a>
</p>

# Loghub
Loghub maintains a collection of system logs, which are freely accessible for research purposes. Some of the logs are production data released from previous studies, while some others are collected from real systems in our lab environment. Wherever possible, the logs are NOT sanitized, anonymized or modified in any way. All these logs amount to over **87GB** in size. We thus host only a small sample (2k lines) on Github for each dataset. 

If you use our loghub datasets in your research for publication, please kindly cite the following paper.
+ [**Arxiv'18**] Jieming Zhu, Shilin He, Jinyang Liu, Pinjia He, Qi Xie, Zibin Zheng, Michael R. Lyu. [Tools and Benchmarks for Automated Log Parsing](https://arxiv.org/pdf/1811.03509.pdf). arXiv:1811.03509, 2018.

### How to get the data? 
If you are interested in these datasets, please request the **[raw logs at Zenodo](https://doi.org/10.5281/zenodo.1144100)**. Please kindly note that the affiliation information is minimally required for your data request. 


### Logs currently available (still in beta release):

| Software System               | Time Span  |  #Messages  |   Size   | Compressed (gzip) |        
| :---------------------------- | --------: | ---------: | ------: | ------------------: | 
| **Distributed systems**       |            |             |          |                      |                                          
| [HDFS](./HDFS)                | 38.7 hours | 11,175,629  |  1.54GB  |       152.01MB       |                                          
|                               |    N.A.    | 71,118,073  | 16.84GB  |       877.38MB       |                                          
| [Hadoop](./Hadoop)            |    N.A.    |   394,308   | 49.78MB  |        2.50MB        |                                          
| [Spark](./Spark)              |    N.A.    | 33,236,604  |  2.88GB  |       179.18MB       |                                          
| [Zookeeper](./Zookeeper)      | 26.7 days  |   74,380    | 10.18MB  |        452KB         |                                          
| [OpenStack](./OpenStack)      |    N.A.    |   207,820   | 60.02MB  |        5.27MB        | 
| **Operating systems**         |            |             |          |                      |                                          
| [Windows](./Windows)          | 226.7 days | 114,608,388 | 27.36GB  |        1.63GB        |                                          
| [Linux](./Linux)              | 263.9 days |   25,567    |  2.30MB  |        228KB         |                                          
| [Mac](./Mac)                  |  7.0 days  |   117,283   | 16.48MB  |        1.46MB        |                                          
| **Server applications**       |            |             |          |                      |                                          
| [Apache Web server](./Apache) | 263.9 days |   56,481    |  5.02MB  |        260KB         |                                          
| [OpenSSH](./OpenSSH)          | 28.4 days  |   655,146   | 71.70MB  |        4.49MB        |                                          
| **Mobile systems**            |            |             |          |                      |                                          
| [Andriod](./Andriod)          |    N.A.    | 63,042,037  |  7.00GB  |       825.57MB       |                                          
| [HealthApp](./HealthApp)      | 10.5 days  |   253,395   | 22.98MB  |        2.24MB        |                                          
| **Supercomputers**            |            |             |          |                      |                                          
| [Blue Gene/L](./BGL)          | 214.7 days |  4,747,963  | 725.77MB |       61.46MB        | 
| [HPC](./HPC)                  |    N.A.    |   433,489   | 32.77MB  |        3.21MB        |                                          
| [Thunderbird](./Thunderbird)  |  244 days  | 211,212,192 | 31.04GB  |        1.97GB        |                                          
| **Standalone software**       |            |             |          |                      |                                          
| [Proxifier](./Proxifier)      |    N.A.    |   21,329    |  2.48MB  |        172KB         |                                          

 
### Publications using these datasets
+ [**CCS'17**] Min Du, Feifei Li, Guineng Zheng, Vivek Srikumar. [DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://acmccs.github.io/papers/p1285-duA.pdf). ACM Conference on Computer and Communications Security (CCS), 2017.
+ [**TDSC'17**] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [Towards Automated Log Parsing for Large-Scale Log Data Analysis](http://jiemingzhu.github.io/pub/pjhe_tdsc2017.pdf). IEEE Transactions on Dependable and Secure Computing (TDSC), 2017.
+ [**ICWS'17**] Pinjia He, Jieming Zhu, Zibin Zheng, Michael R. Lyu. [Drain: An Online Log Parsing Approach with Fixed Depth Tree](http://jiemingzhu.github.io/pub/pjhe_icws2017.pdf). IEEE International Conference on Web Services (ICWS), 2017.
+ [**ICSE'16**] Qingwei Lin, Hongyu Zhang, Jian-Guang Lou, Yu Zhang, Xuewei Chen. [Log Clustering Based Problem Identification for Online Service Systems](http://ieeexplore.ieee.org/document/7883294/). International Conference on Software Engineering (ICSE), 2016.
+ [**DSN'16**] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [An Evaluation Study on Log Parsing and Its Use in Log Mining](http://jiemingzhu.github.io/pub/pjhe_dsn2016.pdf). IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2016.
+ [**ISSRE'16**] Shilin He, Jieming Zhu, Pinjia He, Michael R. Lyu. [Experience Report: System Log Analysis for Anomaly Detection](http://jiemingzhu.github.io/pub/slhe_issre2016.pdf). IEEE International Symposium on Software Reliability Engineering (ISSRE), 2016.
+ [**KDD'09**] Adetokunbo Makanju, A. Nur Zincir-Heywood, Evangelos E. Milios. [Clustering Event Logs Using Iterative Partitioning](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.503.7668&rep=rep1&type=pdf). ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), 2009.
+ [**SOSP'09**] Wei Xu, Ling Huang, Armando Fox, David A. Patterson, Michael I. Jordan. [Detecting Large-Scale System Problems by Mining Console Logs](https://www.sigops.org/sosp/sosp09/papers/xu-sosp09.pdf). ACM Symposium on Operating Systems Principles (SOSP), 2009. 
+ [**DSN'07**] Adam J. Oliner, Jon Stearley. [What Supercomputers Say: A Study of Five System Logs](http://ieeexplore.ieee.org/document/4273008/). IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2007.


### Organizations that request these datasets
We proudly announce that the loghub datasets have been requested by more than [**110 organizations**](https://github.com/logpai/loghub/wiki/Loghub) from both industry and academia.


### Feedback
For any questions or feedback, please post to [our issue page](https://github.com/logpai/loghub/issues).

### License
The log datasets are freely available for research purposes. 



