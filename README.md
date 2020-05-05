<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

# Polygon FA
Polygon FA is a fictional Fund Accounting group within a large Fund Accounting department of an international administrator.
Fund Accounting is the process of calculating a NAV (Net Asset Value) per share for an Investment Fund and publishing that price in the financial markets. Reputational and financial punishments are incurred in the event of late and/or incorrect NAV’s.
The aim of this site is to help ensure that accurate, timely NAV’s are published in times of crisis. Crisis times regularly occur when annual leave is combined with sick leave and is exacerbated due to the current Covid-19 pandemic. In my experience lots of time is lost due to the wrong people being asked questions but still trying to help. More time tends to be lost than saved despite the good intentions.
Help from experienced people will be sought from other teams to assist the team in difficulty. These experienced people will be familiar with 80% of what is required; however, most funds have bespoke processes that the individual will need to become aware of quickly. 
The secondary purpose is so someone outside the group can put positions and names to faces and vice versa.
This site will attempt to provide answers to those questions in a quick, user friendly manner and provide a guide as to who to approach if necessary. It is intended that the user will not be bombarded with information, is only confronted with what they need but can dig deeper with a click if they require more.

UX

This section is also where you would share links to any wireframes, mock-ups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.
### John FA Team Leader
As an experienced FA professional, I have been asked to help the team make their NAV release deadlines for today. They have asked me to do a group of funds with a deadline of 12:00 GMT. I am happy in general with the packs however I need to know any of the funds employ hedging techniques or calculate performance fees and if so; what type? Do any of the funds have bespoke processes?
I want to be 100% certain I have not missed anything so would like to talk to the client owner if possible or the person with the most client experience available.

### Jessica James, Head of FA
I have just joined the company as the new Head of Fund Accounting.
I would like a means to know which clients are serviced in the team, who is in the team and their work biographies. I would like a means to be able to put names to faces and have people comfortable with me. I would prefer to get this information and meet the team informally armed with some information. In my experience lots of people are uncomfortable providing this information in a group meeting scenario.

### Linda Peters, Relationship Manager
A prospective new client has 2 new funds launching and we have been invited to pitch for the administration rights at short notice.
We have identified this team as the team the new funds would go into. We are not the cheapest option for the client, a big part of our pitch will be the quality of our service and experience of our people.  I would like quick, easy access to this information as I only have a short time to prepare. 


##Features

#Existing Features
•	From the landing page John can directly access his client information by clicking on the relevant logo or by clicking the fund-info button at the top of the page. From there he can drill down further if he requires more information. He will also easily see who the best people to talk to are from the progress bars. To note – the bespoke processes are intentionally left as “Lorem Ipsum”. This is to avoid any inadvertent privacy breaches. 
•	Jessica, the new head of FA can easily see what clients are in the team from the 3 logos. She can also see the composition of the team by clicking on the team logo or the org-chart button. From the org-chart page she can easily see the hierarchy of the team and can see their biographies by clicking on the pictures. She will know their names and faces without summoning them for a meeting.
•	Linda, the Relationship Manager can also easily access the org-chart and biographies and use the pages to present to the prospective client in a more visually appealing way than the usual PowerPoint show.

## Technologies Used

