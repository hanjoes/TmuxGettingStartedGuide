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

The second level in the hierarchy is **windows**, a session could contain multiple windows. I usually works on this level. For example, UNDERCONSTRUCTION


## References
[Workflow in Tmux](https://coderwall.com/p/_g2vpq/workflow-in-tmux) Gives some handy examples of tmux workflows.
