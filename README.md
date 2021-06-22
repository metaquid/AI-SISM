# AI-SISM
Artificial Intelligence, Sentiment Interface Score Mechanism.

Meta code

the AI SISM calculation mechanism is very simple
there is the sentiment value of the current sentence
there is a list of all the previous values which are added together
the list of values is not compacted into a simple sum to get a total
the list of values is preserved because it represents a sequence of emotional states during a dialogue 

the value in the foreground exists, the one relative to the current sentence
there is also the background value, that given by the sum of the previous foreground values 



NOTE: see the LE-AI code for implementation in PHP of expert.ai API
