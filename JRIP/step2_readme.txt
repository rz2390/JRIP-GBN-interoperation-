The architecture used in the end was the select.select() structure which was recommended by the processor in the last update of the project guideline. 

The most important part about this design in my mind is that the timeout was maintained using a queue data structure which allows me to append and drop tuple (seq,sent_time) easily.

The goodput results can be seen in screenshot, which was much better than my previous architecture where I did not make it to design a good architecture using multi-threading. 
