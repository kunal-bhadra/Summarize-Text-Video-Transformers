
# Summarizing YouTube Transcripts & Blog Posts

Here, I have summarized YouTube Video Transcripts & Blog posts with SOTA models. The Video Summarization was done through the **facebook/bart-large-cnn** model from HuggingFace Transformers. With the **sshleifer/distilbart-cnn** model, we fetched and scraped a blog post to return its summary to the user. Lastly, the latest **Pegasus** model from Google was also run to generate an Abstractive summary of the text from the corpus given, which can generate text from its own & doesn't use the text from the corpus! All these approaches use current technologies in Text Summarization applying recent breakthroughs.

  
## 🚀 The Result

Extractive Summary models *(Bart)* was able to reduce the size of the text corpus to 20-30%, while still retaining the meaning of the corpus. The Abstractive Summary model *(Pegasus)* often returned only a couple of sentences even after providing a giant corpus.
 

## ✏ Tech Stack for Project Development

- Python
- 🤗 Transformers
- Youtube Transcript API
- BeautifulSoup
- Tensorflow
- PyTorch

  
## 🧠 Approach taken

 1. YouTube Video Transcription & Summarisation with the **facebook/bart-large-cnn** model.
 2. Blog Post Summarization with the default **sshleifer/distilbart-cnn** model from HuggingFace library.
 3. Abstractive Summary of a text corpus with the latest **Pegasus** model from Google.

  

## 🔗 Connect with me:
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.polywork.com/kunal_bhadra)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kunal-bhadra-cs/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/kunal_kaun)

  
