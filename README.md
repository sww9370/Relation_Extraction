# Relation Extraction
This project do relation extraction work by Convolutional Neural Network <br>
The tool we used is Tensorflow <br>

### This project includes: <br>
1. pre-processing python file of ACE data, SemEval data and Chinese data<br>
2. python file for relation extraction by CNN architecture <br>

### File intorduction: <br>
preprocess_ace/:
    preceprocess_ace.py -- main function to extraction structure data from ace and save it as embedding form <br>
    c_xml_parse.py -- class for parse xml <br>
    c_ace_process.py -- classes for ACE Data process, includes definition of data structure, and parse function <br>
    c_relation.py -- class for turning relation mention into embedding <br>
    c_open_tool.py -- class for other tool, includes load position matrix and word matrix and so on. <br>

### Other: <br>
the relation mention we extracted from raw data is the form as follow: <br>
<e1>Ivan</e1> in <e2>Wisconsin</e2>	PHYS	Located <br>
entity are tagged followed by relation tag <br>



