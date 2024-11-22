Dataset

The dataset used in this project consists of Bengali text sequences that represent the structure, semantics, and patterns of the Bengali language. The data was preprocessed and tokenized into sequences to serve as input for training a Generative Adversarial Network (GAN).

The dataset contains text extracted from a range of sources to reflect diverse contexts, ensuring a rich variety of input for text generation. Given the challenges of working with low-resource languages, this project demonstrates how GANs can help augment Bengali text data.

Objective

Natural Language Processing (NLP) tasks, especially in low-resource languages like Bengali, face significant challenges due to the limited availability of high-quality datasets.

The main objective of this project is to:

   1. Generate synthetic Bengali text using GANs.

   2. Validate the effectiveness of GANs for augmenting text data in low-resource languages.
      
   3. Demonstrate a proof of concept to showcase the feasibility of applying GANs to text data augmentation.

Key sub-objectives include:

   . Designing and training a GAN architecture (Generator + Discriminator) tailored for text generation.
	 
   . Preprocessing Bengali text data for tokenization and sequence modeling.
   
   . Generating new text sequences that mimic the linguistic patterns of the original data.
   
   . Evaluating the quality of generated text.

Outline
   
The following steps were undertaken to complete the project:

  1. Import and Preprocess the Data
     
     . Tokenize the Bengali text dataset.
     
     . Create input sequences for the GAN model.
     
     . Split the data into training and evaluation sets.

  2. Model Design
     
     . Generator: A sequence generator model designed using LSTM layers to learn patterns in Bengali text.
     
     . Discriminator: A binary classifier designed to distinguish between real and generated text sequences.
     
     . GAN: A combined model where the generator learns to fool the discriminator.
     
  3. Model Training
     
     . Train the GAN with alternating updates to the generator and discriminator.
     
     . Use an adversarial loss function to improve the quality of generated sequences over time.
     
     . Perform hyperparameter tuning for optimization.

  4. Generated Text Output
     
     . Evaluate the generator's ability to produce high-quality synthetic text.
     
     . Save generated text sequences to a .txt file for analysis.

Generated Text Examples

চাহিছে। আয়– টানি ঘনায়ে বুক। কালীকে। ‍সে অসহ– পাইয়াছ খেলারই করিবে ভাই। গেঁথেছিলেম ঝরনাতলায় কম্পিছে সুরনর অবসাদে। দেহদুর্গে মায়া-তান পাবনা
নেহারো হদয়কোণে॥ দ্বিতীয়া হদয়কোণে॥ ষে। পরিচয়॥ রাগরাগিণীতে পরিচয়॥ পাখিটি সঞ্চয়। মাঝ-কিনারায় নাগিনী। বিনি জাগিয়াছে হলে দাঁড়ালেন মিলনদিনের বদ্ধ জ্বলবে॥ প
আসিল জল– জল– জল– খেলায়– খুঁজি॥ 

This model proves that GANs can generate text data in Bengali. Even if the generated text might not be perfect due to limited epochs or a simplified architecture, the core concept is validated. As the model works, it can be extended by adding more sophisticated models and techniques.
