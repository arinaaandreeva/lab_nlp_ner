# lab_nlp_ner
Named Entities Recognition task
## Dataset
 https://huggingface.co/datasets/just-ai/jayguard-ner-benchmark

 ## Model
 Архив с моделью [https://drive.google.com/file/d/1DgNWpafFfmbgnO-kWNoSbH4vKShsU4OU/view?usp=sharing ](https://drive.google.com/file/d/1DgNWpafFfmbgnO-kWNoSbH4vKShsU4OU/view?usp=sharing)

 ! unzip -d ./bert-ner-model ./bert-ner-model.zip
   model = AutoModelForTokenClassification.from_pretrained("./final-ner-model")

   
 
