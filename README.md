BreakSentences
==============

Breaking sentences more meaningfully.

Often times when inserting a sentence(string) into a predefined database, we run into column character limitations. 

Yes, you can use a truncate function but that end up creating meaningful sentences. Not to mention depending on where is breaks, sentence now could have words that you never want to see/display.

Let's say sentence is, "Quick brown fox jumps over the lazy dog" and breaking at 19(i.e. getting the 19 leftmost characters), would make it "Quick brown fox jum".

I know nothing harmful there but I think I we can be little smarter than that.

And the final result will be something like,
"Quick brown fox"
