# Course Notes - Lesson 1

### Structured Data
Structured data is comprised of clearly defined data types whose pattern makes them easily searchable. It conforms to a tabular format with relationship between the different rows and columns.

**Examples**
1. Multidimensional Arrays (Matrices)
2. Tabular and spread-sheet data where each column may be a different type(string, numeric, data or otherwise).
3. Multiple tables of data interrelated by key columns 
4. Evenly and unevenly spaced time series
Possible to transform data sets into a structured form e.g. converting news articles into a word frequency table

### Scripting Languages 
: Programming language for a special run-time environment that automates the execution of task; used to write quick-and-dirty small programs (scripts).

### Libraries
- numPy
- pandas
- matplotlib
- Ipython
- SciPy

**Misc Notes**
- Python code will run substantially slower than code written in a compiled language like Java or C++
- Python is not an ideal language for highly concurrent, multithreaded applications, particularly applications with many CPU-bound threads. The reason for this is that it has
what is known as the global interpreter lock (GIL), a mechanism which prevents the
interpreter from executing more than one Python bytecode instruction at a time. 
