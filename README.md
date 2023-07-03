# Know Your Bias

A website built using HTML, CSS, JavaScript, and Flask for the [AI Hackfest Hackathon](https://ai-hackfest.devpost.com)

Know Your Bias uses machine learning to determine the political bias of an article, and presents users with articles on the same topic with opposing viewpoints and political biases. The model used for this project was trained by feeding a large dataset of articles and their political biases into a random forest algorithm from [scikit-learn](https://scikit-learn.org/). The [Amazon Comprehend API](https://docs.aws.amazon.com/comprehend/latest/APIReference/welcome.html) is used to find keywords associated with the articles being analyzed, and then uses the [newscatcherAPI](https://newscatcherapi.com/) to find articles on the same topic with opposing viewpoints. For more information, watch this [demo](https://youtu.be/6MfIhqMt-bk) video.

## Preview
![Webpage](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/002/478/074/datas/gallery.jpg)

![Webpage](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/002/478/992/datas/gallery.jpg)
