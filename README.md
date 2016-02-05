# Taxonomy Import

This module provides a mechanism to create taxonomy vocabularies from text files. Very useful when making large vocabularies.

To import a vocabulary, you will go to admin/config/system and select Taxonomy Import. This will give you a form where you can enter the name of the taxonomy, a description, a file name, and whether you want to handle duplicates.

The filename can be a simple filename like IowaCounties.txt, in which case it looks for the file inside the files folder. Or, you can give it the full path, such as /tmp/IowaCounties.txt, and it will try to use that file.

The format of the text file is simply one term per line.
