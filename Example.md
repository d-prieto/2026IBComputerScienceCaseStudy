# Example of research

For the research, depending on the subtopic can happen that maybe more deep or more brief. If I feel that the topic needs to be more explained than what is here I would split it in different subtopics


Please use images, diagrams (remember diagrams.net), references. Try to explain to the other students you can understand each other. If you are not sure about something, feel free to ask! 

(please don't use AI for generate the images, pretty please)

Depending on the topic this will be slightly different but a structure that you can follow:

- Find a short definition. Probably that will need to be expanded and explained so other students can understand it.
- While you research save your references (that's why it's not a good idea to use AI for this). We will need them later. 
- Now that you understand the idea, maybe is time to find / do an image to represent it. (Don't use AI). We're visual animals and even if is a meme it will be easier for everybody to understand the concept. Try to find something that is tied to the concept that you're explaining.
- Now go back to the booklet and find the word in the context. With the definition that you have is it tied to the context of the booklet? If not, you need to find another part. If it's somewhat tied probably you will need some paragraphs to join it. (How can it be used in this context? is it worth it? does it have any nuances? is it connected to other concepts?)
- Separate your ideas in paragraphs.
- Add your references at the end. 



Here you have an example of an extended example from M25 that I did myself. 


## Bag-of-words algorithm:
_This was expanded by the teacher_

![1740730228463](https://github.com/user-attachments/assets/7a087402-bc47-4d1a-bf71-90177a6b150b)

Bag-of-Words (BoW) is a fundamental technique in natural language processing that represents text as a collection of word counts, ignoring word order or grammar. Used to represent the processing of natural languages and the retrieval of information. In general, it's a text representation technique which describes a document as a collection of words, with no grammar or word order, only focusing on preserving frequency (multiplicity). Thereby converting the textual data into a numerical one. (a very long vector, usually)

With that vector you can differenciate texts that are "close" or apart from each other. Let's supose that we have a text that we want to classify "I want to make a claim about a motorbike accident". We are going to have a space with only 3 dimensions: "Claim" "car" and "health". To use this algorithm we're going to check how many times we have words related to the three that we have ("claim", "car" and "health") and assign them to the x,y,z axis of this vector. The rest of the words  (like "a" or "I") are going to be ignored. We do have actually a word that is claim, so that would be 1 for the dimension of that vector, but we don't have anything related to health, so that would be 0 for that vector. In the case of "motorbike", depending on the implementation we could consider that car is related to motorbike and assume that is a 0.7. This give us that ""I want to make a claim about a motorbike accident" is equal to a vector  [1, 0.7, 0]. But if we do the same for "I want information about a health insurance" then we have [0,0,1] and if it's "I want to make a clame about my health insurance" that would be [1,0,1]. With these numbers we can assign "areas" were we can classify text for further reading into a neural model about claims about car insurance, about health insurance, about other topics and if they about claims or not. 

### Uses

The bag-of-words model is commonly used in methods of document classification where, for example, the (frequency of) occurrence of each word is used as a feature for training a classifier. It has also been used for computer vision.

In the case of RAKT(the case study) could be used for classifying either the dataset or the input. 

### Advantadges

- Fast, efficient and relativately easy to code.
- You don't need a Neural Network for this algorithm!

### Disadvantadges

- There could be some nuances regarding the appearance of certain words that should be addressed in design.
- The text is acutally not understood by the code. We can make just inferences. 

More references for Bag-of-words

https://en.wikipedia.org/wiki/Bag-of-words_model

https://builtin.com/machine-learning/bag-of-words
