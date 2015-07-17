# Bioinformatics-using-Python
Bioinformatics Programming Using Python(Mitchell L Model)
Table of Contents
1. Primitives . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
Simple Values 1
Booleans 2
Integers 2
Floats 3
Strings 4
Expressions 5
Numeric Operators 5
Logical Operations 7
String Operations 9
Calls 12
Compound Expressions 16
Tips, Traps, and Tracebacks 18
Tips 18
Traps 20
Tracebacks 20
2. Names, Functions, and Modules . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
Assigning Names 23
Defining Functions 24
Function Parameters 27
Comments and Documentation 28
Assertions 30
Default Parameter Values 32
Using Modules 34
Importing 34
Python Files 38
Tips, Traps, and Tracebacks 40
Tips 40
Traps 45
Tracebacks 46
3. Collections . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 47
Sets 48
Sequences 51
Strings, Bytes, and Bytearrays 53
Ranges 60
Tuples 61
Lists 62
Mappings 66
Dictionaries 67
Streams 72
Files 73
Generators 78
Collection-Related Expression Features 79
Comprehensions 79
Functional Parameters 89
Tips, Traps, and Tracebacks 94
Tips 94
Traps 96
Tracebacks 97
4. Control Statements . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 99
Conditionals 101
Loops 104
Simple Loop Examples 105
Initialization of Loop Values 106
Looping Forever 107
Loops with Guard Conditions 109
Iterations 111
Iteration Statements 111
Kinds of Iterations 113
Exception Handlers 134
Python Errors 136
Exception Handling Statements 138
Raising Exceptions 141
Extended Examples 143
Extracting Information from an HTML File 143
The Grand Unified Bioinformatics File Parser 146
Parsing GenBank Files 148
Translating RNA Sequences 151
Constructing a Table from a Text File 155
Tips, Traps, and Tracebacks 160
Tips 160
Traps 162
Tracebacks 163
5. Classes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 165
Defining Classes 166
Instance Attributes 168
Class Attributes 179
Class and Method Relationships 186
Decomposition 186
Inheritance 194
Tips, Traps, and Tracebacks 205
Tips 205
Traps 207
Tracebacks 208
6. Utilities . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 209
System Environment 209
Dates and Times: datetime 209
System Information 212
Command-Line Utilities 217
Communications 223
The Filesystem 226
Operating System Interface: os 226
Manipulating Paths: os.path 229
Filename Expansion: fnmatch and glob 232
Shell Utilities: shutil 234
Comparing Files and Directories 235
Working with Text 238
Formatting Blocks of Text: textwrap 238
String Utilities: string 240
Comma- and Tab-Separated Formats: csv 241
String-Based Reading and Writing: io 242
Persistent Storage 243
Persistent Text: dbm 243
Persistent Objects: pickle 247
Keyed Persistent Object Storage: shelve 248
Debugging Tools 249
Tips, Traps, and Tracebacks 253
Tips 253
Traps 254
Tracebacks 255
7. Pattern Matching . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 257
Fundamental Syntax 258
Fixed-Length Matching 259
Variable-Length Matching 262
Greedy Versus Nongreedy Matching 263
Grouping and Disjunction 264
The Actions of the re Module 265
Functions 265
Flags 266
Methods 268
Results of re Functions and Methods 269
Match Object Fields 269
Match Object Methods 269
Putting It All Together: Examples 270
Some Quick Examples 270
Extracting Descriptions from Sequence Files 272
Extracting Entries From Sequence Files 274
Tips, Traps, and Tracebacks 283
Tips 283
Traps 284
Tracebacks 285
8. Structured Text . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 287
HTML 287
Simple HTML Processing 289
Structured HTML Processing 297
XML 300
The Nature of XML 300
An XML File for a Complete Genome 302
The ElementTree Module 303
Event-Based Processing 310
expat 317
Tips, Traps, and Tracebacks 322
Tips 322
Traps 323
Tracebacks 323
9. Web Programming . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 325
Manipulating URLs: urllib.parse 325
Disassembling URLs 326
Assembling URLs 327
Opening Web Pages: webbrowser 328
Module Functions 328
Constructing and Submitting Queries 329
Constructing and Viewing an HTML Page 330
Web Clients 331
Making the URLs in a Response Absolute 332
Constructing an HTML Page of Extracted Links 333
Downloading a Web Page’s Linked Files 334
Web Servers 337
Sockets and Servers 337
CGI 343
Simple Web Applications 348
Tips, Traps, and Tracebacks 354
Tips 355
Traps 357
Tracebacks 358
10. Relational Databases . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 359
Representation in Relational Databases 360
Database Tables 360
A Restriction Enzyme Database 365
Using Relational Data 370
SQL Basics 371
SQL Queries 380
Querying the Database from a Web Page 392
Tips, Traps, and Tracebacks 395
Tips 395
Traps 398
Tracebacks 398
11. Structured Graphics . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 399
Introduction to Graphics Programming 399
Concepts 400
GUI Toolkits 404
Structured Graphics with tkinter 406
tkinter Fundamentals 406
Examples 411
Structured Graphics with SVG 431
SVG File Contents 432
Examples 436
Tips, Traps, and Tracebacks 444
Tips 444
Traps 445
Tracebacks 447
A. Python Language Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 449
B. Collection Type Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 459
ndex . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 473
