---
layout: post
title: Design Manifesto
---

# Introduction

When I signed up for Human Computer Interaction, I really didn't know what to expect from the course. Chalk that up to my inability to read course descriptions, but I didn't understand the wealth of design knowledge that I would gain this semester. I have developed several core tenets which I hope to incorporate into all future design and development endeavors, all of which center around one key idea: you may not foresee every problem users will face and you might not know the right solutions, but keeping an open mind is the best way to ensure your design meets the most possible needs and improves the lives of your users. With that said, here are five important concepts in my personal design routine.


# You are not the Users are not Each Other

From the beginning of my Human Computer Interaction course, we were taught the phrase "You are not the user". The idea is that you, the designer, have different experience, knowledge, goals, and outlook from any user, and thus you cannot design with solely your needs in mind. This idea may seem obvious, but it is deceptively difficult to address. We performed several contextual inquiries early in the design process, with the goal of seeing what problems users actually faced in art museums. Our very first participant said that they were an art amateur; hooray! Just like us, and the exact audience we wanted to address. We went in with an idea of who our audience would be, but we also already had design ideas related to encouraging art amateurs to share their thoughts on art pieces. As it would turn out, this first participant felt out of place in art museums, but said that they felt no desire to be a part of the museum community. This idea directly opposed our desire to make art amateurs more comfortable in museums by getting them engaged in the community. We found that other users felt differently and that even this original participant would be willing to engage in a design that wasn't disrespectful to the art museum community in their eyes. This inquiry was a wakeup call that users would not share our exact same goals or issues; in fact, sometimes people can have completely opposing opinions to yours'. 

This inquiry also revealed that users think differently than you, but they also think differently from one another. We further encountered inter-user disagreement during our usability testing. When one user pointed out that it wasn't clear from our paper prototype web-app what the purpose of the large interactive display was, we adjusted our design accordingly to show this information more prominently according to what that user requested. The before and after images of this screen are shown below.

