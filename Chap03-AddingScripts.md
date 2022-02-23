# Adding Scripts

So, what other changes are required in the game?

Try playing the game after cloning it from the repository, you can see that the player can move, jump and pick up keys but when the player touches the enemy nothing happens right?

![](https://media.giphy.com/media/3ohjUT1wGYB23WDzCU/giphy.gif)

First, we need to create a function that does something, in this case, reduce the life by one and then trigger the death or GameOver UI when all 3 lives are lost.

Here is a sample script that does this:

![Killplayer](https://user-images.githubusercontent.com/44625252/155331281-3358531d-db0a-498d-997d-56cb90823d86.png)

Then, once the function created, all we need to do is trigger this function when the enemy collides with the player.

Here is an example how this can be implemented:

![EnemyCollision](https://user-images.githubusercontent.com/44625252/155331606-8ae5ca54-54ad-424a-9732-ae0c671e233f.png)

And thats it!

https://media.giphy.com/media/RLK2SQ1cndlTd4oA7l/giphy.gif

Think where you need to add these script changes from among the script files.

![](https://media.giphy.com/media/xUA7b6G577b74RSS3e/giphy.gif)