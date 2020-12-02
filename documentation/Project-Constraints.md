[Home](../README.md) > Project Constraints

# Project Constraints

<table>
    <tr>
        <td><b>General Constraint</b></td>
        <td><b>Specific Constraints</b></td>
        <td><b>Impacts</b></td>
        <td><b>Solutions</b></td>
    </tr>
    <tr>
        <td rowspan="3">Third-Party</td>
        <td>Azure Services from Microsoft</td>
        <td>We are reliant on Azure’s services and their uptime consistency.</td>
        <td>We should structure the application so that it can be deployed to other services or in other ways.</td>
    </tr>
    <tr>
        <td rowspan="2">The libraries we plan to use, especially React and three.js</td>
        <td>If the libary features we use are changed in an update, parts of our application may break.</td>
        <td>We need to make sure we use a package lockfile, and update the libraries and packages only when ready necessary.</td>
    </tr>
    <tr>
        <td>Some package options may seem great, but are lacking in community support.</td>
        <td>We should choose popular packages and libraries, so we can find solutions to problems we may run into online</td>
    </tr>
    <tr>
        <td rowspan="2">Time</td>
        <td>Project is set to be completed within the developers' senior year.</td>
        <td>This sets a hard due date for delivery, which limits the project to what can be done in that time frame.</td>
        <td>We should ensure date estimates for tasks are made with this delivery date in mind.</td>
    </tr>
    <tr>
        <td>Work on the project must be juggled with other schoolwork.</td>
        <td>Limits team members’ time to work on the project.</td>
        <td>We should keep the project simple wherever possible, so that the project’s workload does not conflict.</td>
    </tr>
    <tr>
        <td>Complexity</td>
        <td>Scope creep, poor-quality code in important components, or trying to add too many features at once can all complicate the project.</td>
        <td>Complications will slow down development and push back delivery dates as we try to fix it or find a work-around.</td>
        <td>We need to minimize scope creep, focus on our key features, follow good practices, only take on one task at a time, etc.</td>
    </tr>
    <tr>
        <td>Team Size</td>
        <td>There are only two developers, and both have workloads outside of this project.</td>
        <td>Limited dev-power for the majority, if not all, of the project’s timespan. This limits number of features that can be implemented: only 2 things can be worked on at once, etc.</td>
        <td>We have to make sure that project completion stays feasible for a team of 2. This can mean limiting the planned feature set, simplifying existing features, etc.</td>
    </tr>
    <tr>
        <td rowspan="2">Technical Expertise</td>
        <td>Josh’s inexperience with some of the resources being used for project design, and the learning curve to get up to speed.</td>
        <td>Some of Josh's tasks may be slower to start, which could delay other features that depend on those tasks.</td>
        <td>We should plan tasks to ensure Josh's early tasks give him time to get the experience he needs.</td>
    </tr>
    <tr>
        <td>The developers' lack of experience working with 3D models on the web, specifically working with three.js or related libraries.</td>
        <td>Tasks involving 3D models may go over estimates, leading to delayed delivery.</td>
        <td>We should focus on the key parts of features involving 3D models, cut down on uncessary additions, leverage existing libraries and tools as much as possible, etc.</td>
    </tr>
</table>
