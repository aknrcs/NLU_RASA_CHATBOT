Modified the example rasa restaurant bot to run for our zomato example. I got it to work.

Note: actions.py file would require the zomato key. Please set it to your personal key and then run the bot.

You need to use 'make' to train nlu and core.

Commands to run
make train-nlu
make train-core
make run #This will run the bot (it runs the action in background)
