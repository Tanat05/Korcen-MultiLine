<div align="center">
  <h1>Korcen-MultiLine</h1>
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

# 6. Technologies Used

This project anticipates utilizing a range of technologies, including but not limited to:

- **Programming Languages:** Python
- **Machine Learning Concepts/Fields:**
  - Natural Language Processing (NLP)
  - Conversational AI
- **Model Architectures/Techniques:**
  - Transformer-based models
  - Sequence-to-Sequence (Seq2Seq) models
- **Example Models/Frameworks:**
  - BERT, GPT (or similar Large Language Models)
  - TensorFlow, PyTorch (as potential development frameworks)

# 7. Getting Started

This project is currently in the conceptual phase. The following provides a general outline of how one might get started once the project is further developed.

### Prerequisites

- Python 3.x installed.
- Familiarity with Natural Language Processing (NLP) concepts and machine learning.
- Access to computational resources for training deep learning models (if planning to train).

### Installation

1. Clone the repository (once publicly available):
   ```bash
   git clone https://github.com/your-username/Korcen-MultiLine.git
   cd Korcen-MultiLine
   ```
2. Installation will depend on the specific frameworks chosen (e.g., TensorFlow, PyTorch). Typically, this would involve installing dependencies from a `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```
   (Note: `requirements.txt` will be provided in future development stages.)

### Running a Conceptual Demo

Once the model is developed and trained:

- **API Interaction:** The model might be exposed via an API endpoint. Users would send conversational text (e.g., a series of utterances) to the API and receive a profanity analysis, potentially including context-based flags.
- **Command-Line Interface (CLI):** A CLI tool could be developed for testing or batch processing. For example:
  ```bash
  python detect_profanity.py --conversation_file path/to/conversation.txt
  ```
- **Integration:** The core logic would be designed for integration into larger platforms or services requiring profanity detection.

Detailed instructions and example code will be provided as the project progresses.

# 8. Contributing

We welcome contributions to Korcen-MultiLine! As the project is currently in its conceptual stages, contributions can range from ideas and suggestions to early-stage development once the groundwork is laid.

### Reporting Bugs or Suggesting Features

If you encounter any bugs (though less likely at this conceptual stage) or have ideas for features and improvements, please open an issue on the GitHub repository. Provide as much detail as possible for bugs, and clear justifications for feature suggestions.

### How to Contribute Code

Once development begins, we will follow a standard fork-and-pull-request workflow:

1. **Fork the Repository:** Create your own fork of the main Korcen-MultiLine repository.
2. **Create a Branch:** For any new feature or bug fix, create a new branch in your forked repository (e.g., `git checkout -b feature/your-feature-name` or `bugfix/issue-number`).
3. **Make Your Changes:** Implement your feature or fix the bug.
4. **Test Your Changes:** (Details on testing procedures will be provided as the project matures. For now, ensure your changes are well-tested conceptually or with any available early tools.)
5. **Commit Your Changes:** Write clear and concise commit messages.
6. **Push to Your Fork:** Push your changes to your forked repository.
7. **Submit a Pull Request:** Open a pull request from your branch to the main Korcen-MultiLine repository. Clearly describe the changes you have made and why.

### Coding Standards

As the project evolves, we will define specific coding standards. For now, please aim for clean, readable, and well-commented code, consistent with common Python best practices.

We appreciate your interest in contributing to making online environments safer and more respectful!

# 9. License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
