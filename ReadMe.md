# Week 2 Lab: System Verilog

1) 
| Test Method | Pros | Cons |
| --- | --- | --- |
| Exhaustive Testing | Edge cases are all exposed, and you can be 100% sure that your code works in every case | Can be very slow for code with a lot of possible inputs. | 
| Sampling | You can selectively test the few cases that you know might trouble the program or that you're going to be using quite often, so can be great for practical use. | If you miss an edge case, there's no real way to tell until your code dies. |
| Random Testing | A great way to bump into test cases that fail but you didn't anticipate | Inconsistent, because weird behavior is difficult to recreate. Also no guarantee that you'll run into the actually troublesome test cases. |