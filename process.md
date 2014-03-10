#IBMStreams Process
The IBMStreams organization within www.github.org is an IBM initiated open source organization focused on extending the programming resources for IBM InfoSphere Streams product.  We actively encourage anyone interested in IBM InfoSphere Streams to participate and contribute to the projects within this organization.  

##Managing Committee
The IBMStreams organization has a managing committee that oversees the projects operating within the IBMStreams organization.  This committee is made up of persons with a vested interest in the success of IBMStreams.  The committee responsibilities include, managing committer rights, managing the projects, managing the proposals process and generally ensuring that the project is well run and that contributors are able to function in a productive manner.

##Proposals
We are seeking proposals for new toolkits or operators for IBM InfoSphere Streams.  The process for a new proposal is:

1. Open a new Issue in the IBMStreams/toolkits repository.  Give it a meaningful title and add the proposal label to the issue.
2. The proposal will be discussed on the IBMStreams/toolkits wiki.  A new page will be created for each proposal request.
3. Once the proposal has been discussed, there will be a vote by IBMStreams/toolkits managing committee recorded in the proposal Issue.
4. Outcomes are:
a) proposal accepted, new repository created and project started.
b) proposal accepted, work assigned to an existing project.
c) proposal rejected.  Proposals will be accepted for IBMStreams if they are of value to a broad audience in the IBMStreams community.  Some projects  may be recommended for incubation outside the IBMStreams community.  

##Committers
The IBMStreams organization will create an initial set of committers when a repository/project is created.  Each repository will have a team created called *reponame*Committers and these people will have write access to the repository.   To become a committer the process is:

1. Establish a good track record of contributions and have a signed individual contributor agreement in place.
2. Be nominated by an existing committer via an Issue titled: Commiter Nomination: *persons name*
3. Existing commiters will then vote in the Issue and 2/3 positive votes are required to be a comitter
4. IBMStreams management committee reserves the right to revoke committer status for individuals that are deemed to not be acting in the best interests of the project.

##Process
1. Issues will be tracked using github issues. 
2. The project github wiki will be used for communication of ideas, designs, meeting minutes, schedules etc...
 
####Branches
Main branch will be called master and is considered to be deployable.  This branch is expected to work and anything pushed to that branch is consider to work.  Care will be taken to ensure that this branch is always stable, works and new work can be branched from it.

Feature or work branches should be created from the main branch and given a meaningful title.  As work proceeds in these branches changes should be regularly pushed to the server in order for people to see the progress as it is being made.  Once a feature/work branch is ready to merge with the master branch a pull request should be created and the project committer(s) will review the changes and update the main branch.

##Development Environment
You can download the IBM InfoSphere Streams Quick Start Edition which has no charge for non-production use from here: [http://www-01.ibm.com/software/data/infosphere/streams/quick-start/downloads.html](http://www-01.ibm.com/software/data/infosphere/streams/quick-start/downloads.html)

For more information on getting started with Streams go to [http://ibm.co/streamsdev](http://ibm.co/streamsdev)


