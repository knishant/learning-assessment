# Samples

### choice

* Choice interaction with one answer
* Shuffle allowed
* Html for question
* See the use of match_correct response processing template

### choice_fixed

* Same as before
* Last option of None of the above is fixed, even when shuffle allowed

### choice_aria

* Much more complex html rendering

### choice_multiple

* Multiple answers allowed
* See the use of **map_response** response processing template
* Mapping section

### inline_choice

* inlineChoiceInteraction
* may be rendered as an inline drop down.

### feedback_adaptive

* feedback shown inline
* multiple attempts allowed
* this is probably what we want
* note adaptive is set to true at assessmentItem level

### adaptive

* adaptive sample with feedbacks

### hint

* endAttemptInteraction to show hints
* good example like feedback_adaptive

### match

* match two sets
* two sets need not be equal in size
* hence matchMax can be set to limit cardinality

### figure

* figure and figcaption elements

### svg

* embed svg

### audio-video

* links to audio and video

### math

* use of math ml

### order

* orderInteraction
* order the list

### multi-input

* multiple interactions in one question
* lang set at question level

### likert

* 5 like ratings from disagree to agree
* no scoring or matching of result

### text_entry

* textEntryInteraction
* fill in the blank

### essay

* extendedTextInteraction for submitting large text
* externalScored = human

### gap_match

* gapMatchInteraction
* fill in the blanks with listed words, ie match gaps to words

### select_point

* selectPointInteraction
* choose a point in graphic (say of map)
* answer can be mentioned as a circle with some radius around the exact point

### slider

* sliderInteraction
* score based on closeness to the right answer

### template

* use of template and variables
