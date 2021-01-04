**\*\***\*\***\*\***Explanation**\*\*\*\***\***\*\*\*\***
Suppose we want to fetch a glass of water. But we are busy and we can't afford losing time. So we have two options :- (
We can either make our clone that can fetch water for us(Process)
Or we can make a hand that does the same(Thread)
A process contains call stack ,register, code and data........
each threads share code and data but do not share call stack and register
)

**\*\***\***\*\***EplanationEnds**\*\***\*\*\***\*\***

(P)rocess
(T)hreads

P :- Heavy weight task
T:- LightWeight task

P:- Creation involves use of system calls
T:- NO systemcall involved

P:- OS treats different processes differently
T:- No new process is created

P:- New Process created is a clone of first process
T:- New thread created is not a clone but opearate on same code and data. Only the call stack and registers are different

P:- The new process created using fork system call causes the new process to have the parent Process id of the previous process but different pid
T:- The new thread belongs to the same process

P:- Each process has its own cal
T:-
