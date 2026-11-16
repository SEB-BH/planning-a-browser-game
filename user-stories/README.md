<h1>
  <span class="headline">Planning Your First Project</span>
  <span class="subhead">Write User Stories</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to write 10 user stories and identify which support their MVP.

## Describe what the player needs

A **user story** describes a feature from the user’s point of view.

Use this pattern:

```text
As a [type of user],
I want to [do something],
so that [reason or benefit].
```

For our games, most stories will begin with **“As a player…”**

## Build one story together

Imagine we are planning a memory matching game.

The player needs to understand how to play. We can describe that need like this:

```text
As a player,
I want to read the game instructions,
so that I understand how to win.
```

Notice the three parts:

| Part | Example |
| ---- | ------- |
| Who needs the feature | A player |
| What they need | Read the instructions |
| Why they need it | Understand how to win |

Two more examples:

```text
As a player,
I want to reveal a card by selecting it,
so that I can look for its matching pair.
```

```text
As a player,
I want to see how many moves I have left,
so that I know how close I am to running out.
```

## Keep each story focused

“Build the game” contains too much work for one story.

Separate it into smaller player needs, such as selecting a card, seeing a match, or viewing the final result.

Technical work such as **“create an array”** may help you build a feature. Your user story should explain what that work allows the **player** to do.

## Add your stories to the board

We will use **draft items**—simple cards that can hold an idea without creating a repository issue.

1. At the bottom of **Product Backlog**, click the add-item area.
2. Type your complete user story.
3. Press **Enter** to create the card.

For this workshop, the full story can be the card title. You can open the card later to add notes. [GitHub Docs](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-items-in-your-project/adding-items-to-your-project?apiVersion=2022-11-28)

## 🎓 You Do: Write 10 user stories

Create **10 separate cards** in **Product Backlog**, with one complete user story on each card.

Think through the player’s experience:

- Understanding the instructions.
- Starting a round.
- Seeing the board or available choices.
- Making a move.
- Seeing the result of a move.
- Tracking progress.
- Handling an invalid or repeated action.
- Winning.
- Losing or drawing, where relevant.
- Playing again.

These are prompts to help you think. Adapt them to your game.

> 💡 Ten stories do not mean ten large features. Small actions and useful feedback can each become a story.

## Put the important work first

Compare your stories with the project requirements.

Add `MVP:` to the beginning of cards needed for the smallest complete version. Drag those cards above optional improvements.

For example:

```text
MVP: As a player, I want to read the game instructions,
so that I understand how to win.
```

Keep required features in your MVP even if they seem difficult. Ask an instructor for help making them manageable.
