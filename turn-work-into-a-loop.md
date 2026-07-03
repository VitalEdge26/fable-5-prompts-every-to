I want to turn this recurring job into a loop:

[Describe the recurring input, desired output, current process, and frequency.]

Examples of previous inputs and outputs:

[Attach representative examples, including failures and human corrections.]

Use Claude's loop capability to design and test a loop that:

1. Collects or detects new input.
2. Tracks what it has already processed and avoids duplicate work.
3. Decides whether the input is actionable.
4. Plans and delegates the work.
5. Produces or ships the output.
6. Verifies the result against explicit standards.
7. Routes decisions that require human judgment.
8. Retries recoverable failures and records unrecoverable ones.
9. Captures corrections and updates the system so the next run improves.

Identify the trigger, schedule, context, tools, permissions, state, memory, and
model-routing rules the loop needs. Use Fable for the hard judgment and
orchestration; use faster models for routine stages. Build the smallest working
version.

Return:

1. A diagram or written map of the loop
2. The working implementation or implementation plan
3. The human checkpoints
4. The verification method
5. How learning will be saved between runs
