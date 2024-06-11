# Obfuscation-and-Deobfuscation-Approaches-Tools-and-Datasets

This thesis proposes an investigation into code obfuscation and deobfuscation.

The student is expected to produce a guide to the tools used for obfuscation and deobfuscation for a given language (e.g., JavaScript), public datasets, and the main methodologies employed in this field.

Deobfuscation, in particular, will be analyzed in detail, examining traditional methodologies and potential novel methods (e.g., those based on neural networks).

The student is expected to deliver an overview of the state-of-the-art in code obfuscation and deobfuscation, as well as datasets that can be used to develop novel techniques in this field.


## Thesis work has produced the following *Main Results*:

  * *Guide* that brings together the state-of-the-art regarding code obfuscation and deobfuscation.
  The first part of the thesis focuses on identifying existing and accessible tools, techniques and methodologies for obfuscating and deobfuscating JavaScript functions. The results of the search are then transcribed and organized in the guide. 
  
  * *Tools Table.*
  The guide is then summarized in the tools table, where tools are listed on the left with their names and useful links, and then for each tool, the techniques and methodologies used are listed on the right. Tools are divided into those for obfuscation and those for deobfuscation, then they are divided again between open source and non open source. Furthermore, under each table, for every tool, techniques and methodologies used are briefly explained.
  
  * *Bash Script.*
  The command line interface that can be used on Bash to obfuscate or deobfuscate code via each downloaded tool was identified among its files and information. Tried each tool on one or two JavaScript functions to see how it worked. Then created some Bash Scripts to automate the process of obfuscating, deobfuscating and executing the 100(0) original JavaScript functions.
  The resulting Bash Script and other useful information and instructions were then collected in the Bash Script document.
  
  * *Dataset.*
  Researched and collected in the "original code functions" folder a total of 100(0) JavaScript functions to obfuscate, deobfuscate, compare and then analyze results.
  Identified among the tools that can be downloaded and used locally on a VirtualBox virtual machine with Ubuntu 22.04.3 LTS: for obfuscation: obfuscator.io; for deobfuscation: relative.im , js-beautify , deobfuscate.io (version for obfuscator.io, called obf-io.deobfuscate.io, which also works for ByteHide) and then used manual obfuscation via the website of: ByteHide.
  Used the first four tools via Bash Scripting and collected the results in their respective folders: "obfuscated code functions": obfuscator.io, ByteHide ; "deobfuscated code functions": relative.im: obfuscator.io, ByteHide and js-beautify: obfuscator.io, ByteHide and obf-io.deobfuscate.io: obfuscator.io, ByteHide.
  
  * *Comparison and Analysis.*
  Initially, a comparison of the results was carried out without tools. Through the information in the tools table and two open notepads with the two codes, these were analyzed by identifying in the lines which techniques and methodologies had been used depending on the tool involved and its description in the tools table, then similarities and differences were highlighted and commented in the dedicated document.
  The next step was to look for tools to compare and analyse the results obtained; three tools were identified: two bash commands: diff and sdiff and a GUI tool called kompare, furthermore diff was also used with the -q option. After comparing the codes, using the tools, the results were saved and organized in the "comparison and analysis" document.
  The pairs compared are: original code with the obfuscated one, obfuscated code with the deobfuscated one, deobfuscated code with the original one.

The search for information on the state-of-the-art in code obfuscation and deobfuscation led to the creation of the first 3 documents mentioned above, which then led to the creation of the dataset. The files collected in the dataset will in turn lead to the creation of potential novel methods and techniques, such as neural networks that learn and improve through the datasets. The latter document, based on the results collected in the dataset, could instead lead to the improvement or creation of new methods, techniques and tools for obfuscation and deobfuscation.


### dataset_webtools.zip

- dataset_webtools
  - dataset_sample_js
    - original_code_functions
    - obfuscated_code_functions
      - obfuscator.io
      - ByteHide
    - deobfuscated_code_functions
      - relative.im
        - obfuscator.io
        - ByteHide
      - js-beautify
        - obfuscator.io
        - ByteHide
      - obf-io.deobfuscate.io
        - obfuscator.io
        - ByteHide
  - web_tools_obf_deobf
    - obfuscated_code
      - obfuscator.io
      - javascriptobfuscator.com
      - javascriptobfuscator
      - CodeBeautify
      - CleanCSS
    - deobfuscated_code
      - CodeAmaze
        - obfuscator.io
        - ByteHide
      - deobfuscate.io
        - obfuscator.io
        - ByteHide
      - js-beautify
        - obfuscator.io
        - ByteHide
      - obf-io.deobfuscate.io
        - obfuscator.io
        - ByteHide
      - relative.im
        - obfuscator.io
        - ByteHide
      - Unminify
        - obfuscator.io
        - ByteHide


