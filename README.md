# What is the purpose of the on section?
It defines which events trigger the workflow to run.

# What does workflow_dispatch do?
It lets you start the workflow manually from the Actions tab.

# What does runs-on specify?
It specifies the type of virtual machine the job runs on.

# Why is actions/checkout needed?
It downloads the repository’s code onto the runner.

# What does the language setup action do?
It installs and configures the specified language version on the runner so its tools are available to later steps.

# What is the difference between compiling and running the program?
Compiling translates source code into a form the computer can execute, while running actually executes it.

# Where can you see the program output?
In the Actions tab, by opening the workflow run and expanding the program-execution step in the log.

# What is the difference between a workflow, a job, and a step?
A workflow is the whole automated process, a job is a set of steps that runs on one runner, and a step is a single action or command within a job.