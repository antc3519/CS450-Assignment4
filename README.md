# CS450 - Assignment 4
# Website can be viewed here: https://antc3519.github.io/CS450-Assignment4/

Classwork for CS450 - Introduction to Data Visualization

A word cloud is a type of visualization that displays the frequency of words in a given text. More frequent words appear larger, while less common words are shown smaller. This method is commonly used in data analysis to quickly identify key themes or topics in large text datasets, offering an intuitive way to summarize and present information. In this assignment, you will create a dynamic word cloud using React and D3.js to visualize the frequency of words from user-inputted text, helping users grasp the main themes.

User Interface and Animation Description: The interface will feature two main components: a textarea for user input and a button labeled "Generate WordCloud." When the button is clicked, the app will calculate word frequencies and update the component's state with the new data. The word cloud will be automatically generated or updated to display the top 5 most frequent words whenever there is a change in the textarea. Words will appear larger based on their frequency, with less frequent words being smaller. You’ll use D3's scaleLinear() to scale both the word positions and their font sizes. The size of the words will visually reflect their frequency in the text. Animation will be applied to the font size when words are appended to the svg. For updated texts, animation will affect both font size and word position to reflect changes.

Note: You will only use D3, HTML and CSS to complete this assignment.
Submission: Submit the following on Canvas:
* The App.js component
* A link to your deployed webpage on GitHub Pages.

