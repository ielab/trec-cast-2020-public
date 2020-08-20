Runs priority:

1. ielab-bertserini-QA-2020-10.txt
2. ielab_bm25T5QLM.txt
3. ielab-bertPRF-QA-2020-10.txt
4. ielab-bm25-2020-AQ.txt

## ielab-bm25-2020-AQ.txt

SUBMISSION CATAGORY: Raw Utterance only
CONVERSATIONAL QUERY UNDERSTANDING METHOD: Query Exspansion
PASSAGE RANKING METHOD: method uses only unsupervised retrieval (QL, BM25, etc.)
CONVERSATIONAL CONTEXT: method uses previous raw utterances (queries) in the topic

## ielab-bertserini-QA-2020-10.txt

SUBMISSION CATAGORY: Raw Utterance only
CONVERSATIONAL QUERY UNDERSTANDING METHOD: Query Exspansion
PASSAGE RANKING METHOD: method uses a pre-trained neural language model (BERT, Roberta, T5, etc.) 
CONVERSATIONAL CONTEXT: method uses previous raw utterances (queries) in the topic

BERT based re-ranking of BM25+RM3 baseline. Top k=10 documents only are re-ranked using BERT. For each topic, for utterances beyond the first, the first query is appended.


## ielab-bertPRF-QA-2020-10.txt

SUBMISSION CATAGORY: Raw Utterance only
CONVERSATIONAL QUERY UNDERSTANDING METHOD: Query Exspansion
PASSAGE RANKING METHOD: method uses a pre-trained neural language model (BERT, Roberta, T5, etc.) 
CONVERSATIONAL CONTEXT: method uses previous raw utterances (queries) in the topic

## ielab_bm25T5QLM.txt

SUBMISSION CATAGORY: Raw Utterance only
CONVERSATIONAL QUERY UNDERSTANDING METHOD: Query Exspansion
PASSAGE RANKING METHOD: method uses a pre-trained neural language model (BERT, Roberta, T5, etc.) 
PASSAGE RANKING DATA: method is trained with CAsT Y1 dataset
CONVERSATIONAL CONTEXT: method uses previous raw utterances (queries) in the topic
