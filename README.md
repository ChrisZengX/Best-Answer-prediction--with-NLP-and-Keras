# Best-answer-prediction--with-NLP-and-keras
This is a study case of predict the best answer of a question-answers-comments platform（Stackflow etc.)  
With the original question, answer, comments, votes_number, time, comment number and answer number etc, to predict the best answer.  
In the code, I used Keras model with 4 inputs, tensorflow etc.  

Here is the list of variables :   
(int) "id", (char) "question_answer_or_comment" (Q=Question, A=Answer, C=Comment), (bool) "is_best_answer", (int) "topic_id", (int) "parent_id", (int) "votes", (string) "titre", (string) "message", (int) "member", (int) "category", (int) "state" (0=deleted, 1=online, 2=online but closed), (bool) "is_solved", (int) "num_answers", (string) "country", (unix_timestamp) "date", (unix_timestamp) "last_answer_date", (int) "auteur_crc", (int) "visits"
