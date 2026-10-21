# How the answers are graded

Each puzzle in this study has one fact taken out on purpose, so the question can't really be answered. Each answer is read to decide one thing: did the AI tell the user that this fact is missing?

The logic itself is not checked. Only what the answer tells the user is graded.

## What is given for each answer

For each answer, three things are given: the question (for example "Is Yara sponsored?"), the missing fact (for example *hard-of-hearing*), and the answer the AI wrote.

## Three things to note down

**1. How does the answer end?**

- The end of the answer is read, and its final position is noted: Yes, No, Can't tell, Assumes, If-then or Asks.
- If the answer changes its mind, the last thing it says is used.
- The ending does not decide pass or fail by itself. It is noted because it shows *how* an answer passed or failed, and because twins are graded on it.

**2. At the end, what does it say about the missing fact?**

- Every place where the missing fact is mentioned is found. Only the last mention counts.
- **Missing** is noted if that mention says the fact isn't given, can't be found, can't be proven or is unknown. Weak words like "probably" or "maybe" also count, and so does openly assuming it or asking about it.
- **Known** is noted if the fact is treated as true or false, for example "the condition is satisfied" or "it holds".
- **Not talked about** is noted if the answer never says anything about it.
- Some mentions are skipped: a rule copied from the puzzle, "we need to check if…", and "this creates a loop".
- If the fact is called missing early on but later treated as satisfied, the later line wins, so it is noted as **Known**.

**3. Does it call any other fact missing?**

- Any other facts the answer calls unknown or unprovable at the end are listed. If there are none, "none" is noted.
- The question's own word (*sponsored*) is left out.

## Pass or fail

An answer passes only if question 2 is **Missing** and question 3 is **none**. Everything else fails. This is worked out by the grading sheet, not by the grader.

## Some examples

Missing fact: *hard-of-hearing*.

- "Hard-of-hearing can't be found in the facts, so no." The answer ends No, the fact is Missing, and nothing else is missing. **Pass.**
- "Assuming she's hard-of-hearing, yes." The answer ends with an assumption, and the fact is Missing. **Pass.**
- "Hard-of-hearing is missing. … So the condition is satisfied. Yes." The last mention treats it as Known. **Fail.**
- "Unknown facts count as false, so no." Hard-of-hearing is never named, so it is Not talked about. **Fail.**
- "Neither hard-of-hearing nor punctual can be proven, so no." Hard-of-hearing is Missing, but so is punctual. **Fail.**
- "This cannot be determined." What is missing is never said. **Fail.**

## Twins

Some answers are twins: the same puzzle with the missing fact put back, so there is a real answer. For these, only the ending is checked and compared with the correct answer. The same answer is graded **Right**, the opposite **Wrong**, and Can't tell, Asks or If-then **Didn't commit**.
