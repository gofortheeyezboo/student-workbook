What are some of the signs and causes of Callback Hell?

Cause is poorly written code, signs are nested callbacks within nested callbacks etc.

What does the asynchronous mean and how are callbacks involved?

Asynchronous part means it doesnt happen right away. The callback may take time to finish

Summarize the 3 ways to avoid / fix Callback Hell

try catch is a good way to prevent excessive nesting. Keep your code shallow - name things appropriately and assume someone who has never seen this code is the one reading it. Modularize - group like data and like functionality. Handle all errors - handle errors as you get them this will prevent a pileup of errors that could get confusing to troubleshoot if you have been ignoring errors in your code.

https://github.com/gofortheeyezboo/latewinter2021-swapi