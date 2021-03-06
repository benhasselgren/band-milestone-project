<h6>Ben Hasselgren</h6>
<h1> User Centric Frontend Development Milestone Project  </h1>

<a href="https://benhasselgren.github.io/band-milestone-project-pages/" target="_blank"> Click here to view website</a>

<h3>Purpose</h3>
<p>
    The purpose of this project is to create a website for the Monkees that
    allows them to share past music with fans and allow fans to keep up to date with what the band are
    doing and also allow fans to hire them for special events. The website also had to be static and resposnive to
    different devices
</p>

<h3>Functionality/Technologies</h3>
<p>
    This website has lots of functionality. One functioniality is that it's resposnive. It has responsive elements
    such as the navbar and sections in the webpage that adapt to make the website more user-friendly and reliable.
    It also has functionality because of the different webpages. The navbar allows the user to travel to different
    webpages to view information about the monkees. These different web pages break the information up and
    make the website easier to use and understand for the user.
</p>
<p>
    The website used code from two previous websited that the developer made while following some previous tutorials with
    the code institute. It was the structure and initial style copied from these two websites and then the code was added to and changed to make
    match the brief.
</p>

<p>   
    There is some different technologies used in this project. Bootstrap was used for the structure of the web pages(html).
    Using Boostraps classes, tables and grids were made to give the website a nice layout with a responsive design. Bootstrap's 
    glyphicons were also used for some of the icons on the website. Google fonts were also applied in the header to give all font a Roboto
    font-family. Bootstrap's JavaScript was also linked at the bottom of the webpage to apply functionality
    to the webpage but in this milestone, that javascript doesn't have to be edited or looked at.
</p>

<h3>Testing</h3>
<p>
    This website was tested using Chrome development tools. The website was created on a design made
    by wireframe diagrams using Balsamiq. It was important to make sure the final version looked like the designs so
    Chrome development tools were used to test out all the features and see if they responded correctly and looked 
    right. Once mistakes/changes were made with Chrome, the code was copied to the actual code to fix the issue permanently.
</p>
<p>
    I also did some manual tests. Here are a couple examples
</p>
<table>
    <tr>
        <th>Test</th>
        <th>Input</th>
        <th>Expected output</th>
        <th>Output</th>
        <th>Pass?</th>
    </tr>
    <tr>
        <td>Testing to see if the correct page is shown</td>
        <td>Clicked About link in navbar</td>
        <td>render about.html</td>
        <td>render about.html</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Testing to see correct modal is shown for bandmember</td>
        <td>Click on Davy Jones read more button</td>
        <td>Davy Jones modal should appear</td>
        <td>Davy Jones modal appeared</td>
        <td>Yes</td>
    </tr>
</table>
<h3>Deployment</h3>
<p>
    This website was deployed to github pages. It was very easy to set up as the website has been put in a github repository from the start
    so all that had to be done was activate github pages and point the source to the master branch. Only one issue was found when deploying.
    This issue was that some of the images couldn't be found. This issue was identified as being because "../" was used before some of the images.
    This worked locally but in git hub pages, meant that the url for the images were being added to the github pages url and making an incorrect path.
</p>
