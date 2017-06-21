# WordTree

### Simple API for comparing hyper and hypon difference between two words

   - [Use BaseHTTPServer](#WordTreeByBaseHTTP.py)
     - WordTreeByBaseHTTP.py
   - [Use Flask](#WordTreeByFlask.py)
     - WordTreeByFlask.py
    
    
### Example
  - hypernyms are the synsets that are more general
    [127.0.0.1:8080/hyper?word1=banana&word2=apple](#output/banana.n.02_vs_apple.n.01_hyper_.png)

  - hyponyms are the synsets that are more specific
    [127.0.0.1:8080/hyper?word1=banana&word2=apple](#output/banana.n.02_vs_apple.n.01_hypon_.png)


#### Reference:
http://www.dh2012.uni-hamburg.de/conference/programme/abstracts/automatic-topic-hierarchy-generation-using-wordnet.1.html


