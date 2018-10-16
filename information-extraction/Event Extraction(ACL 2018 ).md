## Papers about event extraction published in ACL 2018.

1. [Event2Mind: Commonsense Inference on Events,Intents,and Reactions](http://aclweb.org/anthology/P18-1043)  
    Investigate a commonsense inference task. Given "X drinks coffee in the morning", system inference "X wants to stay
    awake".   
    They construct a new crowdsourced corpus of 25,000 event phrases covering a diverse range of everyday events and
    situations.

2. [Improving Event Coreference Resolution by Modeling Correlations between Event Coreference Chains and Document Topic Structures](http://aclweb.org/anthology/P18-1045)  
    Event coreference resolution: identify and link event mentions in a document that refer to the same real-world event 

3. [Self-regulation: Employing a Generative Adversarial Network to Improve Event Detection](http://aclweb.org/anthology/P18-1048)  
    Event detection aims to locate the event triggers of specified types In text.  
    The task of event detection is to determine whether there is one or more event triggers in a sentence.
    They propose a self-regulated learning approach by utilizing a generative adversarial network to generate spurious features  

4. [Temporal Event Knowledge Acquisition via Identifying Narratives](http://aclweb.org/anthology/P18-1050)

5. [A Multi-Axis Annotation Scheme for Event Temporal Relations](http://aclweb.org/anthology/P18-1122)  
    This paper proposes a new multi-axis modeling to better capture the temporal structure of events.  

6. [Nugget Proposal Networks for Chinese Event Detection](http://aclweb.org/anthology/P18-1145)  
    Solve the word-trigger mismatch problem by directly proposing entire trigger nuggets centered at each character regardless of word boundaries.
7. [Zero-Shot Transfer Learning for Event Extraction](http://aclweb.org/anthology/P18-1201)  
    We design a transferable architecture of structural and compositional neural networks to jointly represent and map event mentions and types
into a shared semantic space

8. [Document Embedding Enhanced Event Detection with Hierarchical and Supervised Attention](http://aclweb.org/anthology/P18-2066)  
    In this paper, we propose a novel Document Embedding Enhanced Bi-RNN model, called DEEB-RNN, to detect events in sentences.

9. [DCFEE: A Document-level Chinese Financial Event Extraction System based on Automatically Labeled Training Data](http://aclweb.org/anthology/P18-4009)  
    Propose a Document-level Chinese Financial Event Extraction  
    Automatically generate labeled training data using financial event knowledge database
    
 ## My Presentation
 The ninth paper in previous paper list. [Slides](ppt/DCFEE.pptx)
 
 This paper use a financial event knowledge database to label unstructured text automatically.  
 They construct a dictionary of event triggers and select key event arguments for each event type(manually) 
 Then they use triggers and arguments to label training data.
 Use Bi-LSTM-CRF to train model.
 
 The method of automatically find arguments and triggers is in this paper:  
 [Automatically Labeled Data Generation for Large Scale Event Extraction](http://www.nlpr.ia.ac.cn/cip/~liukang/liukangPageFile/ACL2017-Chen.pdf)  
 This paper use freebase to detect key arguments for each event types.  
 Then they use arguments to label data and  detect triggers  
 By using FrameNet, they can filter noisy triggers and expand triggers  
 Finally, use triggers and key arguments to automatically generate labeled data.
