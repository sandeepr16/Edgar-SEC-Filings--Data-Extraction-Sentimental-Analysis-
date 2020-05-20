# Edgar-SEC-Filings--Data-Extraction-Sentimental-Analysis
EDGAR financial reports extraction and performed text analysis

1	Variables:
“Text Analysis.docx” you need to compute following: 
Section 1.1: Positive score, negative score, polarity score
Section 2: Average Sentence Length, percentage of complex words, fog index
Section 4: Complex word count
Section 5: Word count
 
In addition to these eight variables, compute two more items: “uncertainty” and “constraining”. These variables are calculated similar to the ones in Section 1.1 or Section 4. Attached the lists of words that are classified as uncertain or constraining.

For uncertainty: “uncertainty_dictionary.xlsx”
For constraining: “constraining_dictionary.xlsx”
 
That means you need to collect/compute 10 variables in total.

2	Sections:
For each report (financial reports, links available in excel, cik list), we would like these 10 variables calculated for three sections. These are 
“Management's Discussion and Analysis”, 
“Quantitative and Qualitative Disclosures about Market Risk”, and 
“Risk Factors”. 


3	Additional Variables: positive/negative and uncertainty/constraining word proportion 
The absolute values of “Positive/Negative Scores” are equal to the number of positive/negative words in each section of 10-Q/K; so the (Loughran-McDonald) positive/negative word proportion can be simply calculated as “Positive/Negative Scores divided by Word Count – compute these measure in addition to Polarity Score.  And, the “uncertainty score” and “constraining score” will be also just equal to the number of corresponding words and you can calculate the portion of these words as same as above.  
 
4	Additional Variable: Constraining words for whole report
Add one variable to the mix, which will be calculated only once for the whole report (i.e., not three times). It’s the number of “constraining” words over the whole report rather than in any specific section.

5	Output Data Structure
Notations: 
“Management's Discussion and Analysis”: MDA
“Quantitative and Qualitative Disclosures about Market Risk”: QQDMR
“Risk Factors”: RF

Output Variables: 
1.	All input variables in “cik_list.xlsx”
2.	mda_positive_score
3.	mda_negative_score
4.	mda_polarity_score
5.	mda_average_sentence_length
6.	mda_percentage_of_complex_words
7.	mda_fog_index
8.	mda_complex_word_count
9.	mda_word_count
10.	mda_uncertainty_score
11.	mda_constraining_score
12.	mda_positive_word_proportion
13.	mda_negative_word_proportion
14.	mda_uncertainty_word_proportion
15.	mda_constraining_word_proportion
16.	qqdmr_positive_score
17.	qqdmr_negative_score
18.	qqdmr_polarity_score
19.	qqdmr_average_sentence_length
20.	qqdmr_percentage_of_complex_words
21.	qqdmr_fog_index
22.	qqdmr_complex_word_count
23.	qqdmr_word_count
24.	qqdmr_uncertainty_score
25.	qqdmr_constraining_score
26.	qqdmr_positive_word_proportion
27.	qqdmr_negative_word_proportion
28.	qqdmr_uncertainty_word_proportion
29.	qqdmr_constraining_word_proportion
30.	rf_positive_score
31.	rf_negative_score
32.	rf_polarity_score
33.	rf_average_sentence_length
34.	rf_percentage_of_complex_words
35.	rf_fog_index
36.	rf_complex_word_count
37.	rf_word_count
38.	rf_uncertainty_score
39.	rf_constraining_score
40.	rf_positive_word_proportion
41.	rf_negative_word_proportion
42.	rf_uncertainty_word_proportion
43.	rf_constraining_word_proportion
44.	constraining_words_whole_report

