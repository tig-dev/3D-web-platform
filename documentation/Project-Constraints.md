[README.md](../README.md) > Project-Constraints.md

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
        <td>We should make sure the project can stand on another service if necessary.</td>
    </tr>
    <tr>
        <td rowspan="2">The libraries we plan to use, especially React and three.js</td>
        <td>We are reliant on features that exist in the version we use when starting, if features change, it can break the application.</td>
        <td>We need to make sure we lock down what version we use, and update the libraries and packages only when ready to work with the changes.</td>
    </tr>
    <tr>
        <td>Some package options may not be very popular, so community resources on them would be sparse.</td>
        <td>We should choose commonly known/used packages and libraries.</td>
    </tr>
    <tr>
        <td rowspan="2">Time</td>
        <td>Project is set to be completed within the year-long period.</td>
        <td>Hard due date for delivery, which limits the project to what can be done in that time frame.</td>
        <td>We should ensure task date estimates are done with the hard delivery date in mind.</td>
    </tr>
    <tr>
        <td>Work on the project must be juggled with other schoolwork.</td>
        <td>Limits team members’ time to work on the project.</td>
        <td>We should keep the project simple where possible, so that the project’s workload does not heavily conflict with others.</td>
    </tr>
    <tr>
        <td>Complexity</td>
        <td>The project can be complicated by issues like scope creep, poor-quality code in heavily relied-upon components, or trying to implement too much at the same time.</td>
        <td>Complications will slow down development and push back delivery dates as we try to fix or work around it.</td>
        <td>We need to minimize/disallow scope creep, focus on key features, follow good practices, keep focused on one task at a time, etc.</td>
    </tr>
    <tr>
        <td>Team Size</td>
        <td>There are only two team members, who have workloads outside of this project.</td>
        <td>Limited dev-power for the majority, if not all, of the project’s timespan. Limits number of features that can be implemented: only 2 things can be worked on at once, etc.</td>
        <td>We have to make sure that project completion stays feasible for a team of 2. This can mean limiting the planned feature set, simplifying existing features, etc.</td>
    </tr>
    <tr>
        <td rowspan="2">Technical Expertise</td>
        <td>Josh’s inexperience with some of the resources being used for project design, and the learning curve to get up to speed.</td>
        <td>The tasks assigned to Josh may be slower to start, which may delay other features that depend on those tasks.</td>
        <td>We should plan tasks to ensure Josh's early tasks give him time to get the experience he needs.</td>
    </tr>
    <tr>
        <td>The team's lack of experience working with 3D models on the web, specifically working with three.js or related libraries.</td>
        <td>Tasks involving 3D models may go over estimates, leading to delayed delivery.</td>
        <td>We can focus on the key parts of features involving 3D models, leverage existing libraries and tools as much as possible, etc.</td>
    </tr>
</table>
