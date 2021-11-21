### JLox

 Implementing a language with java following the "Crafting Interpreters" book

 running the ast generator

 ```shell
// Compiling & generating AST classes
 cd src
javac ./com/craftinginterpreters/tool/GenerateAst.java
java com.craftinginterpreters.tool.GenerateAst ./com/craftinginterpreters/lox
 ```


 Ideas after completing the book
 - recursive lang
 - >> pipe functions (heavyly inspired by elixir's |>)
 - monadic by default? all functions might or not return values?
 - dynamically typed
 - branchless??
 - Rust as background lang??
 - high order functions
 - c/ruby flavor?
 - polymorphic

2 >> + 1 >> - 10
expands to 1 + 2 - 10

params >> validate >> create >> render

list >> process

pipe process(list)
 process(list, 0)
end

pipe process(list, index) {
  length list eq index and return 0 or process list index++
}

