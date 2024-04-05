# Fine-tuning Language Models with UnSloth and Custom Data on Google Colab

This repository hosts a modified version of the original UnSloth library code, tailored for fine-tuning any Hugging Face language model (LLM) with custom data. This adaptation facilitates the utilization of custom datasets in JSONL format stored on Google Drive, providing an accessible and efficient approach to model fine-tuning directly within Google Colab environments.

## Features

- **Google Colab Integration**: Designed for seamless execution in Google Colab, leveraging its computational resources and pre-installed libraries.
- **Custom Data Training**: Enables fine-tuning with datasets in JSONL format from Google Drive.
- **UnSloth Library Enhancements**: Incorporates modifications to the original UnSloth codebase for improved performance and usability.
- **Hugging Face Model Compatibility**: Supports fine-tuning of any LLM available on Hugging Face.

## Prerequisites

- A Google Account for access to Google Colab and Google Drive.
- A dataset formatted in JSONL stored within your Google Drive.

## Quick Start

To begin fine-tuning your language model with custom data:

1. Access the [CustomLMFineTuning.ipynb](https://github.com/Den-Sec/CustomLMFineTuning/blob/main/CustomLMFineTuning.ipynb) notebook from the repository, or directly  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PCwOXxfVRyekEx6LbHn08kqTD25Ph3U2?usp=sharing)
3. Follow the step-by-step instructions within the notebook. These will guide you through setting up your environment, including mounting your Google Drive to access your dataset and executing the fine-tuning process.
4. Adjust any configurations as necessary to tailor the fine-tuning to your specific model and dataset requirements.

## Contributing

Contributions are highly appreciated and help make this project even better. If you're interested in contributing:

1. Fork this repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Acknowledgements

- [Original UnSloth Library](https://github.com/unsloth-docs) - For the foundational codebase.
- [Hugging Face](https://huggingface.co/) - For their extensive library of language models.
- [Google Colab](https://colab.research.google.com/) - For providing a flexible and powerful environment for machine learning projects.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
