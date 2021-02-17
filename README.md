# SimDocSin

SimDocSin is a cross-lingual document similarity checking tool for Sinhala and English.

This system can be used to find similar documents or parts of documents of Sinhala (English) language to a given document of English (Sinhala) language. System consists of two parts.
##### Full Matching

Here an user can submit a source document to get any matching complete document that exists in the system database in target language. Here the user has to set 3 input fields. <br> 
<ul>* Input language - Language of the source document. It can be Sinhala or English.</ul><br>
<ul>* Similarity level - This indicates how much similarity you expect from a similar pair output by system. The user can give a value within the range from 1 to 5. Low value means there is a high chance of getting a similar document but the similarity can be relatively low while high value means that system can output a document with a relatively high similarity but the chance of getting a result is low.</ul> <br>
<ul>* Source file - Source document given as the input. It can be submitted as either a file or a text.</ul><br>

##### Partial Matching

Here an user can submit a source document to get any matching partials of documents that exist in the system database in target language. Here also the user has to set the 3 inputs fields mentioned in the previous section. Apart from those there is another input field called Min Length. <br> <ul> * Min Length - minimum number of sentences the user expected to have in a document partial. It can be 1, greater than 1, greater than 2, greater than 5 or greater than 10.</ul>

## How to Deploy SimDocSin

### Install Dependencies
You will need python 3.x. You can build the enviornment as follows.<br>
```pip install -r requirements.txt```<br>

### Create Neccessary Folder

### Create Index Files

### Run SimDocSin
```flask run```

### Contributors
Udhan Isuranga (udhanisuranga.16@cse.mrt.ac.lk) <br>
Janaka Sandaruwan (janakasadaruwan.16@cse.mrt.ac.lk) <br>
Udesh Athukorala (udeshathukorala.16@cse.mrt.ac.lk) <br>
