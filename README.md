# Abstract2Title T5 Model Fine-tuning

![Colab Banner](colab_banner.png)

This repository is dedicated to fine-tuning the T5 model for the specific task of generating titles for given abstracts. It's a powerful tool for automatic summarization and content generation.

## 📂 Repository Contents

This repository consists of the following components:

- **Google Colab Notebook:** An interactive Colab notebook that guides you through the fine-tuning process. It's designed to make the process as smooth as possible.

- **Dataset:** The dataset used for fine-tuning, provided in both training and testing sets in CSV format. This dataset forms the basis for training and evaluation.

- **Python file:** This repo also contains the Python file of the Notebook to run this on local machine with virtual environment. If you want to run this on local machine then you have to install some dependencies in your virtual environment. 

<script src="https://cdnjs.cloudflare.com/ajax/libs/clipboard.js/2.0.8/clipboard.min.js">

```bash
pip install transformers
<button class="copy-button" data-clipboard-text="pip install transformers">Copy</button>

go
Copy code

```bash
pip install sentencepiece
<button class="copy-button" data-clipboard-text="pip install sentencepiece">Copy</button>

go
Copy code

```bash
pip install shutil
<button class="copy-button" data-clipboard-text="pip install shutil">Copy</button>

go
Copy code

```bash
pip install nltk
<button class="copy-button" data-clipboard-text="pip install nltk">Copy</button>

go
Copy code

```bash
pip install os
<button class="copy-button" data-clipboard-text="pip install os">Copy</button>

php
Copy code
</script>
<script>
  var copyButtons = new ClipboardJS('.copy-button');

  copyButtons.on('success', function(e) {
    e.clearSelection();
    alert('Command copied to clipboard: ' + e.text);
  });
</script>



## 🚀 Getting Started

To fine-tune the T5 model using this repository and the provided dataset, follow these steps:

1. **Open the Google Colab Notebook:** Click the "Open in Colab" button at the top of the README. This will open the Colab notebook in your web browser.

2. **Run the Notebook:** Follow the instructions provided within the Colab notebook. It will guide you through the steps of fine-tuning the T5 model.

Happy fine-tuning and text generation!

![Colab](colab.png)
