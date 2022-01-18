# A Poor Student's First Try at Robotic Process Automation (RPA)

I am interested in Robotic Process Automation. I am fascinated by UiPath. It allows a user to easily set up automation with drag and drop.
It even allows users to include machine learning models to allow automations to make decisions.

At the UiPath Academy, I learned that this feature is only available for the enterprise version, which costs thousands of USD. In the turorial section of this feature, at https://academy.uipath.com/learningpath-viewer/2910/1/158885/30, the task was to use UiPath's AI Fabric to build a movie review sentiment analysis classifier, so that emails can be automatically sent depending on whether a review is classified as positive or negative.

With some basics of deep learning from my studies, I built my own classifier using the datasets given (Out of copyright concerns, please get them at the academy). I tried various models, but am finally satisfied with the BERT model built in imbd_sentiment_analysis.ipynb.

The actual model files are are bigger than the file size limits in GitHub. I planned to put the model in my website and allow user to get its prediction via a form, but due to this issue and my current tech stack, I will do it after I migrate to AWS.