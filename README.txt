Detailed experimental results for single and multiple papers summarisation using the A-KPLM framework. 

Part I: Single paper extractive summarisation:

The data used is Qazvinian's single paper summarisation corpus (downloadable from http://www-personal.umich.edu/~vahed/data.html). 

Single paper summaries generated using A-KPLM can be found in the single_paper_summaries folder. 

There are 5 sub-folders underneath, each corresponds to one of the 5 domains in this corpus:

DP: Dependency Parsing
PBMT: Phrase Based Machine Translation
QA: Question Answering
SUM: Summarisation
TE: Textual Entailment

An extractive summary generated for each paper in this corpus using A-KPLM can be found in the perspective .txt file.   

The file: single_paper_summarisation_pyramid_scores.csv under the single_paper_summaries folder contains Pyramid scores obtained on each of the 25 papers using A-KPLM, from which the mean (0.81) and median (0.89) scores are calculable.


Part II: Multiple paper extractive summarisation:  

The data used is Qazvinian's survey generation corpus (downloadable from http://www-personal.umich.edu/~vahed/data.html)

Multiple paper summaries generated using the A-KPLM framework can be found in the multiple_paper_summaries folder, which are further arranged in the following two sub-folders:

DP: containing key contribution summaries generated for the Dependency Parsing domain
QA: containing key contribution summaries generated for the Question Answering domain

The two sub-folders are of identical structure:

A-KPLM 55: this folder contains all 55 250-words key contribution summaries generated using the A-KPLM framework with all 55 parameter combinations in both html and txt formats. The html files can be directly used by ROUGE-1.5.5 toolkit for evaluation, while the txt files are ready for pyramid score evaluation using the detect_nuggets.pl Perl script shipped with Qazvinian's survey generation corpus. 

A-KPLM best: this folder contains the summary with the highest pyramid F-measure (A-KPLM best in Table 3 in the paper) in both html and txt format. The html files can be directly used by ROUGE-1.5.5 toolkit for evaluation, while the txt files are ready for pyramid score evaluation using the detect_nuggets.pl perl script shipped with Qazvinian's survey generation corpus. 


