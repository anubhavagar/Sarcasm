# Sarcasm
Quickstart using Colab
Try this using Google Colab Notebook for a quick preview. You can run all cells without any modifications after following below steps:
1.In order to easily load our fine-tuned model, we should save it in a specific way, i.e. the same way the default BERT models are saved. Here is how you can do that.
2.Put Test.tsv inside Data Directory.
3.Go into the output directory where the fine tuned models will be saved. There, you should find 3 files; bert_config.json, pytorch_model.bin, vocab.txt.
4.Archive the two files config.json, and pytorch_model.bin into a .tar file.
5.Compress the .tar file into gzip format. Now the file should be something like Sarcasm1.tar.gz
6.Run sarcasmevaluation.py with Google Colab Notebook
