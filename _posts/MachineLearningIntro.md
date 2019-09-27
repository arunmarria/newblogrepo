**Introduction to Machine Learning**

Machine learning is one of the most popular technical terms of the century. One need not to have a strong computers background to understand basics of machine learning. It's in fact quite comparable to how humans learn. Human learning can come from different sources like reading books, experiences, watching educational videos, talking to people, seeing images etc. Consider how a child learns to recognize animals for the very first time. One of the ways to do this is to show him **labeled** pictures of different animals(until he starts recognizing). Now the next time he sees a new animal, he can quickly use his experience(of learning from labeled images) to recognize the animal. 

Machine learning is quite similar to human learning. It is the process of making machines i.e. computers learn. As we cannot show labeled images and/or communicate with computers directly(as we do with kids); we provide computers with the data/information from which they can learn about a particular thing. Computers can then use this experience of learning(from the data fed) to recognize characteristics of new(but similar) data. In a formal way, *"Machine Learning is the science of getting computers to learn and act like humans do, and improve their learning over time in autonomous fashion, by feeding them data and information in the form of observations and real-world interactions."[1]* 


There are some important terms associated with this entire learning process. Let’s try understanding these terms with an example. 


Consider a scenario where you want a computer to tell/predict that whether a person has cancer or not. In order to achieve this, we feed the computer with the data/information about multiple people for whom we already know if they have cancer or not. The data may include tumour size, genetic history, medication history, age, sex etc. The computer then uses these properties/**features** to learn what causes cancer in a given person. This phase is called **training phase** and the data used for training the computer is called **training data**. Comparing that to our previous example of a kid learning to recognize animals, the phase when a kid is repeatedly made to see labeled pictures is called training phase. And the training data in that case is labeled animal images which may include features like shape of animal, color, number of legs etc.

After training phase comes the **testing phase**. Here we make the computer to predict/answer a question based on experience from the training phase. In our cancer prediction example, we ask computer to tell whether a new person has cancer or not. The computer will then use the data (tumor size, age, sex etc.) for new person and answer based on the learning experience from training phase. In human learning this is just the part where we test the kid to recognize an animal  outside the labeled images; this might be a dog or cat walking on the street. The kid can then use his experience from training phase to answer. This phase where we test computer’s answers is called testing phase and data used for testing phase is called the **test data**. The table below summarizes this info for human and machine learning. 

|               | Human learning(teaching a kid to recognize animals)    | Machine learning(predicting a cancer)                      |
|---------------|--------------------------------------------------------|------------------------------------------------------------|
| Features      | Shape of animal, colour, number of legs, etc.          | Sex, age, tumour size, genetic history, medical history etc.   |
| Training data | Labeled images of animals showing different features   | Data about individuals for whom it is known if they have cancer |
| Test data     | Any animal walking on the street(unseen by kid before) | Data about individuals which is unseen by computer(but we know outcomes)           |
| Label/target variable to be learned    | Animal names like dog, cat, deer etc. | Whether a person has cancer or not |




Now what to do when a kid fails to recognize some of the animals? 

We provide the kid **feedback** and the kid further learns from the feedback. Similarly, for incorrect predictions which computer make feedback is provided either by supplying more training data or some other methods. The computer then does predictions better. 


Finally, what do we do when a kid answers almost everything correctly? 

We then say that the kid is good to go. He knows how to recognize animals. Similarly, when the machine does correct predictions on test data, we confirm that it is good to go for normal use. This is in computer terminology is called good for **production systems**, where computers can make predictions/analyze on completely unseen data.

Nowadays, machine learning is applied in almost every field. Some of the applications include predicting stock prices, predicting revenue of a company in given financial year, image recognition, recommender systems, identifying number of gangs a ship may demand etc. 

**REFERENCES**

[1] The formal definition of Machine learning(italicized part) is taken from [Emerj website](https://emerj.com/ai-glossary-terms/what-is-machine-learning/) blogged by Daniel Faggella - the founder and CEO at Emerj.
