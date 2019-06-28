# Lessons Learned:

link to KevinBird blog about the same: http://kevinbird15.com/2019/06/11/Haha-2019-Lessons-Learned.html

Lessons: 
* You learn a lot when pushed by a competition.  You are critical of your process and you look into all the details to extract and edge.
* The community is a huge help. Put your code out there, people give feedback and want to assist you and help you out.  You get lots of suggestions when you have an example out there.
* Writing up your results and consolidating your code gives you ideas about what makes sense to try/do next and to improve on your model.  When I moved the code into a clean repo and started to document what I had done, I realized I had missed the fine-tuning stage. 
* GIT is your friend.  I came to love it and to use it to see what I had changed/used at each stage of the competition and then revert back to points where things had run better in my final results.  It really did help me to stay organized during development. 
* Pre-training and transfer learning is a big deal - it works and is worth your time to figure it out in NLP.  You can embed a lot of information in the network with pre-training.  The winner used pre-trained BERT which is a huge amount of information embedded into the model. 
* Controlling the random seed and using it as a hyper-parameter.  Great idea/suggestion.  It really did help me to stay sane and have results that I could replicate when I wanted to go back and re-build a model.  I set the random seed and got the exact same results. 
