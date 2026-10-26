# Madlibzzzzzzzzzzzzzzzzzzzzzzzz
I wrote the StoryGenerator class, which has one method called generateStory. It takes the story template (from Shourya's StoryTemplate) and the words the user typed in (from Vansh's InputCollector) and puts the words into the blanks.

The template uses %s for each blank, so I used a for loop with replaceFirst("%s", words[i]). Each time through the loop it fills the next blank with the next word, in order. It returns the finished story as a String instead of printing it, so the main program (Halloween_MadLibs) decides when to print it.

Things I worked out with the team:

The words have to be collected in the same order as the blanks in the story, so Vansh's prompts match Shourya's template.
Shourya's template is a variable, not a method, so we changed line 9 in main to use StoryTemplate.template.

I added my file to my fork and opened a pull request to merge it into the main repo.
