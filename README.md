process to create a power prediction model in the next day
1. Import the necessary library
2. Read data from a file.
3. Do data cleansing by
     3.1 Inspecting the number of nulls in each column
     3.2 Using dropna() to eliminate null space and drop_duplicates() to eliminate replicated rows
5. Plot the data to see the trend of power versus temperature, and humidity.
6. Create a model for prediction by assuming that the power is linear with temperature and humidity, and randomly choose train data by using the train_test_split command with the ratio train: test = 30:70 and using reg.fit(). Then, using reg.score() for model evaluation.
   
หมายเหตุ เนื่องจากยังไม่มีความรู้มากพอในการทำ project ด้านนี้ หากเป็นไปได้ก็อยากจะลองหาโอกาสที่จะได้ศึกษาเพิ่มเติม แต่หากยังไม่สามารถเข้าร่วมกับโครงการได้ ก็ไม่เป็นไรนะครับ(พี่ๆ จะได้ไม่ลำบากใจ) แล้วก็ขอบคุณที่ได้ลองให้โอกาสมาทำครับ
