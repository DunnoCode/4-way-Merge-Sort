<h1>4-Way Merge Sort</h1>

For assign_q1_1.c is to make the parent processor and the child processor async and share the same memeory location with the use of shmid.

For assign_q1_2.c will have one more child processor compare to assign_q1_2.c and the parent needs to wait both of the child processors finsih the task first.

For assign_q2.1.c asssume that will the method of sorting an array will devide by 4 instead of the traditional method of dividing by 2. The four processor needs to do the sorting of 
the divided array and then they will do the final sort in the parent processor.

For assign_q2_2.c using assign_q2_1.c as the base case and it will allow to do more dividing compare to the previous one. Such that if the array have 64 integers, then it will able to
divide 4 first and then separe the rest to the 4 processors.
