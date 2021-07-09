<h1>Steps of execution and work</h1>
<p>
<ul>
    <li>Importing libraries</li>
     <li>Testing data</li>
     <li>Data cleaning  : lower case , eliminating ponctuation</li>
    <ul>Tokenization : tokenizing by word , tokenizing by sentence , <li>The sent_tokenize() splite the text into sentences :

    - 'perhaps one of the most significant advances made by arabic mathematics began at this time with the work of al-khwarizmi, namely the beginnings of algebra.'
    - 'it is important to understand just how significant this new idea was.'
Same Thing In Arabic Text :</li>
    </ul>
     <li>Filtering Stop Words</li> <li>Lemmatizing
A lemma is a word that represents a whole group of words, and that group of words is called a lexeme.</li>
     <li>
Chunking
While tokenizing allows you to identify words and sentences, chunking allows you to identify phrases.</li>
    
</ul>
</p>
<h1>Text processing using spacy</h1>
<img src="https://www.tertiarycourses.com.gh/media/catalog/product/cache/3/image/512x/040ec09b1e35df139433887a97daa66f/n/l/nlp-python-spacy_1.jpg"
     alt="spacy" width="600" height="400">
<p>spaCy is a free and open-source library for Natural Language Processing (NLP) in Python with a lot of in-built capabilities. It’s becoming increasingly popular for processing and analyzing data in NLP. Unstructured textual data is produced at a large scale, and it’s important to process and derive insights from unstructured data. To do that, you need to represent the data in a format that can be understood by computers. NLP can help you do that.</p>

<h1>Text processing using NLTK</h1>
<img src="https://www.datacorner.fr/wp-content/uploads/2020/08/nltk.png"
     alt="NLTK" width="600" height="400">
<p>
Natural language processing (NLP) is a field that focuses on making natural human language usable by computer programs. NLTK, or Natural Language Toolkit, is a Python package that you can use for NLP.

A lot of the data that you could be analyzing is unstructured data and contains human-readable text. Before you can analyze that data programmatically, it's composed of :
Find text to analyze
Preprocess your text for analysis
Analyze your tex
Create visualizations based on your analysis
</p>

<h1>Text processing using hugging face</h1>
<img src="https://1.bp.blogspot.com/-qQryqABhdhA/XcC3lJupTKI/AAAAAAAAAzA/MOYu3P_DFRsmNkpjD9j813_SOugPgoBLACLcBGAsYHQ/s1600/h1.png"
     alt="hugging face" width="600" height="400">
<p>
Hugging Face is an NLP-focused startup with a large open-source community, in particular around the Transformers library. 🤗/Transformers is a python-based library that exposes an API to use many well-known transformer architectures, such as BERT, RoBERTa, GPT-2 or DistilBERT, that obtain state-of-the-art results on a variety of NLP tasks like text classification, information extraction, question answering, and text generation. Those architectures come pre-trained with several sets of weights. Getting started with Transformers only requires to install the pip package:


pip install transformers

The library has seen super-fast growth in PyTorch and has recently been ported to TensorFlow 2.0, offering an API that now works with Keras’ fit API, TensorFlow Extended, and TPUs 👏. This blog post is dedicated to the use of the Transformers library using TensorFlow: using the Keras API as well as the TensorFlow TPUStrategy to fine-tune a State-of-The-Art Transformer model.
</p>


