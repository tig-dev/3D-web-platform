[README.md](../README.md) > Project-Constraints.md

# Project Constraints

<table>
    <tr>
        <td><b>Constraint</b></td>
        <td><b>Description/Sub-Constraints</b></td>
        <td><b>Impacts</b></td>
        <td><b>Solutions</b></td>
    </tr>
    <tr>
        <td rowspan="3">Third-Party</td>
        <td>Microsoft for Azure</td>
        <td>We’re reliant on Azure’s services and uptime consistency.</td>
        <td>Make sure the project can stand on another service if necessary.</td>
    </tr>
    <tr>
        <td rowspan="2">The libraries we plan to use, especially React and Three.js</td>
        <td>Reliant on features that exist in the version we use when starting, if features change, it can break the application.</td>
        <td>Make sure we lock down what version we use, and update the libraries and packages only when ready to work with the changes.</td>
    </tr>
    <tr>
        <td>Some package options may not be used much, so resources on them would be sparse.</td>
        <td>Choose commonly-used packages and libraries.</td>
    </tr>
    <tr>
        <td rowspan="2">Time</td>
        <td>Set to be completed within the year-long period.</td>
        <td>Set due date for delivery, which limits the project to what can be done in that time frame.</td>
        <td>Task date estimates should be done with the hard delivery date in mind.</td>
    </tr>
    <tr>
        <td>Must be juggled with other schoolwork.</td>
        <td>Limits team members’ time to work on the project.</td>
        <td>Keep the project simple where possible, so that the project’s workload does not heavily conflict with others.</td>
    </tr>
    <tr>
        <td>Complexity</td>
        <td>The project can potentially become very complicated, which would slow down development and push back delivery dates. Several factors could complicate it, such as scope creep, poor-quality code in heavily relied-upon components, or trying to implement too much at the same time.</td>
        <td>Depends on the complicating factor, but most will slow down development as we try to fix or work around it.</td>
        <td>Minimize/disallow scope creep, focus on key features, follow good practices, keep focused on one task at a time, etc.</td>
    </tr>
    <tr>
        <td>Team Size</td>
        <td>There are only two team members, who have workloads outside of this project.</td>
        <td>Limited dev-power for the majority, if not all, of the project’s timespan. LImits number of features that can be implemented: only 2 things can be worked on at once, etc.</td>
        <td>Project completion must stay feasible for a team of 2. This can mean limiting the planned feature set, simplifying existing features, etc.</td>
    </tr>
    <tr>
        <td rowspan="2">Technical Expertise</td>
        <td>Josh’s inexperience with resources being used for project design and the learning curve to get up to speed.</td>
        <td>The tasks assigned to Josh may be slower to start, which may delay other features that depend on those tasks.</td>
        <td>Plan tasks so that any that depend on getting past this learning curve are set to be worked on after experience is gained.</td>
    </tr>
    <tr>
        <td>Lack of experience working with 3D models on the web, specifically working with three.js.</td>
        <td>Tasks involving 3D models may go over estimates, leading to delayed delivery.</td>
        <td>Focus on key parts of features involving 3D models, leverage existing libraries and tools as much as possible, etc.</td>
    </tr>
</table>

