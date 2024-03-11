This is an assignment for my machine learning couse. Below are the instructions: 

An automated answer-rating site marks each post in a community forum website as “good” or “bad” based on the quality of the post. The required data in the form of a CSV file is available. The following are the type of qualities that the dataset contains:
num_words: number of words in the post
num_characters: number of characters in the post
num_misspelled: number of misspelled words
bin_end_qmark: if the post ends with a question mark
num_interrogative: number of interrogative words in the post
bin_start_small: if the answer starts with a lowercase letter (1 means yes, otherwise no) num_sentences: number of sentences per post
num_punctuations: number of punctuation symbols in the post
label: the label of the post (G for good and B for bad) as determined by the tool.
Using the features available, build a logistic regression-based classifier to classify a post’s label (G or B). Make sure to create appropriate training and testing sets from the available data
