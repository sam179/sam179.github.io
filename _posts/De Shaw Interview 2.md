---
layout: post
title: DE Shaw Interview, Round 2
---
De Shaw Interview 2:

So a much more stable start this time. No more blabbering. Thank God the guy waited till I got the link.

The question of wanting to leave current company after one year. Told the need to work at an organisation with higher standards of work. Need to mention another point: a stable system. This is something people might relate to.

Then we started on. First came the coding question. Got to say, the question this time was much better than or probably because of my own strenghts and weaknesses seemed decently harder than the first round. For a data strucutre that stores simple integrs, I was asked to optimise 5 operations, insert, search, delete, MinDelete, MaxDelete. All of them can be done O(log N), using heaps or BST. First priority was to upgrade, Min and Max to O(1), which I promptly did using two pointers on a doubly linked list. This was kind of a breakthrough. Post this point the question was not a mountain to climb. Then he wanted me to upgrade search and delete. Using a hash table in conjunction, I did this too. Objective was complete.

Some info about current work. Told him about catalog and stuff. He enquired about batching and expiry. Gave him a brief info about what the idea is.

Then suddenly he sprang up a question designing a trading platform. Now here is the weird part. This was neither a complete system question, nor a complete OOPS entity question. He wanted to work on a fine line between both. After a lot of hassle, I presented a system that he seemed to atleast be satisfied with. But what I really feel is that he wanted me to use RabbitMq messaging system explicitly, this was probably the biggest disadvantage with today's interview, as rewarding as this round was it never a good idea to want to hear few keywords for the interview. Post this a portfolio trading extension was asked to develop. This solution was shaky at best. But in this part he put up a concurrency condition which should never have been put. He wanted to see if I could handle it. I questioned the relevance of condition in the first place. He acknowledged his mistake and seemed to be somewhat impressed. Although I might be reading too much in the moment here.


Now came the DB part. Now I flunked in this part. I didn't know how to normalize. I was asked about indexes. After giving a "I don't know shit about DB indexes" disclaimer, I somewhat recovered and answered him some basics about DB indexes and their functions. Then I was asked a much simpler question. He wanted me to identify primary and foriegn keys in three interdependent tables. I felt that this was a question for a DB noob. Thankfully, I was able to get all the primary keys correctly. Now foriegn keys were a toss up. I admitted that I didn't fully understand the repercussions of adding a foriegn key. He asked the result of deleting some dependent foriegn keys. I could not get it as I didn't fucking know foriegn keys. He told me that. This fucking company and their fucking obsession with databases man I tell you. But boy do they take a balanced round of interview. So this interview was not good either. There is a faint optimism because of last time, but I must prepare for all possible eventualities.

Finally got the rejection mail. Damn. This was one bittersweet experience.
