 **Fundamental concepts** 
 
1. Characteristic of algorithms. 

  An algorithm is a series of steps or instructions that need to be executed in a certain order to get the desired output and complete a task.  It must have these characteristics:
     - *Unambiguous.* Algorithm should be clear and unambiguous.
     - *Input.* To have 0 or more well-defined inputs.
     - *Output.* It should have 1 or more well-defined outputs, and should match the desired output. 
     - *Finiteness.* Must finish after a finite number of steps. Feasibility. To be feasible with the available resources.
     - *Independent.* That has step-by-step directions, which should be independent of any programming code.
    
   [link](https://www.tutorialspoint.com/data_structures_algorithms/algorithms_basics.htm "Heading link")
   
  **Algorithm representation**
  1. Control structures in the design and construction of an algorithm
- Selective structures. Refers to a line-by-line execution of code statements (one line after another).
- Repetitive structures. Are used for looping, repeating a piece of code multiple times in a row. E.g.
while
do/while
for
- Nested structures. Are used for decisions, choosing between 2 or more alternative paths. E.g. In C++ 
if
if/else
switch

   [link](https://www.cs.fsu.edu/~myers/c++/notes/control1.html)
 
 2. Types of algorithm representation:
- Graph: Flow chart. Is a graphic representation of a stepwise process, showing the steps with figures ordered and connected with arrows. 
- Written: Pseudocode. Is a simple way of describing a set of instructions that does not have to use specific syntax.

  [link](https://www.bbc.co.uk/bitesize/guides/zpp49j6/revision/2)
  
 **Data types and expressions** 
  
1. Types of computational data
- Numeric. Is the use of software that combines symbolic and numeric methods to solve problems.   [link](https://en.wikipedia.org/wiki/Symbolic-numeric_computation)
- Logic. Computational logic is the use of computers to establish facts in a logical formalism. Is concerned with formal logic, where it is frequently applied to solve problems related to computation.   [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5832843/)
- String and characters. A _string data_ type is traditionally a sequence of characters, either as a literal constant or as some kind of variable. Is often implemented as an array data structure of bytes (or words) that stores a sequence of elements, typically characters, using some character encoding. 
The _character data_ type represents individual or single characters. They include a variety of symbols such as the alphabet the numeral digits, punctuation, etc.  [link](https://press.rebus.community/programmingfundamentals/chapter/string-data-type/)
- Arrangements. It is used in computational geometry to present lines and figures in planes.  [link](http://www.ams.sunysb.edu/~jsbm/courses/345/13/lecture-arrangements-duality.pdf)

2. Representation of computational data
- Variables. Are data values that can change when the user is asked a question, during program execution. A variable is a memory location, it has a name that is associated with that location and is used to hold data.
- Constants. These values that stay the same every time a program is executed, constants are not expected to change. Named constants are values where a name is defined to be used instead of a literal constant.

  [link](https://www.bbc.co.uk/bitesize/guides/zc6s4wx/revision/5)
  
3. Types of computational operations
- Operators: Are typographical symbols that mean something special and tells it to do something with the literals or variables next to it.
    - Arithmetic. These are used to perform mathematical calculations (addition, multiplication, division, etc.)
    - Logic. They connect two or more expressions such that the value of the compound expression produced depends only on that of the original expressions and on the meaning of the operator. (AND, OR, or NOT).
    
     [link](https://www.cdc.gov/epiinfo/user-guide/functions-and-operators/operators.html)
    
- Relationships Operands: Are operators that tests or define some kind of relation between two entities. These include numerical equality (e.g.5=5) and inequalities (e.g.4≥3).  Often used to create a test expression that controls program flow. 
     - Variables. They store/remember information and manipulate it. Simple variables typically store some value input by the user, or some value calculated by the program from user-inputs. When a program runs, the values in some of its variables change: thus, the value stored in a variable can vary as the program runs.
    
     [link](https://press.rebus.community/programmingfundamentals/chapter/relational-operators/)
    
-Constants Expressions: These expression contain only constants. Can be evaluated during compilation rather than at run time, and can be used in any place that a constant can occur. Each constant expression must evaluate to a constant that is in the range of representable values for its type.
      - Arithmetic. An arithmetic constant expression has an arithmetic type and contains only operands that are integer constants, floating constants, enumeration constants, character constants, or sizeof expressions. 
      - Logic. Are the expressions selected to indicate the logical form of a sentence. A sentence will play a proper role in inference in virtue of a structure that can be exhibited by means of these expressions. The basic logical constants include expressions for the truth functions &, ∨, →, 0 and ¬, the quantifiers (∃) and (∀), and the identity relation=. 

   [link](https://www.oxfordreference.com/view/10.1093/oi/authority.20110803100112574)    [link](https://www.cs.auckland.ac.nz/references/unix/digital/AQTLTBTE/DOCU_066.HTM)
