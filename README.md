# HW2


![HW2 README command line](https://user-images.githubusercontent.com/98851959/152481397-04fc8897-fb3c-4d24-8672-c24823514c87.PNG)


Yes, the distributions match those expected from the generate data section. Although not all are exact, they are within several decimal places of the expected output. This variation may be due to unexpected repeats in the reference string. Although the first 50% was designed with the expectation to not have repeats, it is possible that the random generation created an identical segment in the first half of the refence string. 


As the size of the reference increases, the time it takes to compute the program greatly increases. Since the human genome is roughly 6.4 billion letters, that means that the reference length would be 64,000x greater than the largest reference length used in this program. The largest reference length with is 600,000 reads took over a minute to compute, so there's no way this program could feasibly compute the human genome in a reasonable amount of time. 


I spent 8 hours total on this program and about 4-5 hours on this section. I rewrote parts of the main loop several times before I got the desired output in the aligns file, but I learned how to work better with strings and use the find function to search a string and look for a segment. This was a vital part of the process data section and I feel that I performed this correctly.
