# ChatInterpretter
Analyzing chat conversations!

The Project contains multiple parts as follows:

(A) Sentiment Analysis:

We classify the sentiment of the text into positive, negative and neutral.

For example,

consider the text: "You're the best man, I love talking to you!", the output for this example would be as follows:

neg: 0.0

neu: 0.408

pos: 0.592

These are the respective probabilities of the text being negative, neutral and positive.


Consider another example: "I can't have any logical conversations with you, you're so dumb", the output here is:

neg: 0.32 

neu: 0.68 

pos: 0.0



(B) Task Extraction:

We intend to extract the various commitments and deadlines mentioned in the chat which are worth a reminder.

For example,

Consider the statement:

"Hey brother how are you! I'll reach your place by 10 today, so be ready.", the output for this would be:

"I 'll reach your place by 10 today"

Hence, we successfully chunk out the task.

Let's consider another example:

"Hey driver, please be early tomorrow, I have my flight at 6 in the morning.", here we got the following as output:

'I have my flight at 6 in the morning'

Again we could extract the relevant information

Requirements:

The codes have been written in Jupyter Notebook which was installed along through Anaconda Distributions, therefore, various libraries were already downloaded along with the Anaconda Distributions, therefore the same is suggested for the tester.
