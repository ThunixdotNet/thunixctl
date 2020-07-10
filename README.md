# thunixctl

These are a set of tools to allow users to carry out basic administrative tasks, in a secure manner. This tool isn't written set, and this doc acts as a specification.

# thunixctl

thunixctl {service} {action}

  thunixctl is a tool that allows for end-user execution of simple administrative tasks, in a secure fashion.

  {service} and {action} are required arguments.

	Currently, the available services are ansible, www, and gopher.  Actions are pull for all three, and run for ansible.  "Run" allows users to kick off an ansible run on the machine. "Pull" grabs the latest copy of the repo into it's thunix working location.

# openissue 

openissue {repo} {title} {body}

	openissue eases the ability for users to open issues in the pertient Thunix repo, without the need to create a tildegit account.

	{repo} - Any of the project repos Thunix uses to operate.  A list can be found (here)[https://tildegit.org/thunix].
	{title} - A short description of the issue
	{body} - Full length description of the problem.  Your username will be included here, so we know who to address regarding this issue.
