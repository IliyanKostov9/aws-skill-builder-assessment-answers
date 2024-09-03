#### What are the features of AWS Step Functions? (Select THREE.)

> - Managing workflows with multiple steps that add flow logic.
- Provisioning and managing servers.
> - Continuing the process where it was left off due to network failure or hung components.
> - Tracking inputs and outputs between steps of a workflow.
- Managing operating system patches and
- access control.


#### What are the benefits of AWS Step Functions? (Select FOUR.)

> - Automatic scaling
> - AWS service integrations
- Pre-provisioning AWS services
- Launching EC2 instances
> - High availability
> - Visual monitoring


#### AWS Step Functions maintains application state and tracking. Select True or False.

> - True
- False


#### Which workflows do you choose for 100,000 requests per second?

- Standard Workflows
> - Express Workflows


#### Which workflows are ideal for long-running, durable, and auditable workflows?

> - Standard
- Express


#### There can be any number of terminal states per state machine.

> - True
- False


#### Which workflow type writes to CloudWatch Logs by default?

- Standard Workflows
> - Express Workflows

#### In the below section, match the column on the left (AWS Step Functions states) with the terms on the right (states definitions). If you're using the keyboard to navigate, tab to the term on the left, press the space bar, then use the right arrow key to move to the column on the right. Press space to match, then repeat for the next item.

    Pass = Passes its input to its output without performing work.
    Task = Represents a single unit of work performed by a state machine.
    Choice = Adds branching logic to a state machine.
    Wait = Delays the state machine from continuing for a specified time.
    Suceed = Stops an activity successfully.
    Fall = Stops the activity of the state machine and marks it as a failure.
    Parallel = Can be used to create parallel branches of activity in your state machine.
    Map = Can be used to run a set of steps for each element of an input array.
