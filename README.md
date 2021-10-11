# datathon-voter-registration
Code from Datathon NYU Fall 2021


Last semester, a close friend and I created a team for a datathon. The goal of this datathon was to make voter data more accessible and anonymous. After some group brainstorming, I thought of the idea of jittering the data to add random noise. The columns I chose were latitude and longitude so that each voter's location was not exactly specified, rather, a five mile radius was given. This increases anonymity of the voter's home address while still staying true to the accuracy of the data.


Goals of the Datathon:
- Condensing dataset
- SRS of data
- Remove columns with lots of missing values/don’t contain super relevant information
- Use isnull function to identify those with many missing values
- Increase granularity 
- Data granularity is the level of detail in a model or decision making process. It tells you how detailed your data is: Lower levels of detail equal finer, more detailed, data granularity
- Make data less specific ex. add data ranges to make the data less personally identifiable
- Jitter data (non-categorical columns)
- Adding random noise
- Dummy-size 
- One-hot encoding
- Make data more usable
- Breaking into smaller tables
- Identify which columns are related/would be useful to use together

