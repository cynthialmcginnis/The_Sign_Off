# The Sign-Off

An interactive exercise in approving an AI system before it goes live.

Software is about to decide which applications get accepted: who gets a job interview, who gets a loan, or who gets an apartment. It scores every applicant from 0 to 100 and rejects everyone below a cutoff. You set the cutoff, see who the model gets wrong in each of two groups, and put your name on the decision.

**Try it:** https://YOUR-USERNAME.github.io/the-sign-off/

## How it works

1. **Pick a decision.** Choose a hiring screener, a loan approval model, or a tenant screening service.
2. **Ask the vendor.** Three questions about the training data, what the score predicts, and how it was tested. Your record shows which ones you asked before you signed.
3. **Move the cutoff.** Each dot is one simulated applicant. Watch who is wrongly turned away and who is wrongly let through, group by group. Pin at least three cutoffs to compare.
4. **Sign.** Choose a cutoff, decide to deploy, deploy with conditions, or not deploy, and give your reason. Save the record as a PDF or copy it as text.

## What it teaches

- A cutoff is a human choice. The model does not make it.
- Moving the cutoff does not remove mistakes. It moves them from one kind of person to another.
- One overall accuracy number can hide a model that fails one group far more often than another.
- A check on approval rates can pass while the model still treats two groups very differently.
- Each scenario goes wrong for a different reason. The vendor's answers tell you which.

## Running it

It is one file, `index.html`. There is nothing to install and no server. The page makes no network requests and sends your answers nowhere. Progress is saved in your own browser.

Open the link above, or download `index.html` and open it in any browser.

## Notes

- Every organization, applicant, and vendor is fictional. The numbers were generated for this exercise and describe no real group of people.
- The page shows which rejected applicants would have worked out. No real organization has that information. That is the point of the simulation.
- The four-fifths rule shown on the page is a rule of thumb from United States employment guidelines. Nothing here is legal advice.

## Author

Cynthia McGinnis

&copy; 2026 Cynthia McGinnis. All rights reserved.
