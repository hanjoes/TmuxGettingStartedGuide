# TmuxGettingStartedGuide

## Basics

* How to Start Tmux

In your terminal, run:

`tmux -2`

I put this in my terminal start script so each time I open my terminal tmux is ready.

* Conrol

If you've used emacs, you should know the idea of **meta key** (or **prefix** in tmux terminology). Basically it is a key combination that starts a command.
In tmux, the meta key is **ctrl+b**, and we will use **C-b** throughout the guide to represent the tmux meta key.

## Window/Pane Management

I'm not a hardcore tmux user, I mostly use tmux to do some window/pane management. Tmux also has very strong session management functionalities. For users interested in session management, please check out the references section.

**Session** though is not elaborated in this guide, you should at least know that it's the highest level of the tmux management hierarchy. A session basically manages the current working context (including windows, and more..).

The second level in the hierarchy is **windows**, a session could contain multiple windows. I usually work on this level. For example, I'm working on some server code and want to deploy that server to remote machine and check logs. I will create a window for all workflow for that server. And split the window into **panes** (which will describe later). In this case each window is a workspace. As shown in the picture below:

![Workspace](./pics/win1)

## References
[Workflow in Tmux](https://coderwall.com/p/_g2vpq/workflow-in-tmux) Gives some handy examples of tmux workflows.
