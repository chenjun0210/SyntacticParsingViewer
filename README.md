# SyntacticParsingViewer
A Tool to view or edit syntactic parsing results

There are two .html files in this project.

TagParse.html:
  -You can open this file in your browser (Chrome recommended)
  -Then input a syntaictic parsing result in the top TextInput (the format of the parsing result string should be consistent with the result from BerkerleyParser, an example will be given below).
  -Click outside this TextInput, then the tree will appear.
  -You can input the ID of a node in corresponding TextInput, then click outside, the content of that node (if exists) will be shown in the TextInput below.
  -Try various operations on the tree to change its content or structure.
  -Once you changed the tree, the Sencond TextInput (which is closely next to the TextInput where you input your syntactic parsing result) will show the corresponding string format of syntactic parsing result of the current tree.
  
  
ViewParse.html:
 -You can copy more than one syntactic parsing reault into the TextArea, each line stands for one syntactic tree.
 -Then click outside the textarea, the first line of what you input will be show at the bottom of the page.
 -"Prev" and "Next" buttons can be used to switch among different syntactic trees.

An Syntactic Tree Input Example:
( (IP (NP (DP (DT 该)) (NP (NN 山地))) (VP (VV 位于) (NP (NN 天山山脉)))) )
 
中文说明（懒得看上面可以看这里，简述一下）：
TagParse.html可以通过多种才做改变你已有的句法树结构，并自动生成新的树结构对应的句法结构字符串
ViewParse.html可以查看句法结构字符串的可视化树结构，可以一次输入多行，每行对应一个句法树，初始显示第一句。
输入的句法树结构应该和BerkelParser的输出形式完全一致。
  
