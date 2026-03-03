### Siamese Neural Networks

I first came across SNNs during a deep learning for computer vision course class. I initially just brushed them off as models generating latent space representations of two features and calculating the distances between them. I am glad to report that this misconception of mine was cleared quite quickly thanks to yann lecunn's work on forgery detection in signatures using time delay siamese neural networks (I keep forgetting how legendary this guy is). 

Link to the paper is - [Signature Verification using a "Siamese"
Time Delay Neural Network](https://papers.neurips.cc/paper_files/paper/1993/file/288cc0ff022877bd3df94bc9360b9c5d-Paper.pdf) 

Some rough unorganized thoughts - 
https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf

https://www.researchgate.net/publication/4156225_Learning_a_similarity_metric_discriminatively_with_application_to_face_verification

vector embeddings distance between two images
loved how innovatively leCun was able to think about considering time as a feature in the signatures rather than just having the final sign

still a little bit confused as to why we dont use a single model for vector embeddings kinda
how does the loss function work

more applications of SNNs

meaning of Siamese here

different loss functions we can use 