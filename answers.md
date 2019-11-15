# How does it respond to: 
# My mother and I talked last night. 
Tell me more about your family.

# I said no! 
Why so negative?

# The weather is nice.
You don't say

# Do you know my brother
Why so negative?

#Statements & Response
S: Joe Swanson
R: Joe Swanson from Family 

S: Nathan 
R: I know of a Nathan Harris he likes a cup of joe.

S: video game
R: What games do you like?

#What happens when more than one keyword appears in a string? Consider the string "My mother has a dog but no cat." Explain how to prioritize reponses in the reply method.

It reads the first keyword and instantly returns the response labled under mother because it's first. You put the first keyword you want first so that it prints out the response you want.

# What happens when a keyword is included in another word? Consider statements like "I know all the state capitals" and "I like the vegatbales smothered in cheese." Explain the problem with the responses to these statements. 
When a keyword is used in any of these statements then it'll print out the words like know even though that's a word itself the code reads the no in the word giving out the response "Why so negative?". It's an issue because it reads what it finds first and returns the responses. 