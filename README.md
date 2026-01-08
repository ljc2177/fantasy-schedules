<h1>Fantasy Sports Scheduling - Including Conferences</h1>
<img width="994" height="240" alt="ExampleSchedule" src="https://github.com/user-attachments/assets/a3e70c6a-8430-4aa8-a4ad-69f1e18e92e0" />
<p></p>
<p>
Within the Sleeper fantasy platform, there is currently not an option for schedule creation that takes into account conferences. More specifically, there is no way to designate the ideal schedule spreading out conference play, differences in team faceoff counts, and buffer periods. Rather than manually calculating this schedule, this python code allows for the dynamic creation of a schedule using the following inputs:</p>

<img width="832" height="156" alt="inputs" src="https://github.com/user-attachments/assets/fd367939-1f49-4ddb-b3a2-838b2c5cbd84" />

<ul>
  <li><i>weeks</i> - total number of weeks within the fantasy season</li>
  <li><i>conference1</i> & <i>conference2</i> - complete list of team names within each conference</li>
  <li><i>buffer</i> - number of weeks between which two teams cannot play each other twice</li>
</ul>

<p>Following the generation of the schedule, this code also runs checks to ensure that a team plays all other teams at least once, that out-of-conference teams are only played once, and that the remaining games are made up of in-conference games.</p>


<p>Following these checks, the schedule will be formatted into excel and exported into a CSV for use and sharing. An example schedule looking like this:</p>
<img width="994" height="241" alt="Output" src="https://github.com/user-attachments/assets/a18a700f-84db-4070-8b62-aefe4113d428" />

