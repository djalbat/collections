# Collections

Collections for [Occam](https://occam.science).

Collections encompass the notion of membership but preclude the notions of intersection and union.
Most mathematicsal objects requie the notion of membership but the notiions of intersection and union are either non-sensical or, if they do make sense, constrained.
Having a `Collections` type with an `element` property together with the `∈` relation means that mathematical objects such as groups can inherit both the property and the relation without the encumberance of other class-theoretic notions.

This package also defines the transitive membership, which leads to the Russian Doll Axiom:

```
∀C ¬(C ∈⁺ C)
```

Note that a trivial corollary of this axiom is non-reflexivity, namely no collection can be an element of itself, which does not have to be stated separately.

Again, having a common base type means that this can be applied more generally across combinattions of mathematical objects that require membership.

## Contact

* https://djalbat.com

