# ppl212-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [PPL212 Homework 4 Solved](https://www.ankitcodinghub.com/product/ppl212-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92024&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;PPL212 Homework 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Part 0: Preliminaries

Structure of a TypeScript Project

Every TypeScript assignment will come with two very important files: • package.json – lists the dependencies of the project.

• tsconfig.json – specifies the TypeScript compiler options.

Before starting to work on your assignment, open a command prompt in your assignment folder and run npm install to install the dependencies.

What happens when you run npm install and the file package.json is present in the folder is the following:

<ol>
<li>npm will download all required modules and their dependencies from the internet into the folder
node_modules.
</li>
<li>A file package-lock.json is created which lists the exact version of all the packages that have been
installed.
</li>
</ol>
What tsconfig.json controls is the way the TypeScript compiler (tsc) analyzes and typechecks the code in this project. We will use for all the assignments the strongest form of type-checking, which is called the “strict” mode of the tsc compiler.

Do not delete or change these files (e.g., install new packages or change compiler options), as we will run your code against our own copy of those files, exactly the way we provide them.

If you change these files, your code may run on your machine but not when we test it, which may lead to a situation where you believe your code is correct, but you would fail to pass compilation when we grade the assignment (which means a grade of zero).

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Testing Your Code

Every TypeScript assignment will have Mocha and Chai as dependencies for testing purposes. In order to run the tests, save your tests in the test directory in a file ending with .test.ts and run npm test from a command prompt. This will activate the execution of the tests you have specified in the test file and report the results of the tests in a very nice format.

An example test file assignmentX.test.ts might look like this: import { expect } from “chai”;

<pre>import { sum } from "../src/assignmentX";
</pre>
<pre>describe("Assignment X", () =&gt; {
  it("sums two numbers", () =&gt; {
</pre>
<pre>    expect(sum(1, 2)).to.equal(3);
  });
</pre>
});

Every function you want to test must be export-ed, for example, in assignmentX.ts, so that it can be

import-ed in the .test.ts file (and by our automatic test script when we grade the assignment). export const sum = (a: number, b: number) =&gt; a + b;

You are given some basic tests in the test directory, just to make sure you are on the right track during the assignment.

What to Submit

You should submit a zip file called &lt;id1&gt;_&lt;id2&gt;.zip which has the following structure: /

<pre>     answers.pdf
     part2
</pre>
src part2.ts

