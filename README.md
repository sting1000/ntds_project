# A Network Tour of NIPS Conference papers

**Group 26: Yueran Liang, Peilin Kang, Yawen Hou, Zhechen Su**

Machine   learning   has   always   been   a   very   popularsubject  since  the  last  decade.  In  the  last  few  years,  thenumber  of  papers  submitted  to  the  top  machine  learningconferences has been increasing exponentially. More andmore   researchers   become   interested   to   this   field   andnew  concepts  and  algorithms  are  proposed  every  yearat  conferences.  Among  all  the  conferences,  Neural  In-formation  Processing  Systems  (NIPS)  is  the  one  of  theworld’s  largest  machine  learning  conference  (see  sectionIV).  For  our  current  project,  we  will  build  our  networksbased  on  NIPS  papers.  We  will  study  the  papers’  topicsand  their  authors’  favorite  topics  by  building  a  networkof  topics  using  Latent  Dirichlet  allocation  (LDA)  andassociate each researcher to the topics they write the mostabout using Author-Topic modeling (ATM). We will alsostudy  the  connections  between  individual  researchers  bybuilding a co-authorship graph using adjacent matrices. Tobetter visualize the networks, we will apply dimensional-ity  reduction  to  our  network  models  using  T-distributedStochastic Neighbor Embedding (t-SNE). We will exploitthe distribution the distribution of the papers’ topics overyears  and  the  distribution  of  topic  preference  per  author.As a result, we will attempt to predict the main topic of anew paper with our LDA model. Given a particular author,we  will  also  attempt  to  look  for  other  authors  that  havethe same research orientation as them

We did not include the dataset in our repository as it exceeds the maximum file size that Github allows. Here is the link to download it: https://drive.google.com/drive/folders/1olqiQqQCjWm5MtteurADoaenn-7neo3n. Do not forget to change the path in the jupyter notebook to load correctly the dataset.

Here is an overview of our repository's architecture:

```
.   
├── model                                   # Folder containing the models we've trained and some processed file that takes a long time to generate from scratch.
├── figure                                  # Folder containing the saved figures we generated
├── **Topic_and_Author_Network.ipynb**      # Jupyter notebook having all the code for our project
├── A Network Tour of NIPS Papers.pdf       # Our report
├── environment.yml                         # Environment file for Anaconda
└── README.md                               # This file
```
