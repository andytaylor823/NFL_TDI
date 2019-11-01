# NFL_TDI
An analysis of NFL data (provided by Armchair Analysis) in conjunction with The Data Incubator's fellowship program
------------------------------------------------------------------------------------

For my capstone project as part of The Data Incubator, I would like to study play-calling in the NFL. Specifically, I would like to study 4th down conversion attempts, 3rd down play-calling, the effects of weather on play-calling, and the importance of field position in the NFL. If time permitted, I would like to study several other smaller research questions related to the NFL as well (such as Bill Belichek's belief that punts made by a lefty are more difficult to receive than from a righty).

THE DATA:
---------------------------------------------

The data I will be using for this project are provided by Armchair Analysis, and sample data may be found at https://www.armchairanalysis.com/nfl-data.php . In this folder, I have prepared a short Python notebook, where I perform a brief data exploration, on the subject of 4th down conversion attempts. Because of the time limitations of The Data Incubator's challenge phase, I was unable to thoroughly analyze the data, but I believe I have raised interesting research questions (with real-world applications) and demonstrated that I am capable of answering these questions.

The data used in this exploratory data analysis (EDA) are taken from the free available data on Nov. 1, 2019. If I were accepted to The Data Incubator's fellowship program, I would purchase the research data package to have access to every play called in every game in the NFL for the last 19 years. Talk about big data!


THE PROPOSAL:
--------------------------------------------

Under the broad umbrella of play-calling in the NFL, there are certain specific plays that I would like to analyze further:
  (1) Fourth-down conversion attempts
  (2) Third-down defensive play-calls
  (3) Play-calling in inclement weather

The first question I would like to study is the effectiveness of "going for it" on 4th down. What situation are teams often in when they choose to "go for it"? What sorts of plays are called to attempt the conversion, and how effective are these plays? Via the EDA performed in the attached Python notebook, we see that teams that go for it on 4th down (1) are often losing, (2) have success rates roughly equal in short- and medium/long-yardage situations, (3) tend to commit penalties twice as often, and (4) call passing plays nearly three times as often as rushing plays. With more time (and more data), I believe I could perform a thorough study on the effectiveness of "going for it" on 4th down.

The second question I would like to study is related to defensive play-calling on 3rd down. Conventional wisdom suggests that defenses bring a blitz on 3rd down, especially when the quarterback is relatively inexperienced. This stems from a desire by the defense to confuse the quarterback, not allowing him to get comfortable, leading to defensive success and a failure to convert on 3rd down. Does this have a basis in reality, however? Is it true that defenses that blitz on 3rd down tend to have better success than defenses that play otherwise standard coverage?  And does the suggested relationship with quarterback inexperience have merit, as well? I would like to answer these and similar questions as part of my capstone project.

The third question I would like to answer concerns the effects of inclement weather in play-calling. When the weather is poor, do teams often switch to more conservative playstyles? If so, how well does this work? Does the team with the more conservative playstyle tend to win games more often when the weather is poor? Does the team whose roster *better supports a conservative playstyle* tend to win games more often when the weather is poor? Thanks to the fine team at Armchair Analysis, every game in the NFL over the last 19 years has been recorded, and so has the weather. With access to this full dataset, I would be able to answer these and similar questions.

FIELD POSITION:
------------------------------------------------

To tie these separate threads together, I would like to study the importance of field position on a team's likelihood of winning a game. If a team opts to try and "go for it" on 4th down, they may risk the chance of handing their opponent a sizable field position advantage; but, how important is the advantage? Of course, an offense would rather start with the ball at midfield than on their own 20-yard line, but is it possible to quantify the importance of this field position advantage?

Regarding 3rd down play-calling, is there a relationship between defensive or offensive play-calling and one's field position? Are offenses more likely to play conservatively on 3rd down when deep in their own territory, and does the data suggest that this is the smart play? Or, is it actually better for offenses to always aggressively try and convert, since the potential points gained far outweigh the potential field position lost?

When a game is played in inclement weather, the importance of field position likely increases. It is harder for offenses to pass the ball (and therefore score points) in the rain, so any field position boost may be enough to turn the tide of the game in one team's favor. Is this actually true? Does field position become more important in inclement weather, or is there no change?

Under the umbrella of field position, I would like to study 4th downs, 3rd down play-calling, and the effects of inclement weather. I have demonstrated in the attached Python notebook that I am capable of performing such an analysis and can extract meaningful results from the data. Thank you for considering me for this fellowship.
