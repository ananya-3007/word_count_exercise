# word_count_exercise
text_variable='The dog barked wagging and wagging  and barked at the passing cars, its tail wagging and wagging with excitement as it ran around in circles, barking and barking again, hoping someone would stop and play, but the cars just kept driving by, driving by without a second glance.' 
count=0
word_split=text_variable.split()
for i in word_split:
    if 'wagging'==i:
        count=count+1
print('The word count is :',count)
