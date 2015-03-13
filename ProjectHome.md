Freankly speaking, this sampler isn't a sampler. because it doesn't make request by itself. it just delegate a requeset to remote process and keep the process alive in remote server. The real request would be made in this remote process.

> - This contains a jmeter sampler. AgentSampler
> - This contains a tcp server. It listen the command, launch the process, and terminate it.