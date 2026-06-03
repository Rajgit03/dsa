#Reverse a string: &quot;this is my book&quot; expected output: &quot;book my is this&quot;
text="this is my book"
print(text)
words=text.split()
print(words)
reversewords=words[::-1]
result=' '.join(reversewords)
print(result)
