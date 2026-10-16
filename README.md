# devops-submodules

A course demo for the agentlabs learn DevOps track, Course 3, Lesson 7 ("Releases and detective tools: tag, blame, bisect, submodule").

It is a tiny service repository that pins the Tasks API (https://github.com/agl-learn-examples/devops-tasks-api) at its first release, v0.1.0, as a git submodule in `vendor/tasks-api`.

A plain clone leaves `vendor/tasks-api` empty. Fill it with

    git submodule update --init --recursive

or clone with the submodule in one go:

    git clone --recurse-submodules https://github.com/agl-learn-examples/devops-submodules.git
