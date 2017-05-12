## Debugging

-

## "unhackable code"

-

## "unwritable code"

---

## Debugging

- What went wrong?
- Where to start?
- Where to look?
- How to look?
- How to research?
- What to research?

---

## What went wrong?

- What did you expect? vs What happened?
- How to categorize the failure
  - Logic
  - Data
  - Visual
  - Interaction
  - :boom:

---

## Where to start?

- Usually the last thing you changed
- This is why having good git commits is important
- `git diff` is your friend
- Can you roll back those changes and the problem goes away?
  - Then it must be that change that caused it

---

## Where to look?

- logic issue? - Look in models, controllers, a little bit in views (where there is logic)
- data? - Look in your database, or your models
- visual? - Look in your views
- interaction? - Look in your javascript

---

## How to look

- Logs are your friend, get to know the _rails_ log
- Javascript console is also your friend, keep it open when using your app
- `heroku logs` can show you what is happening to a failure to your app in production

---

## How to research

- Copy/paste the error message into google
- Maybe surround the entire thing, or part of it in quotes (for an exact match)
- Search key words
- Re-read the docs for the gem/library/language-feature you are using

---

## What to research?

- The error message
- The code that generated it
- The lines of code you recently added, or the gem you recently added.

---
