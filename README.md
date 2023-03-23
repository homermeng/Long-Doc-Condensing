# Long-Doc-Condensing
This code will take a long PDF doc as input and condense the file semantically into shorter texts.

The code contains the following functions:

1. read PDF file and covert it into pages of images;
2. corp the images to remove irrelevant header and footer information;
3. OCR the images into text and concat all pages of text together;
4. split the content into semantically meaningful chunks;
5. for each chunk, call GPT-3.5-turbo API to condense/summarize the chunk into fewer texts together with the previously condensed text;
6. the resulting text is a very dense summary for the input long document.

####
Use this code at your own risks.
All rights reserved.
Fansheng Meng
homer.fansheng.meng@gmail.com
####
