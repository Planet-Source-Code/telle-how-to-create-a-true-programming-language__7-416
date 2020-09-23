<div align="center">

## How To Create A True Programming Language


</div>

### Description

Explains how to create a programming language..not a scripting language
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[telle](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/telle.md)
**Level**          |Beginner
**User Rating**    |2.3 (21 globes from 9 users)
**Compatibility**  |Delphi 5, Delphi 4, Pre Delphi 4
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__7-1.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/telle-how-to-create-a-true-programming-language__7-416/archive/master.zip)





### Source Code

<HTML><FONT COLOR="#004080" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10><B>How To Create A Programming Language</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"></B><BR>
<BR>
</FONT><FONT COLOR="#0080ff" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">In this tutorial i will explain everything needed to make a true<BR>
programming language, not a scripting language, although i will <BR>
explain some on that, but there isnt much point...</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#0080ff" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">Okay, i know many people who have always wanted to make a programming<BR>
language(mainly me...), but a lot could never figure out how to make <BR>
a true language, the truth is, its hard, very hard, not because you<BR>
have to make it in C++, because thats a lie, it can be created in<BR>
almost any language, mainly a language will the ability to replace<BR>
and do some other basic commands, a true language like c++ or delphi,<BR>
compiles it's code to assembly, a machine spacific chip, anyway,<BR>
the langauge is just a way to make things easier, assembly is not<BR>
the easiest thing to learn, it usally takes many,anywhere like,<BR>
10 to 100,000 programers, who mainly only know assembly, the truth is<BR>
you must convert a unique language syntax, to assembly, or, you could<BR>
simply convert it to a language that can already be compiled to asm,<BR>
example, say you made a language called SBL(Simple Basic Language), <BR>
and your basic hello world program looked like this:</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL.Program: HelloWorld.SBL<BR>
SBL.Vars: Str<BR>
SBL.SetVar: Str,Hello World<BR>
SBL.Body: { SBL.OutPut(Str) }<BR>
SBL.EndProgram</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#0080ff" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">alright, now say, you want to be lazy, and convert it to c++<BR>
and let it compile it, thats fine, doesnt make you anyless of<BR>
a programmer...you would have todo this</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#0080ff" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL Version:</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL.Program: HelloWorld.SBL<BR>
SBL.Vars: Str<BR>
SBL.SetVar: Str,Hello World<BR>
SBL.Body: { SBL.OutPut(Str) }<BR>
SBL.EndProgram</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#0080ff" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">C++ Version:</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">#include &lt;iostream.h&gt;<BR>
<BR>
int main()<BR>
char Str;<BR>
Str = "Hello World";<BR>
{<BR>
cout &lt;&lt; Str;<BR>
return;<BR>
}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#0080ff" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">Now...the hard part would be translating the SBL version to the C++ version<BR>
you would have to first, create a temp file like HelloWorld.Cpp<BR>
then translate it like this:<BR>
Line-By-Line:</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL.Program: HelloWorld.SBL </FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">{this simply tells you the file name, so you really dont need it, just delete the line,}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL.Vars: Str</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">{hum...ok...you can do 2 things here, create the c++ var like:<BR>
char Str;<BR>
or, you turn it into a string right then and there}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL.SetVar: Str,Hello World</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">{ok..if you applyed the first method, then you use this, else, you directly do it<BR>
Str = "Hello World";<BR>
please note: i dont know much c++ anymore, so dont be offended if its wrong, anyway<BR>
well, now you have 2 lines translated...<BR>
char Str;</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">Str = "Hello World";</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">ok...}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL.Body { SBL.OutPut(Str) }</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">{ok, by now you get my point, this is transformed to:</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">{<BR>
cout &lt;&lt; Str;<BR>
Return 0;<BR>
}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">or whatever function you use,<BR>
<BR>
now you have one line left:}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#ff0000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">SBL.EndProgram</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">{this basicly was Return 0;...but oh well}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
<BR>
</FONT><FONT COLOR="#008000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">{ok so by now youve made a file from HelloWorld.SBL to HelloWorld.Cpp<BR>
youve translated the code...but you havnt found all the required header files<BR>
...so you basicly scan all the functions used and compare it to a reference,<BR>
(which just tells which function belongs to which header file)... well, now<BR>
you have the translated segments, the header segments, and a file called HelloWorld.Cpp}</FONT><FONT COLOR="#000000" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0"><BR>
</FONT><FONT COLOR="#0080ff" BACK="#ffffff" style="BACKGROUND-COLOR: #ffffff" SIZE=2 PTSIZE=10 FAMILY="SANSSERIF" FACE="Arial" LANG="0">...now what? well first you combine the segments, then save the resulting code to <BR>
HelloWorld.Cpp, then compile the file to a .OBJ...then you link it to an EXE...<BR>
then you can now delete HelloWorld.Cpp, HelloWorld.Obj, which leaves you with<BR>
HelloWorld.SBL and HelloWorld.EXE...and there you have it, an explaination on<BR>
how to create a true programming language...now for scripting languages...<BR>
you see them all over psc, vb world, delphi world, c++ world, well they are<BR>
by far a lot easier to make, like youll see, its just an interpreter slapped with source code<BR>
to interpret...thats your job, im not explaining it...this is my 12 minute tutorial. thank you<BR>
for reading it and please vote and leave comments!<BR>
<BR>
<BR>
</FONT></HTML>

