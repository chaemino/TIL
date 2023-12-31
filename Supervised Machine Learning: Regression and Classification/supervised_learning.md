# Supervised Learning

Supervised Learning, refers to algorithms that learn x to y or input to output mappings.  
**Learns from being given right answers**.  
=> The learning algorithm eventually learns to take just the input alone without the output label and gives a resonably
accurate prediction or guess of the output.

- Example

|input |output | application|
|--|--|--|
| email | spam? (0/1) | spam filtering |
|audio |text transcripts | speech recognition |
| English | Spanish | machine translation |

In all of these applications,
you will first train your model with examples of inputs x and right answers,
that is the labels y.  

After the model has learned from these input, output, or x and y pairs, they can then take
a brand new input x, something it has never seen before,
and try to produce the appropriate corresponding output y.

- regression algorithms
  - which is a type of supervised learning algorithm learns to predict numbers out of infinitely many possible numbers.

- classification
  - predict categories.
  - <img width="604" alt="image" src="https://github.com/chaemino/TIL/assets/107089629/96a4394a-2255-4afe-b04f-7c7390fc0031">
  - the learning algorithm has to decide how to fit a boundary line through these data.

|regression | classification |
|--|--|
| predict numbers from infinitely many possible output numbers. | make a prediction of a category. |
