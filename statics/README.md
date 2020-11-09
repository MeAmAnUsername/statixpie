Ad-hoc Documentation

Lexical and semantic types have sorts `Type` and `TYPE` respectively.
Lexical types end in `Ty`, semantic types end in `Type`.
All functions only take the semantic types, the only place where syntactic
types are used is when they come in from the AST.
They are converted using `typeOfType`.