part3 src/*

You will create the file answers.pdf and change the files part2.ts, and the files under part3/src in the places marked by the string TODO. Make sure to to include additional folders and specifically avoid node_modules which can take a lot of space.

Make sure that when you extract the zip (using unzip on Linux), the result is flat, i.e., not inside a folder. This structure is crucial for us to be able to import your code to our tests. Also, make sure the file is a .zip file – not a RAR or TAR or any other compression format.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Part 1: Theoretical Questions

Submit the solution to this part in answers.pdf. We can’t stress this enough: the file has to be a PDF file. 1. Which of the following typing statement is true / false, explain why (5 pts).

(a) {f : [T 1 → T 2], g : [T 1 → T 2], a : T 1} ⊢ (f (g a)) : T 2 (b) {x:T1,y:T2,f :[T2→T1]}⊢(f y):T1

(c) {f : [T1 → T2]} ⊢ (lambda (x) (f x)) : [T1 → T2]

(d) {f : [T 1 ∗ T 2 → T 3]} ⊢ (lambda (x) (f x 100)) : [T 1 → T 3]

2. Perform type inference manually on the following expressions, using the Type Equations method. List all the steps of the procedure (12 pts):

(a) ((lambda (x1) (+ x1 1)) 4)

(b) ((lambda (f1 x1) (f1 x1 1)) 4 +)

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Part 2: Async Fun with TypeScript

Complete the following functions in TypeScript in the file part2/src/part2.ts. You are requested to use generic types where appropriate and provide types as precise as possible (avoid any unless otherwise noted).

Remember that it is crucial you do not remove the export keyword from the code in the given template. Question 2.1

In this question you are requested to use promises and not to use the async keyword! (a) (8 pts)

Write a function makePromisedStore&lt;K, V&gt; that returns an object that simulates a remote key-value store like a database or a web-service.

Since we are not really using a remote store, the actual data is going to be stored using a simple JavaScript Map. The object returned from makePromisedStore has the following type that delegates to the Map object:

<pre>type PromisedStore&lt;K, V&gt; = {
    get(key: K): Promise&lt;V&gt;,
    set(key: K, value: V): Promise&lt;void&gt;,
    delete(key: K): Promise&lt;void&gt;
</pre>
}

For a successful ’get’ the value matching the ’key’ should be resolved. For successful ’set’ and ’delete’ the promise should resolve without any value (just call resolve()).

If a value is missing during ’get’ or ’delete’, you are requested to reject the Promise with the following constant (it exists in the template. Do not create a new one):

export const MISSING_KEY = “___MISSING___” (b) (3 pts)

Write a function, getAll&lt;K, V&gt;, that accepts a promisedStore&lt;K, V&gt; and a list of keys and returns a promise containing a list of the matching values for the store. If a key is missing the promise should reject with the MISSING_KEY constant.

Question 2.2

In this question you are requested to use the async keyword! (Promise is OK only if used as a type, but to not use new Promise(…), Promise.all, Promise.prototype.then, etc.,)

(a)

Write a function asyncMemo that takes another function that has a single parameter and returns a new function that caches any application of the original function using the PromisedStore from the previous question. Any subsequent application with the same parameter will then use the cached result.

That is, the keys stored in the PromisedStore are the parameter values that the original function was called with and the values in the PromisedStore are those values returned when running the original function with the parameter in the key.

Wrappers like asyncMemo can be used, for example, when the target function has some high cost (e.g., it solves a travelling sales men problem) and we want to maintain a persistent ’memo’ in the (asynchronously accessed) local network, which will enable has to re-use that memo in different executions.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
(b)

The type of asyncMemo is

type AsyncMemoType = &lt;T, R&gt;(f: (param: T) =&gt; R) =&gt; (param: T) =&gt; Promise&lt;R&gt; Explain why the wrapped function returns Promise&lt;R&gt; (add to answers.pdf).

Question 2.3

&nbsp;

Write the functions lazyFilter and lazyMap that take a parameter-less generator function and a filter or map callbacks, respectively (you can find the signatures in the template).

These functions then return a new generator function which lazily applies filtering or mapping (respectively) during the iteration. That is, you are requested not to convert the original generator to an array at any point.

Question 2.4

&nbsp;

In this question you can choose whether to use async functions or promises.

Write an async function called asyncWaterfallWithRetry. The function expects an array of async functions as a parameter and runs the functions in sequence, where each function is called with the resolved return value of its predecessor. That is the first, function takes no parameters and any subsequent function has a single parameter that match the resolved return type of its predecessor. To make the typing easier (although not ideal) you can always except at least one input function and you can declare that input functions accept and return type any (except for the first function, which doesn’t have a parameter).

If one of the functions in the list fails (i.e., rejects), then we want to wait 2 seconds using setTimeout and then try again (tip: create a new Promise, and send its resolve as a callback to the setTimeout) . We only retry two times and then re-throw the error if it still happens (that is, we will attempt at most three times to invoke each function). If a function fails three times, asyncWaterfallWithRetry will fail.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Part 3: Type Inference System

In this part, we will work on the Type Inference system studied in class – on the type inference ver- sion https://github.com/bguppl/interpreters/blob/master/src/L5/L5-typeinference.ts. The code attached to this assignment under part3 contains an updated version of the type inference system with additions towards the following goals, which you will complete:

1. CompletethetypeinferencecodeinL5tosupportthemissingASTexpressiontypesprogram, define, quoted literal expressions and set!.

2. Extend the L5 language and type inference code to support the class construct as introduced in Assignment 2.

All modifications with respect to the base system discussed in class are marked with comments of the form // L51. You will complete the places marked by the string TODO.

(3.1) Support Type Inference with Program, Define, Quoted Literal Expressions and Set!

Complement the code in src/part3/src/L51-typeinference.ts so that the type inference system can deal

with the L5 AST nodes of type define, program, literal and set!.

In answers.pdf, write the typing rule for define and set! expressions:

<pre>Typing rule define:
  For every: type environment _Tenv,
</pre>
<pre>           variable _x1
           expressions _e1 and
           type expressions _S1, _U1:
</pre>
<pre>    If   _Tenv ... |- ...
    Then _Tenv |- (define _x1 _e1) : ...
</pre>
Make sure that this typing rule allows type inference of recursive functions.

<pre>Typing rule set!:
  ...
</pre>
You must implement the functions typeofDefine, typeofLit, typeofProgram and typeofSet in file src/part3/src/L51-typeinference.ts.

(3.2) Define the Type of Primitives cons, car, cdr

&nbsp;

Extend the procedure typeofPrim in src/part3/src/L51-typecheck.ts so that the type inference system supports the primitives cons, car and cdr. Use the type expression for PairTExp that has been added in src/part3/src/TExp51.ts.

(3.3) Extend L5 with Class Types

We introduced in Assignment 2 the class construct, with the following syntax: &lt;cexp&gt; ::= …

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
<pre>  | ( class : &lt;TypeName&gt;
      ( &lt;varDecl&gt;+ )
</pre>
<pre>      ( &lt;binding&gt;+ ) ) /
    ClassExp(typeName:String,
</pre>
<pre>             fields:VarDecl[],
             methods:Binding[]))
</pre>
We introduce this construct in L5, and support type annotations in classes as in this example. To make type inference more consistent and support methods with parameters, we change slightly the syntax of class methods from what was done in Assignment 2: given a class value c-value (the return value of the class constructor), and a symbol corresponding to the name of a method method, the application expression (c-value method) always returns a closure. (In Assignment 2, this application was returning the application of the closure.)

<pre>(define pair
  (class : Tpair
</pre>
<pre>    ((a : number)
     (b : number))
</pre>
<pre>    ((first (lambda () : number a))
     (second (lambda () : number b))
     (scale (lambda (k) : pair (pair (* k a) (* k b))))
     (sum (lambda () : number (+ a b))))))
</pre>
<pre>(define (p34 : Tpair) (pair 3 4))
(define f
</pre>
<pre>  (lambda ((x : Tpair))
    (* ((x 'first)) ((x 'second)))))
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
(p34 ‘first)

((p34 ‘first))

((p34 ‘sum))

((p34 ‘scale) 2) ; –&gt; #pair&lt;6,8&gt; (f p34) ; –&gt; 12

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>; --&gt; #&lt;procedure&gt;
; --&gt; 3
; --&gt; 7
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
The evaluation of the class expression returns a class constructor, which takes one parameter for each of the fields in the class definition. In the example above, the pair class constructor has type:

[number * number -&gt; Tpair]

The evaluation of a class constructor returns a class value which has the type defined by the class. In the

example above, the pair value constructor returns a value of type Tpair.

The definition of a class defines a new user defined compound type, which we call a ClassTExp and which is associated to a TVar. In our example we call it Tpair, which can be used in any place a Type Expression (TExpr) is expected (for example, it is used in the declaration of the p34 variable).

Your mission is to extend the type inference system to support user defined class types. You will need to do the following:

<ol>
<li>Extend the parser (in file src/part3/src/L51-ast.ts) to support class constructs. This will be similar to what you saw in Assignment 2 but with the extension of type annotations where appropriate. You must implement the function parseGoodClassExp.</li>
<li>Add to the parser (in file src/part3/src/L51-ast.ts) a function const parsedToClassExps: (p: Parsed) =&gt; ClassExp[];</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
to collect the list of typed names in an AST, so that the type inference system can use the corresponding type definitions. This function must be used in makeTEnvFromClasses in

file src/part3/src/L51-typeinference.ts. This function scans the AST, collects all user defined types, and inserts them in the TEnv that will be used initially when analyzing the AST to infer its type.

<ol start="3">
<li>Read the code and learn how the type expression parser (in file src/part3/src/TExp51.ts) has been extended so that class types can be recognized as type expressions, and unparsed. (You do not have to write code about this, the implementation is provided.)</li>
<li>Extend the type inference system to support class expressions in each of their possible positions:
<ol>
<li>(a) &nbsp;As operator in an application (e.g., (p34 ‘sum)). Applying a class value to anything which is not one of the defined method names is a type error. For example, (p34 ‘x) is a type error. This behavior is implemented in function checkEqualType in L51-typeinference.ts.</li>
<li>(b) &nbsp;As parameter of an application (e.g., (f p34)).</li>
<li>(c) &nbsp;As class value constructor (e.g., (pair 1 2))</li>
<li>(d) &nbsp;As class definition (e.g., (define pair (class …))). The definitions of the methods in the class definition must be type checked, while taking into account the type of the fields of the class.</li>
</ol>
</li>
</ol>
To this end, you must define typing rules that concern class types. In these typing rules, use the following notation:

<pre>// We extend the 2 rules seen in class for application
// with a 3rd rule for the case of class-values as operator:
Typing rule Application:
For every: type environment _Tenv,
</pre>
<pre>           expressions _f, _e1, ..., _en, n &gt;= 0 , and
           type expressions _S1, ..., _Sn, _S, and
           expression _class_value and
           symbols _m1, ..., _mk, k &gt;= 0 and
</pre>
<pre>           type expressions _U1, ..., _Uk
</pre>
<pre>Procedure with parameters (n &gt; 0):
    If   _Tenv |- _f : [_S1 * ... * _Sn -&gt; _S],
</pre>
<pre>         _Tenv |- _e1 : _S1, ..., _Tenv |- _en : _Sn
    Then _Tenv |- (_f _e1 ... _en) : _S
</pre>
<pre>Parameter-less Procedure (n = 0):
    If   _Tenv |- _f : [Empty -&gt; _S]
    Then _Tenv |- (_f) : _S
</pre>
<pre>// New case:
// An expression (class_value 'method) returns a closure
// whose type is defined in the class's type
Class-value Application and (n = 1):
</pre>
<pre>    If   _Tenv |- _class_value : ClassTExp[{_mi, _Ui} i = 1..k],
         _Tenv |- _e1 = _mi
</pre>
<pre>    Then _Tenv |- (_class_value _e1) : _Ui
</pre>
<pre>// A class expression returns a class-value constructor
Typing rule ClassExp:
For every: type environment _Tenv,
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
<pre>variables _x1, ..., _xn, n &gt;= 0
           symbols _m1, ..., _mk, k &gt;= 0
           procedure expressions _p1, ..., _pk and
           symbol _ct and
</pre>
<pre>           type expressions _S1, ...,_Sn, _U1, ...,_Uk :
</pre>
<pre>    If   _Tenv o {_x1:_S1, ..., _xn:_Sn } |- _pi:_Ui for all i = 1..k ,
    Then _Tenv |- (class : _ct ( _x1 ... _xn ) ((_m1 _p1) ... (_mk _pk))) :
</pre>
<pre>                    [_S1 * ... * _Sn -&gt; _ct]
                  _ct : ClassTExp(_ct, (_m1 : _p1) ... (_mk : _pk))
</pre>
You must implement the function typeofClass in file src/part3/src/L51-typeinference.ts to implement the typing rule.

Good Luck and Have Fun!

</div>
</div>
</div>
