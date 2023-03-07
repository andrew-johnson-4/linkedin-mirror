# Covariance vs Contravariance in Type Theory

In type theory, covariance and contravariance refer to how subtyping relationships are applied to different types in different contexts. 
Under covariance, subtyping relations are maintained directly. Under contravariance, subtyping relations are reversed.

For example, variables are normally considered covariant with their types. 
Any variable that is an Integer will also be a Number, when an Integer is a subtype of Number.

By contrast, functions are typically covariant with their outputs and contravariant with their inputs. 
Any function that returns an Integer can also be viewed as a function that returns a Number. 
Any function that expects an Integer, however, must be given an Integer, not just any Number.
