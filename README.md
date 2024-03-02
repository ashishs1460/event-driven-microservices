# event-driven-microservices
event-driven-microservices

CQRS : Command and Query Responsibility Segregation

Command: Think of this as a request to change something. For example, when you send a command to your TV remote to turn on the TV, you're requesting a change in the state of the TV.

Query: This is a request for information. When you ask your TV for the current channel it's on, you're making a query to get information without changing anything.

Responsibility Segregation: This means splitting up the responsibilities or tasks into separate parts. In the context of CQRS, it means separating the handling of commands (requests to change something) from the handling of queries (requests for information).
CQRS (Command and Query Responsibility Segregation): So, putting it all together, CQRS is an architectural pattern where commands (requests to change something) and queries (requests for information) are handled separately. This separation allows for different optimization strategies for reading and writing data, which can lead to better performance and scalability in complex systems.

Command : we will be telling the system to do some commands to do some operations  (aggregate) ==> command handler

Query : we will be creating queries to fetch any data in the system (projections) ==> query handler

￼

￼

￼

