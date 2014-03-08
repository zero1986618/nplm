neural probabilistic language model toolkit based on http://nlg.isi.edu/software/nplm/ with following extensions:

1. Remove depdency with other python scripts

2. Support word class

3. Support topic layer

4. Support weighted training

For example:

nplm --train_text_file train-text-file --train_text_weight_file train-text-weight --validation_text_file validation-text-file

nplm --train_text_file train-text-file --train_topics_file train.topics-file --validation_topics_file validation.topics-file --num_topics 20 --validation_text_file validation-text-file

If you have any question, feel free to ask me(yinggong.zhao@gmail.com)

Yinggong ZHAO
Nanjing University.
