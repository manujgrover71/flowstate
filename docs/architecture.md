### Architecture

#### System Components:
1. Server: Responsible for workflow creation, management, and observability.
2. Workflow Engine: Polls workflow tasks from workflow queues and executes them. Does task execution, retries, and error handling.
3. Activity Worker: Executes the actual business logic of the workflow tasks. It can be implemented in any programming language and can run on any platform.
4. Event Hi

#### Queues:
1. Workflow Queue: Stores workflow tasks that need to be executed by the workflow engine.
2. Activity Queue: Stores activity tasks that need to be executed by the activity worker.


