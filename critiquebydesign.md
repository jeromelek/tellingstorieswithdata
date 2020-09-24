# Assignment: Critique By Design

## Original Data Visualization
![Original Data Visualization](https://i.imgur.com/6UChlys.png)

Screenshot captured from The Guardian [https://www.theguardian.com/football/live/2020/aug/29/arsenal-v-liverpool-2020-community-shield-live](https://www.theguardian.com/football/live/2020/aug/29/arsenal-v-liverpool-2020-community-shield-live)

I selected this data visualization because I am a huge soccer fan, and such visualizations have become so commonplace in the game. Every match report comes with a lot of game statistics, possession, shots, tackles, passes, and it intrigued me to think if I could design a visualization. Some websites do not even bother with this and displays them as a series of numbers in the table. As more and more complicated visualizations are done for greater in depth statistics, I wonder how might I display the simple things for the common man? On top of this, the choice of colors on this particular visualization triggered me into choosing it for this assignment.

## Thought Process
The process started with the use of Stephen Few's Data Visualization Effectiveness Profile, and the outcome of this exercise made me feel like the design of the visualization has to breed familiarity. Years of experiencing such design cues would cause a radically different design to be hard for a new reader to adapt to. Often, readers are interested in such data, and thus I would think that simplicity is key in this case. I could also argue that it is this reason that many resort to listing the statistics without any visualization at all.

The main issue that screamed out to me from these visualizations was the choice of colors. I understand that both teams have red as their home color, but it is precisely this reason why there are different coloured soccer kits for home and away games. It would be a disaster if all 20 players were wearing red, and thus, the chart shouldn't be all red either. Instead, I thought that we could use the colours that the teams wore for this match.

The second part about the goal attempts seems to attempt making a clever graphic out of a goal post design, but in doing so, the visualization did not provide any sense of scale.

The next issue I thought about was the corners and fouls bars looking like they added up to 100%, or weren't in some sort of scale. I don't think it should be showing a majority kind of comparison, and thus I thought this representation does not really help. 

So with these 3 issues that I felt needed changing the most, I began research on what existing designs are out there in various sports, how the data is represented differently for football, soccer, basketball and how other graphics look like to gain inspiration on what to do / not to do. Next, I started sketching out a low fidelity wireframe solution on paper.
![Paper Wireframe](https://imgur.com/P5Wt3fc.jpg)

In the above process, I decided to break down the entire series of charts and think of them one by one.
Firstly, the possession chart. I think the donut works, similar to a pie chart since it adds up to 100%. It is a clean way of representing the composition of the match.
Secondly, Goal Attempts, the original chart does not work for me, given the lack of proportion between the two values as well. I tried working with a stacked bar chart to see a clearer comparison of the data.
Thirdly, the corners and fouls charts seem to show a summation of 100%, which I think is an inaccurate way of representing the attempts, since it shouldn't be adding up. Furthermore, even when the number of corners and number of fouls are different, the bar is of the same length. It represents a proportion that adds up to 100%, when it should simply show a difference in scale.

### User Test
With the paper prototypes, I began the test for feedback from readers. I gathered feedback from two readers, one who doesn't watch soccer, and one who does.

Can you tell me what you think this is?
1. An infographic representing Arsenal vs Liverpool
2. The match statistics from Arsenal vs Liverpool

Can you describe to me what this is telling you?
1. It's telling me that Liverpool has more possession than Arsenal, but they have the same amount of goals, and Liverpool has more fouls.
2. Liverpool dominate possession and had more attempts on goal, but they scored the same number of goals.

Is there anything you find confusing?
1. Why does Liverpool have 4 on Target, and Arsenal has 2 on target, but they have only one goal each? What's going on? The embedded model is confusing
2. The goals and on target bars seem to be quite confusing, why are goals categorised into the attempts as well? I thought that typically it is not included in the calculation.

Who do you think is the intended audience?
1. The general soccer fanatic, it's not targetted at a particular fanbase, if it was it should have stood out more in a certain way. It could be targetted for Liverpool fans, since Liverpool is in red, but it does not seem that way.
2. Soccer news readers reading the match reports

Is there anything you would change or do differently?
1. The goal attempts is still confusing, the rest of the charts depict the proportion very well.
2. The goals should not be lumped together with the goal attempts, it should be given more prominence, it doesn't have to be a part of the chart

After explaining the visualization, to the readers, they said,

1. Oh, after a while, it becomes understandable only with explanation. I do not really know what on target and off target means so it does not really make sense to me. Wow, the original chart can't even be seen properly if you're colourblind.
2. I get what you're trying to do, but goals is typically not categorised together with the goal attempts. Hence I think that part is confusing.

With the feedback, I decided to focus on redesigning the goal attempts to see what other ways I could try to represent the data.

## Final Data Visualization
<div class="flourish-embed flourish-chart" data-src="visualisation/3823452" data-url="https://flo.uri.sh/visualisation/3823452/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>


### Back to [Homepage](https://jeromelek.github.io/tellingstorieswithdataportfolio/)
