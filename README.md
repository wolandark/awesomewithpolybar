<h2>My AwesomeWM Config with Polybar and Gaps</h2>
<h3> Basic Keybindings</h3>
  
| Keys           | Event          |
|----------------|----------------|
| Meta + return  | Terminal       |
| Meta + b       | Firefox        |
| Meta + w       | Waterfox       |
| Meta + d       | Rofi           |
| Meta + Space   | Toggle layout  |
| Meta + Arrow right/left| Go one tag left or right |
| Meta + h / l       | Grow tile right or left       |
| Meta + Shift + j       | Cycle tiles      |
| Meta + j       | Change focuse between tiles           |
| Meta +  Tab     | Toggle between two last clicked or focused tiles           |

<h2>Setting up and Usage</h2> 

  <li>Download polybar,rofi and Feh from the repos.</li> 
  <li>Place revelations folder & rc.lua in .config/awesome </li>
<li>Place polybar folder (or just the files if you have the polybar folder in your .config) in .config/polybar </li>
<li>I have set the default terminal to be kde konsole. Change the line about terminal to point to your terminal of choice.</li>
<code>  terminal = "konsole" </code> <br>

<li>change the line 551 of rc.lua to point to the start.sh address in your polybar folder </li> 
<li>The start.sh script must be executable </li>
<code>  chmod +x start.sh </code><br>
<li> Point feh (at the bottom of lua.rc) to a picture you'd want to use as your wallpaper </li>
<code> awful.spawn.with_shell("feh --bg-scale ~/Pictures/HD/5.jpg") </code>
<hr>
<h2> keep in mind that without polybar you will have no bar at all! </h2>
<img src="https://github.com/wolandark/awesomewithpolybar/blob/main/awesome2.png" width=100% height=100%>

<img src="https://github.com/wolandark/awesomewithpolybar/blob/main/awesome1.png" width=100% height=100%>


