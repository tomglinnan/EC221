# EC221 Class Resources

Welcome! This is where I'll post any bonus resources for EC221 (MT and LT) for the classes that I teach

Please email me if you have any questions!
Link to the [course moodle](https://moodle.lse.ac.uk/course/view.php?id=4816)

* **MT week 2:** [Slides](MT2.pdf) on an introduction to the course and on Stata
* **MT week 4:** [Some short OVB notes](Quick OVB Notes.pdf), in case I went through the chain rule analogy too fast!
* **MT week 6:** Two extra things this week
	* [A note on Robust Standard Errors](Robust SEs.pdf) - a few people were asking me about how these work, but unfortunately nearly all material online explains them using matrices. This note goes through what they are, why (and when) we should use them, and also shows how they're computed in a simple case (which doesn't require matrices). Remember: this material isn't examinable in MT, and we'll get back to it all properly in LT!
	* [A note on Interaction Effects](Interaction Effects.pdf) - people sometimes have problems with this the first time they see it, so I've added in my explanation of how they work and why we should care about them (to supplement Lecture 15)
* **MT week 7:** [Exam Tips](Exam Tips.pdf) - some of my thoughts on how to revise for the MT exam, where to get resources, and what might help in transitioning back to in-person exams
* **MT week 8:** [Controls Tutorial](https://ftp.cs.ucla.edu/pub/stat_ser/r493.pdf) - a more complete tutorial on good on bad controls, written for computer scientists. Importantly, you'll see in the appendix that everything is rigorously defined. Be aware of different notation used: eg saying Y_i \| do(X=1) instead of Y_1i
* **MT week 9:** [Controls in Two-Step Procedures](Controls_in_Two_Step_Procedures.pdf) - a short note on the intuition of why we control for things, especially why have to include controls **consistently** to find the coefficients in the OVB formula, and to do 2SLS correctly




* **Random (Maybe) Interesting Resources:** This is a list of things you might be interested in if you really like EC221 so far, and want to learn more about metrics and how it works
	* [ML Book](http://ema.cri-info.cm/wp-content/uploads/2019/07/2019BurkovTheHundred-pageMachineLearning.pdf) - we spent a lot of time talking about the difference between causal and correlation questions, and in EC221's MT we focus entirely on causal questions. These are most of the questions economists care about, but sometimes we have a reason to just want really accurate prediction. This is where the (fancily-named) field of **machine learning** comes in: it's all about doing prediction really well, not caring at all about causality. As you might know, this is used by companies all over the place (such as by Netflix to predict which shows you'll want to watch, not caring _why_ you want to watch specific shows). This book is probably the best non-technical introduction to ML I've seen: very short and very readable. One word of warning: as ML was developed by computer scientists, they have different language for many of the things which we do (eg they say _features_ while we say _covariates_ or _regressors_), but you'll see they start at a similar place to us (OLS!). Much of the work I do in my research is adapting ML methods to Economics
	* Search Google for _Mostly Harmless Econometrics_ (first link) - one of the most famous textbooks in applied metrics (like the MT of EC221), meant for PhD students. Written by Josh Angrist and Steve Pischke, this textbook is partly responsible for the revolution in Economics towards caring about causality and data (rather than pure theory) which just won the Nobel prize. Though it's PhD level, it's not way beyond EC221's MT if you are very comfortable with statistics and matrices, and it definitely won't be beyond you by the end of the LT! Might be interesting if you want to look deeper at any of the methods (especially the quasi-random methods near the end of the MT). The undergrad version of this textbook (mastering metrics) is set at the MT level itsel




* **Bonus Teaching Resources:** These were written by me for previous courses I've taught - one in LSE Life, and another run by the LSE Economics society
	1. [Point of Stats](Point of Stats.pdf) - this is a presentation which talks about hypothesis testing, how it's applied to OLS, and what estimation _is_. Might be helpful if you want to see how many of the tools learnt in the first half of MT fit together (though as I explain, this is all about analysing correlation instead of causation)
	2. [Testing](q4q.pdf) - this is a short pdf walking through what hypothesis testing is, intended for those who've never studied statistics before. It might be helpful if you're stuck on this specific topic, as people often are

More coming soon!