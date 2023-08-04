I have used the *Myers-Briggs Type Indicator (MBTI) Dataset* from Kaggle to train a Logistic Regression model that classifies a person as one of the 16 possible personality types from the MBTI dataset based on the text extracted from their resumes.

I have used ResumeDataset.csv from Kaggle to provide the model with Resume data for prediction.

I have also provided the code that can take any text input from the user, that text can be the entire text copied from someone's CV.

The model will then attempt to classify a person's personality type based on that text.

Brief Description of each personality type from the Myers-Briggs Type Indicator (MBTI) Dataset
The Myers-Briggs Type Indicator (MBTI) Dataset categorizes personality types based on four dimensions: *extraversion (E) vs. introversion (I), sensing (S) vs. intuition (N), thinking (T) vs. feeling (F), and judging (J) vs. perceiving (P)*.
The combination of these dimensions results in *16 distinct personality types*. Here's a brief overview of each personality type in the MBTI dataset:
*ISTJ (Introversion, Sensing, Thinking, Judging)*: ISTJs are practical, responsible, and dependable. They prefer structure, follow rules, and focus on details.

*ISFJ (Introversion, Sensing, Feeling, Judging)*: ISFJs are warm, caring, and reliable. They are attentive to others' needs, value harmony, and are detail-oriented.

*INFJ (Introversion, Intuition, Feeling, Judging)*: INFJs are insightful, compassionate, and idealistic. They have a deep understanding of others, seek meaning, and are driven by their values.

*INTJ (Introversion, Intuition, Thinking, Judging)*: INTJs are strategic, independent, and logical. They have a long-term vision, excel in analyzing complex problems, and value competence.

*ISTP (Introversion, Sensing, Thinking, Perceiving)*: ISTPs are observant, analytical, and adaptable. They enjoy hands-on activities, value practicality, and are skilled problem solvers.

*ISFP (Introversion, Sensing, Feeling, Perceiving)*: ISFPs are artistic, gentle, and empathetic. They appreciate beauty, value personal values, and enjoy expressing themselves creatively.

*INFP (Introversion, Intuition, Feeling, Perceiving)*: INFPs are compassionate, imaginative, and individualistic. They seek authenticity, value personal growth, and are driven by their ideals.
*INTP (Introversion, Intuition, Thinking, Perceiving)*: INTPs are logical, curious, and innovative. They have a thirst for knowledge, enjoy theoretical thinking, and are skilled problem solvers.

*ESTP (Extraversion, Sensing, Thinking, Perceiving)*: ESTPs are outgoing, energetic, and action-oriented. They are adaptable, enjoy new experiences, and excel in fast-paced environments.

*ESFP (Extraversion, Sensing, Feeling, Perceiving)*: ESFPs are enthusiastic, friendly, and spontaneous. They appreciate sensory experiences, value social connections, and seek joy in the present moment.

*ENFP (Extraversion, Intuition, Feeling, Perceiving)*: ENFPs are enthusiastic, creative, and empathetic. They value personal growth, enjoy exploring possibilities, and are skilled communicators.

*ENTP (Extraversion, Intuition, Thinking, Perceiving)*: ENTPs are inventive, quick-witted, and intellectually curious. They enjoy debates, value creativity, and excel in generating new ideas.

*ESTJ (Extraversion, Sensing, Thinking, Judging)*: ESTJs are organized, practical, and efficient. They value structure, follow traditions, and excel in leadership roles.

*ESFJ (Extraversion, Sensing, Feeling, Judging)*: ESFJs are warm, outgoing, and supportive. They value harmony, prioritize the needs of others, and excel in nurturing relationships.

*ENFJ (Extraversion, Intuition, Feeling, Judging)*: ENFJs are charismatic, empathetic, and influential. They value harmony, are skilled at understanding others' emotions, and excel in leadership and helping roles.

*ENTJ (Extraversion, Intuition, Thinking, Judging)*: ENTJs are strategic, assertive, and efficient. They have strong leadership skills, value competence, and excel in organizational settings.

It's important to note that these brief descriptions capture some general characteristics associated with each personality type, but individual variations exist within each type.
