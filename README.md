# COVID-19-diagnosis-system
COVID-19 detector using X-ray images with Keras, TensorFlow, and Deep Learning

Automatic COVID-19 detector is obtaining ~90-92% accuracy on the sample dataset based solely on X-ray images — no other data, including geographical location, population density, etc. was used to train this model.

Obtaining 100% sensitivity and 80% specificity implying that:

Patients that do have COVID-19 (i.e., true positives), we could accurately identify them as “COVID-19 positive” 100% of the time using this model.
Patients that do not have COVID-19 (i.e., true negatives), we could accurately identify them as “COVID-19 negative” only 80% of the time using this model.

Balancing sensitivity and specificity is incredibly challenging when it comes to medical applications, especially infectious diseases that can be rapidly transmitted, such as COVID-19.

When it comes to medical computer vision and deep learning, we must always be mindful of the fact that the predictive models can have very real consequences because a missed diagnosis can cost lives.

Being able to accurately detect COVID-19 with 100% accuracy is great however, the true negative rate is a bit concerning. These results are gathered for educational and research purposes only dont solely rely on this.

There's simply not enough data to train a perfect COVID-19 detector yet there's a large number of patients in hospitals and their data can lead to a nearly perfect, more accurate detector. 

Data is always beautiful and precious!
