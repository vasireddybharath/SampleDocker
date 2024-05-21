# docker-sample-nginx
a sample nginx container


workflow reuse also promotes best practices because you can use workflows that have already been tested and already been tried out and so on so forth and are provde
to be well designed. We can create a library of centrally managed workflows to be reused across the different organizations.

Caveats:
Workflow must be stored in the same repo as the caller or in a public repo or yet in an internal repo with settings that allow it to be accessed.

Limitations:
Reusable workflows cannot be used by other workflows if they are in private repos unless of course the caller is in the same repo also reusable workflows cannot call another reusable workflow. Environment variables set at the workflow level of the color workflow are not automatically passed to the reusable workflow so if you need any of those value in their usable workflow you need to pass them using the parameters as we've seen in the demo.