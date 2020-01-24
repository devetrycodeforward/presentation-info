# PyDen Presentations Outline

## General theme:
You are presenting a technical **product** to a technical audience

## Important notes:
- Presentations will be 3 minutes with a 2 minute Q/A
- We will all be presenting on a single laptop to avoid transition times
- The application you plan on presenting **must** be deployed

## Outline:
1.  **Business case**:  Why does this thing exist?  What problem is it trying to solve? (no more than 30s)
    - Greenfield: Why did you make this from scratch?
    - Legacy portion: Why did you implement _your_ feature from scratch?

2.  **Tech used**:
    - Greenfield: Full stack
    - Legacy: To implement particular feature
    - **NOTE**: Your base tech stack here is identical to all the other presenters (Vue, Flask, Postgres). Given that this is the case, do **not** spend more than one sentence telling the audience what your tack stack is.  Eg: *Similar to my peers, I built my App as a Single Page Application in Vue, that communicates with a Flask Back End, that talks to an AWS RDS Postgres instance via SQLAlchemy*
        - Don't memorize this word-for-word, but say something to that effect.
    - **Spend more time discussing**: Cool tech used
        - Moment.JS
        - Drag & Drop
        - XML Parser
        - Vue Router
        - ...ect.

2.  **Challenges**:
    - What was **unusual** / difficult to implement?
    - What might a technical audience find _interesting_?
    - Any cases of trying to fit a square peg in a round hole?

3. **Next Steps**:
    - How might another engineer wanting to fork your project add to it?

## Potential Q/A Questions:

1. Why did you use Vue instead of React (or anything else you haven't learned yet)
    - **Acceptable Answer**: I haven't yet gotten the chance try React, but I'm excited to check it out soon.

2. Why did you architect your app to store favorites in the Vue application state instead of the DB?
    - Generally, they are asking, why did you use this pattern instead of that pattern.
    - **Acceptable Answer**: [Try your best to justify your tech/business decisions]