* HTML 
* CSS 
* [Canva](https://www.canva.com/) - to generate logos
* [Bootstrap](https://getbootstrap.com/) - for responsiveness, raw code taken for popovers, tables, progress bars etc
* [Google Fonts](https://fonts.google.com/) - Merriweather font used
* [GIT](https://git-scm.com/) - Version Control
* [GitHub](https://github.com/) - to host the repositories for this project and the live 
    website preview
* [W3 Schools](https://validator.w3.org/) - to validate CSS and HTML
* [Autoprefixer](https://autoprefixer.github.io/) - to parse CSS and add vendor prefixes to CSS
* Eventyret's Bootstrap 4 extension `!bscdn` used adding jquery and popper to the above



##Testing

Ran code on Chrome Developer Tools to check responsiveness.
Also entered the site on http://ami.responsivedesign.is/.
Physically self checked that the pages rendered correctly on Chrome, Edge and Internet Explorer browsers on desktop. 
All navigation links were tested on each page to check that they were linked to the correct pages. Likewise clicked on logos, pictures and tables were going to the correct page when clicked.
Group contact information was checked on each summary page to check that all were showing PolygonFA@ffc.com, a group nessage for chat and 1 phone number which it would be intended that all members of the groupw ould be on a pick up list.
All contact information on individualk profile pages were clicked to check that they reflected the correct user eg PhilMoore@ffc.com. 
All the above checks were also physically completed by myself on Samsung A7 in a Chrome browser and an ipad mini on Safari.
1 issue encountered on Chrome Developer tools. The footer buttons appear stacked instead of in a triangle as intended on Iphone 5SE

3 friends also advised that they physically tested layout and links on Chrome browser on a Huawei P3 2019, Samsung s10e and Huawei p20lite.
Links were reported to be working and the footer appearing on all devices as a triangle as intended.
Verified that all progress bar information on individual profile pages corresponded to the summary progress bars on the client pages.

Passed the CSS page and all HTML pages through the W3C validator which shows no issues apart from advice that the import from Google Fonts is not tested.

On all devices the landing page shows 3 navigation links in the header in a triangle which is the theme of the site.
The contact information in the footer also shows 3 buttons in a triangle except on an Iphone 5 SE as mentioned above where they appear to be stacked.

On Mobile and desktop all pages are intended to be triangular, eg on the fund info page the 3 tables are different widths with the bottom table the widest.
The effect is less obvious on mobile with org charts, landing, profile pages appearing stacked, the nav links, footer buttons and Polygon FA logo still somewhat convey the triangular effect.

The design changed as the site was being built. The original landing page was a Microsoft Paint triangle with a little bit of text. This was changed upon reading a slack conversation where it was mentioned that logos coould be made on canva.com (@Eventyret_mentor).
I believe the clickable logos are more effective than text to attract the user to the required information. This advice was given by .

It was intended at the outset that the org chart would have a brief biographies beside some people photo and under others. Upon seeing it on the page I decided it was more in keeping to keep 1 page just pictureswhich invite the user to click if more info was required.
This is more in keeping with my original plan of not bomabrding the user with info that they're not looking for.
My experience in FA tells me that there is so much data available on SharePoint sites that the user gives up and goes to talk to someone as they can't see the wood for the trees.

A similar pattern emerged with the fund info-page. I decided to give each client their own page after one summary page appeared too packed with info.

Bootstarp Modal and HTML to send an email were considered for the footer links. In the end however I decided to go with Bootstrap popovers on all 3 for consistency on this static project.



## Deployment

To deploy this page to GitHub Pages from its [GitHub repository](https://d0nni387.github.io/The-Quiz-Hub/), the following steps were taken: 

1. From the menu items near the top of the page, select **Settings**.
2. Scroll down to the **GitHub Pages** section.
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
5. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 

### How to run this project locally

To clone this project from GitHub:

1. Under the repository name, click "Clone or download".
2. In the Clone with HTTPs section, copy the clone URL for the repository. 
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/D0nni387/The-Quiz-Hub.git
```
6. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

**Credits

Inspiration for the project came from my experiences working for large international fund administrators PNC Bank, BNY Mellon and Northern Trust.
How to use the Bootstrap 4 grid - Demo site by Anna Gilhespy on You Tube was incredibly useful in helping to get to grips with Bootsrap.
I attended 2 slack calls hosted by Richard Wells which were also very useful.
Also reading old and new slack conversations with the whole community was a great help in solving problems encountered and problems I wasn't aware I had, in particular the contributions of @Eventyret_mentor and @anna_ci 
are very on point.
I would also like to thank my mentor Guido Cecilio.