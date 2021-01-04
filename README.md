# Has Dan been a vegan today?

The answer to this question, available here: http://danieljabailey.github.io/have_I_been_vegan_today

# Have I been a vegan today?

Want to use this to track your own veganuary?

For this repo, create a folder called `data`.

Inside the `data` folder create a folder structure for the dates.

For example, a folder called `data/2021/1/23` for the 23rd of January 2021.

Inside each day folder have a file called `answer` which contains `yes`, `no`, or something more descriptive. This is the answer to the question "have you been vegan today".

Yes is coloured green, no is red, anything else is yellow.

Add any notes you want in a file called `notes` next to the `answer` file.

Deploy this to a gh-pages instance and you're good to go.

Remember to remove `data` from the `.gitignore` file and then commit all your data.

You can test if the data looks right by running `./build` and then testing it with a local web server. Perhaps use `python3 -m http.server`.
