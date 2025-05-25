<div align="center">
  <h1>Korcen-MultiLine</h1>
</div>

![131_20220604170616](https://user-images.githubusercontent.com/85154556/171998341-9a7439c8-122f-4a9f-beb6-0e0b3aad05ed.png)

Here's the project description in English, in Markdown format:

Project Description: Enhancing Profanity Detection AI Model through Conversation Context Understanding
# 1. Project Overview

This project aims to overcome the limitations of existing single-sentence-based profanity detection AI models by developing a next-generation AI model that more accurately detects profanity through a deep understanding of conversation flow and context. Our goal is to significantly lower misclassification rates, precisely grasp user intent, and thereby foster a healthier and more pleasant service environment.

# 2. The Problem

Existing profanity detection AI models suffer from the following limitations:

- Limitations of Single-Sentence Analysis: They rely on keyword matching or pattern recognition at the sentence level, failing to consider the overall conversation context or relationships with previous utterances.

- High Error Rates:

  - False Positives: Occur when a non-profane word is misclassified as profanity simply because it contains certain keywords (e.g., 'Damn, I lost it' where 'Damn' is misclassified as profanity).

  - False Negatives: Occur when metaphorical, figurative, or subtly used profanity spanning multiple sentences, or sarcastic expressions, are not detected (e.g., sarcastic remarks like "That's truly amazing. Is that the best method?").

- Inability to Grasp User Intent: Beyond simply classifying profanity, these models struggle to understand user emotions or intentions.

- User Dissatisfaction and Decreased Service Trust: Frequent misclassifications lead to user frustration and erode trust in the service.

# 3. The Solution

We will address these problems by building an AI model that understands the flow and context of conversations.

- Context-Aware Detection:

  - Beyond simple keyword matching or individual sentence analysis, the model will comprehensively consider relationships with previous utterances, the overall tone of the conversation, and the speaker's intent to determine profanity.

  - To achieve this, we will explore and apply Transformer-based Sequence-to-Sequence (Seq2Seq) models or model architectures specialized for conversational AI (e.g., leveraging the conversational processing capabilities of large language models like BERT, GPT).

- Multi-turn Conversation Processing: The model will take the entire conversation history as input to understand the pre- and post-context of profanity and clarify why a specific utterance is considered profane.

- Refined Dataset Construction: We will perform high-quality labeling that reflects context, based on diverse forms of profane and non-profane conversational data collected from real service environments.

- Continuous Learning and Updates: The model will be continuously trained and updated to adapt quickly to changing language environments, even with the emergence of new slang, neologisms, or sarcastic expressions.

# 4. Key Features and Improvements

- Context-Aware Detection: Significantly reduces false positive/negative rates by understanding conversation flow.

- Detection of Nuanced Expressions: Improves the ability to detect subtle profanity, including sarcasm, metaphorical profanity, and neologisms specific to certain groups.

- Revolutionary Reduction in Error Rates: Minimizes False Positive and False Negative rates compared to existing single-sentence models.

- Enhanced User Intent Analysis: Expands the possibility of providing insights into the speaker's emotions and intentions, beyond mere profanity classification.

- Aim for Explainable AI (XAI): Explores the possibility of implementing a feature to provide information on the basis for profanity classification (e.g., which part of the conversation is considered profane in context).

# 5. Expected Outcomes

- Maximized Profanity Detection Accuracy: Strengthens the reliability and professionalism of AI-powered services.

- Creation of a Pleasant and Safe Service Environment: Enhances user satisfaction and fosters a healthy community culture.

- Increased Operational Efficiency: Reduces the burden of manual review and dispute resolution, saving operational resources.

- Improved User Experience: Addresses dissatisfaction and inconvenience caused by misclassifications.

- Strengthened Service Trust: Enhances brand image through a predictable and fair profanity detection system.

Copyright© All rights reserved.
