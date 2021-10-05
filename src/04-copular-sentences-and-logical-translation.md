In this chapter, one shall finally learn how to say something in Eberban. We shall consider only the simplest type of sentence here -- copular sentences. One will also learn personal pronouns of class MI. 

Copular sentences in English are of the form "X is Y", such as "This is an apple," or "I am happy". 

Eberban does not have a copula particle like in English, being that it has no distinction between verbs, nouns and adjectives formally. Certain words are used very similarly to how verbs, nouns and adjectives are used in English, yes, but underneath, the grammar is all the same -- they are all predicates. Let us consider the sentence "This is an apple" again. One could define "this" and "apple" thusly:

`` gloss
this: P is this.
apple: P is an apple.
``

And then construct the sentence like so:

`` gloss
this is an apple: P is this, and P is an apple
``

One could actually break down virtually all English sentences like this. Here is another, more complex example.

`` gloss
I go to the market.
I: P is me.
go: P goes to Q.
market: Q is the market.
P is me, and P goes to Q, and Q is the market.
``

This is the core of Eberban grammar. All root words are predicates. To ensure that it will be understood, we will have an exercise in the middle of the lesson.

### Decomposition of English sentences
Decompose the following sentences into the Eberban predicate style, similar to what is shown above.

<spoiler>
I look at you.
	
`` gloss
I: P is me.
look: P looks at Q.
you: Q is you.
P is me, and P looks at Q, and Q is you.
``
</spoiler>

<spoiler>
Someone eats an apple.
	
`` gloss
someone: P is someone.
eats: P eats Q.
apple: Q is an apple.
P is someone, and P eats Q, and Q is an apple.
``
</spoiler>

<spoiler>
I go from the mall to the office.
	
``
I: P is me.
go: P goes from Q to R.
mall: Q is the mall.
office: R is the office.
P is me, and P goes from Q, and Q is the mall, to R, and R is the office.
(Alt:) P is me, and P goes from Q to R, and Q is the mall, and R is the office.
``
</spoiler>

<spoiler>
I am sad.
	
``
I: P is me.
sad: P is sad.
P is me, and P is sad.
``
</spoiler>

Eberban treats **existential variables** as "first-class citizens" -- they are the linchpin from which all other grammar derives. Given that Eberban is a logical language, it makes sense that sentences should be easy to translate into formal logic. Specifically, Eberban uses second-order logic. When one says **mei menoe**, one is actually saying

`` gloss
mei menoe
Ex: mei(x), menoe(x)
There exists X such that X is something near the speaker and X is an apple.
``

Reciprocally, when one says **mei menoe**, one is not only saying "There is something near (the speaker) that is an apple," but also "There is an apple that is near (the speaker)".


