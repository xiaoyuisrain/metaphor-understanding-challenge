# Prompts used in the experiments
## Paraphrase judgement
### Word judgement: Implicit
#### CTWT52

```
Choose the word(s) that can replace the highlighted word in the given sentence without changing the meaning of the sentence.
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### SWTC20

```
Select words that can replace the highlighted word in the given sentence without altering the sentence's meaning.
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### WOTG20

```
Which of the given options can replace the highlighted word in the given sentence without altering the sentence's meaning?
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

### Word judgement: M-sent
#### CTWT23

```
Choose the word(s) that can replace the highlighted word in the given metaphorical sentence without changing the meaning of the sentence.
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### SWTC03

```
Select words that can replace the highlighted word in the given metaphorical sentence without altering the sentence's meaning.
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### WOTG03

```
Which of the given options can replace the highlighted word in the given metaphorical sentence without altering the sentence's meaning?
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

### Word judgement: M-word
#### CTWT33

```
Choose the word(s) that can replace the highlighted metaphorically used word in the given sentence without changing the meaning of the sentence.
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### SWTC33

```
Select words that can replace the highlighted metaphorically used word in the given sentence without altering the sentence's meaning.
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### WOTG33

```
Which of the given options can replace the highlighted metaphorically used word in the given sentence without altering the sentence's meaning?
Sentence: {original_sentence}
Option A: {substitution_a}
Option B: {substitution_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

### Sentence judgement: Implicit
#### CTCP10

```
Choose the correct paraphrase(s) for the given sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### SSTP10

```
Select sentences that paraphrase the given sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### SSTA94

```
Select sentences that are semantically equivalent to the following sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

### Sentence judgement: M-sent
#### CTCP13

```
Choose the correct paraphrase(s) for the given metaphorical sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### SSTP13

```
Select sentences that paraphrase the given metaphorical sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### SSTA93

```
Select sentences that are semantically equivalent to the following metaphorical sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

### Sentence judgement: M-word
#### YAGA10

```
You are given a sentence where the highlighted word is metaphorically used. Choose the correct paraphrase(s) for the given sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### GASW55

```
Given a sentence where the highlighted word is metaphorically used, select sentences that paraphrase this sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```

#### GASW94

```
Given a sentence where the highlighted word is metaphorically used, select sentences that are semantically equivalent to this sentence.
Sentence: {original_sentence}
Option A: {paraphrase_a}
Option B: {paraphrase_b}
Option C: Both Option A and Option B
Option D: Neither Option A nor Option B
Correct answer: Option
```


## Paraphrase generation
### PTGS54

```
Paraphrase the given sentence by substituting the highlighted word with another word. The substitution should be a single word.
Sentence: {original_sentence}
Paraphrase: {tw_replaced_by_blank}
[blank] should be "
```

### UASW92

```
Use a single word to replace the highlighted word in the given sentence, so that the new sentence and the given sentence mean the same thing.
Sentence: {original_sentence}
New sentence: {tw_replaced_by_blank}
[blank] should be "
```

### GASW45

```
Given a sentence with a highlighted word, replace this word with a different word to make a paraphrase.
Sentence: {original_sentence}
Paraphrase: {tw_replaced_by_blank}
[blank] should be "
```

