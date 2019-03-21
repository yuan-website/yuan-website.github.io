# yuan-website.github.io

This repository is for the website of Prof. Yuan's group at SHAO (center.shao.ac.cn/fyuan). It hosts some static files and most importantly, the club_activities.html which can be edited here directly and is used to serve website's journal club webpage (http://center.shao.ac.cn/fyuan/journalclub.html).

# For the organiser of Journal club

What needs to be modified in club_activities.html is quite straightforward - just copy the code between '<tr>' and '</tr>' in '<tbody>' and edit it accordingly. For example:
  '''html
  <tr>
					<td>Mar 20, 2019</td>
					<td>2:00 pm</td>
					<td>1608</td>
					<td>XXXxxx XXX</td>
					<td><a href="http://adsabs.harvard.edu/abs/1992ApJS...80..753S5" target="_parent">ZEUS-2D: A radiation magnetohydrodynamics code for astrophysical flows in two space dimensions. I - The hydrodynamic algorithms and tests.</a></td>
	</tr>
  '''
Then commit the changes and Github will do the rest of the work for you.

To make sure that Github really has deployed this page, you can check https://yuan-website.github.io/club_activities.html. Maybe you will need to press Cltr+a in order to see all the texts.

If you have any questions, please feel free to drop me an email and I will be happy to help.
