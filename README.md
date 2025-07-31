<div align="center">
  <h1>Korcen-MultiLine (Under development)</h1>
</div>

![131_20220604170616](https://user-images.githubusercontent.com/85154556/171998341-9a7439c8-122f-4a9f-beb6-0e0b3aad05ed.png)

# 1. Project Overview

This project aims to overcome the limitations of existing single-sentence-based profanity detection AI models by developing an advanced AI model that more accurately detects profanity through a deep understanding of conversation flow and context. Our goal is to significantly lower misclassification rates, precisely grasp user intent, and thereby foster a healthier and more pleasant service environment.

# 2. The Problem

Existing profanity detection AI models suffer from the following limitations:

- Single-Sentence Analysis Limitations: Current models analyze sentences in isolation using keyword matching or pattern recognition, neglecting broader conversational context and inter-sentence relationships.

- High Error Rates:

  - False Positives: Non-profane words are misclassified as profanity due to keyword presence (e.g., 'Damn' in 'Damn, I lost it').

  - False Negatives: Metaphorical, figurative, subtle multi-sentence profanity, or sarcastic expressions often go undetected (e.g., "That's truly amazing. Is that the best method?").

- Inability to Grasp User Intent: Models struggle to understand user emotions or intentions beyond basic profanity classification.

- User Dissatisfaction and Decreased Service Trust: Frequent misclassifications frustrate users and erode service trust.

# 3. The Solution

Our solution involves an AI model that comprehends conversational flow and context.

- Context-Aware Detection:

  - The model will determine profanity by analyzing inter-sentence relationships, conversational tone, and speaker intent, moving beyond keyword matching or isolated sentence analysis.

  - This will be achieved by exploring and applying Transformer-based Sequence-to-Sequence (Seq2Seq) models or architectures specialized for conversational AI (e.g., leveraging large language models like BERT, GPT).

- Multi-turn Conversation Processing: The model will analyze full conversation histories to understand profanity context and the reasoning behind classifications.

- Refined Dataset Construction: High-quality, context-aware labeling will be performed on diverse conversational data from real service environments.

- Continuous Learning and Updates: The model will be continuously trained and updated to adapt to evolving language, including new slang, neologisms, and sarcastic expressions.

# 4. Key Features and Improvements

- Context-Aware Detection: Significantly reduces false positive/negative rates by understanding conversation flow.

- Detection of Nuanced Expressions: Improves the ability to detect subtle profanity, including sarcasm, metaphorical profanity, and neologisms specific to certain groups.

- Significant Reduction in Error Rates: Minimizes False Positive and False Negative rates compared to existing single-sentence models.

- Enhanced User Intent Analysis: Expands the possibility of providing insights into the speaker's emotions and intentions, beyond mere profanity classification.

- Aim for Explainable AI (XAI): Explores the possibility of implementing a feature to provide information on the basis for profanity classification (e.g., which part of the conversation is considered profane in context).

# 5. Expected Outcomes

- Improved Profanity Detection Accuracy: Strengthens the reliability and professionalism of AI-powered services.

- Creation of a Pleasant and Safe Service Environment: Enhances user satisfaction and fosters a healthy community culture.

- Increased Operational Efficiency: Reduces the burden of manual review and dispute resolution, saving operational resources.

- Improved User Experience: Addresses dissatisfaction and inconvenience caused by misclassifications.

- Strengthened Service Trust: Enhances brand image through a predictable and fair profanity detection system.

# 9. License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