![Original Design Without a Link](https://camo.githubusercontent.com/3a69b21ffea6100a26ef5c69522b798ea6840e10/68747470733a2f2f692e696d6775722e636f6d2f6c5834507775672e6a7067)

![Design With a Link to a Page](https://camo.githubusercontent.com/16e52ffa9c12090cd09da63c7dd7be881de25db4/68747470733a2f2f692e696d6775722e636f6d2f4859543476716a2e6a7067)


Much to our dismay, the participant in our next usability test was perplexed at the same point in the design even with additional information. We again had to change this page in our final design to enhance clarity. These users encountered issues in the exact same location, but the solution for one user did not work for the other. It is important to not simply design exactly to the user's requests, but to consider the broader implication of why the user is asking for that solution. 

# You Can Achieve The Same Goal In Multiple Ways

Users are not only different from one another in usability needs; they can also have fundamentally different desires from a design. A design can work towards addressing a specific issue, like ensuring all museumgoers feel included, but do so in several different or incremental ways. Our design allows users to engage with content in different manners and with varying levels of freedom. For example, a user needs to select an emotional response in order to leave a comment (both screens shown below).

![Emotion Selection Screen](https://camo.githubusercontent.com/03f0b165d33aa973a7ee39caca95182c4af012bc/68747470733a2f2f692e696d6775722e636f6d2f566e4a745a79522e706e67)

![Commenting Screen](https://camo.githubusercontent.com/58ffb8e9ae206eec7e65b5f0bc45cb0eb9b87811/68747470733a2f2f692e696d6775722e636f6d2f5845356b63466b2e706e67)


We made this design decision because commenting is a higher-effort form of leaving a response; a user who is willing to leave a comment is probably also willing to leave an emotional response. The progression in this part of the design makes logical sense, but we also wanted to give users the option to opt out of this chain at any time. It is important to give users the choice to undo any action or abort use of the design at any time (Nielsen, "Usability Heuristics"), and we found this to be true in our design research process. One of our usability test participants said that they would not leave a comment in real life because they were shy beyond being an art amateur. However, they would be willing to leave an emotional response and enjoyed seeing that other people reacted similarly. Thus, like designing for usability needs, you must recognize that users want different levels of engagement even if you are addressing a specific problem.

# Work Beyond Your Main Goal

In addition to helping users overcome a specific issue, you should also design beyond this main issue. Adding additional features, where appropriate, can enhance user engagement and even reveal new solutions to your original problem. One usability test participant remarked that they would really like to see actual statistics and numbers about how people have responded. This desire wasn't because the user wanted to feel included in the art community; such information was simply interesting to them and exciting to look at. We did add this information to the large display because it was both simple to implement and engaging for users.


![Screen showing the number of angry users and the total percentage of the population that those users make up](https://camo.githubusercontent.com/3a8ec4dd008c2138e5ee43726c12bb20625883b0/68747470733a2f2f692e696d6775722e636f6d2f3577535837564e2e6a7067)

While this design choice did not directly address our original design goal, it did serve to increase user enjoyment and engagement with our design. By getting users engaged and having fun with our design, we can indirectly help people feel like they belong in an art museum. Thus, it is wise to expand beyond a specific design goal to other ways that you can benefit your users. Sometimes you'll even help meet your original goal in the process.

# Design to the Same Level for Everyone

In considering all manner of user concerns and desires, no matter is more important than ensuring anyone can engage with the design regardless of accessibility needs. Admittedly, there are many different ways I now realize we could have made our design and webpage more accessibile. We could have added text descriptions to all images in our posts if I had realized that the brackets in a markdown image tag weren't just for writing the image source (just learned that last week, check them out on the images on this page). However, we did consciously make several design decisions to improve accessibility. Our design made heavy use of color (like in showing possible emotional responses like the screen below) as a way to differentiate between choices.

![Emotion Selection Screen](https://camo.githubusercontent.com/03f0b165d33aa973a7ee39caca95182c4af012bc/68747470733a2f2f692e696d6775722e636f6d2f566e4a745a79522e706e67)

No matter the extent to which you choose contrasting colors in a design, which we tried to do throughout our project, the use of color has the potential to discriminate against people with different vision needs. Thus we tried to add other novel visualizations in addition to explicit text descriptions of color-based visualizations. The very poorly-made visualization below started as a simple pie chart showing user response proportions, but we decided to add additional facial structure and text description to it.

![A face / pie chart with different segments colored according to their corresponding emotion and facial components differing depending on the emotional region they fall into on the chart. Text description of statistics accompanies the visualization](https://camo.githubusercontent.com/7b35780f4bf19ddebd70f6f968108d781830b248/68747470733a2f2f692e696d6775722e636f6d2f4861697a3343412e6a7067)

In this way, we attempt to address color-related accessibility needs while providing the same create visualizations to users. Accessibility is unfortunately not at the forefront of the minds of many developers and designers. It is important to address accessibility needs in a way that best preserves the original intent and interesting aspects of the design so that all users can experience them.

# Personal Code of Ethics

Interacting with users has helped me develop personal guidelines on morals and ethics in the design process. With such a code, I can't ensure that my actions are not harming anyone, but I can ensure that I am doing my conscious best to be fair and leave a positive impact with my designs. My first two tenets are inspired by the Signal Code (Harvard Humanitarian Initiative, "The Signal Code: A Human Rights Approach to Information During Crisis"), but stem directly from my design experience.

## Privacy

From the beginning, our professor instilled in us the importance of privacy when conducting different forms of user-centered design. People want control over their identity in every facet of online life, from social media profiles to online-published research in which they were a participant. Throughout my brief time as a designer, I've sought to ensure that people only reveal as much information as they would like when using my designs or participating in research with me. When we conducted our contextual inquiries, we ensured that people were completely comfortable sharing all of their information before actually recording their thoughts. Our project was focused on art amateurs, and we made sure that people were comfortable sharing any ideas that they thought might sound "dumb" or unsophisticated. We made people comfortable with sharing these private ideas by reassuring them that their ideas would remain completely anonymous and that they could not be identified solely through descriptions of them in our writings. We did the same in our usability tests, while also letting users choose their pseudonyms. This decision actually offered another degree of privacy, as we had previously been giving gender-normative names to our participants without asking them. The overall privacy stakes were low in this course, but we nevertheless did our best to ensure the utmost privacy of our research volunteers. 

![Post-emotional response submission screen where the user is shown many faces representing other users who responded the same](https://camo.githubusercontent.com/c1a8b809eb541671239e34caf84f9bc570b34244/68747470733a2f2f692e696d6775722e636f6d2f6a6f6755466a672e706e67)

In addition to our research process, our actual design was heavily based upon user privacy. The above image provides an example of the anonymous way in which users see other user responses. Privacy was a core tenet of our design because it allowed users to casually share their ideas without fear of being publicly ridiculed, an improbable occurrence but a real fear in the minds of art amateurs. Overall, this design and design research process helped develop my views on technological privacy such that privacy is essential to my future career as a software developer.

## Rectification

People do not want all of their data to be public, but they would also like control over whether data about them is accurate. During our contextual inquiries, we were encouraged to get our users to clarify any statements that were confusing to us. In doing so, we discovered that users really do care about how their thoughts are written down and whether they are represented accurately, even in this anonymous school-based setting. We used these results in our usability testing later in the semester, asking users to elaborate on ideas that were clear to us at first statement but which the user might like to say more about. In these veins, our design had numerous points where the user could either change their answer (such as when selecting an emotional response) or elaborate further on their feelings (leave a comment). These points are shown in the two images below.

![Post-emotional response selection screen where the user is prompted to submit their response or go back and change it](https://camo.githubusercontent.com/29dd1126f6d2b540cee198a23e1fa521cf05ef8d/68747470733a2f2f692e696d6775722e636f6d2f5939574d36476a2e706e67)

![Comments screen](https://camo.githubusercontent.com/e09d8eebcbdab6b189fca504d6806a5bfc1fefb7/68747470733a2f2f692e696d6775722e636f6d2f354531724b69482e706e67)

As I discussed earlier, users want control over how much they engage in a design. Being able to choose and change how their data appears is another step in ensuring users have this control, in addition to being an important moral idea.

## Inclusivity

My final and perhaps most important ethical code is to ensure that anyone who tries to use our designs feels like they are included and personally wanted. Our design focused specifically on the issue of making sure that everyone who walks into an art museum can feel like they belong in that space. Over the course of the semester, our design evolved along this path to include the idea of social belonging for all users. We learned that people feel more like they belong if they know that other users have the same emotional response or thoughts. This idea of inclusivity is incredibly important to engaging users, but it is also morally correct to eliminate the stress and loneliness of feeling excluded / apart from any group. We created our design so that absolutely anyone would feel included, regardless of their emotional response or thoughts on a piece. Feeling like I belong in a space is incredibly important to me, and I hope to foster that same feeling in all of my future work.

# Conclusion

User needs are varied and not necessarily easy to predict. What works best for you will often not work best for the user, and it is important to not become focused on one possible solution or one specific user issue. The best way to ensure that you leave users better off after your product is to maintain an open outlook on both potential problems and solutions. Doing so will improve both the success of your product and the lives of your users.
