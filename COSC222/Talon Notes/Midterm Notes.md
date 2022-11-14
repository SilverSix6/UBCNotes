### Asymptotic Notation:
- Worst Case is usually reffered to the most.
- Constant terms are ignored, 5n -> O(n)
- Lowest order terms get dropped, O(1) + O(N) = O(N)
![[Pasted image 20221101192553.png]]
- Constant Time - O(1): 
	- When there is no dependance on random variables of the outcome.
	- Even when there is multiple lines, because they are constant it still comes down to O(1)
- Linear Time - N * O(1) = O(N): 
	- For an output affected by a loop, the result is linear time N * O(1).
	- Low order terms get dropped, O(1) + O(N) = O(N).
- Quadratic Time - O(N^2):
	- A loop nested in a loop would result in O(N) * O(N) = O(N^2).

