# Worksheet 6: Version Control

## Instructions

- Due on Tuesday (Nov, 14th) at Midnight
- Copy the worksheet, answer the questions, and SUBMIT TO [OUR GITHUB
  REPOSITORY] via pull request (see question 8).
- It is recommended that you Complete the GitHub "Hello World" tutorial before
  starting with this worksheet.

aa3798

	1.	In your own words, what is version (or source) control?

In my own words: version control is a sophisticated elaboration of the “save as” function that is found in most document editors. Where the “save as” command produces an entirely new document each time it is executed, version control collates saved versions, explicitly grouping them as chronological iterations of an original file. Version control allows the user to easily visualize differences between these saved iterations, which are presented on a timeline/“document tree.” It also allows the user to easily reconcile these variances across different iterations of the document, which might come about through collaboration or editorial input. 

Version control is significant because, as a tool of digital information management, it helps writers manage the confusion and uncertainty arising out of the fact, long ago recognized by literary theory, that texts are never truly stable, immutable, singular, or bounded entities. Presenting a text as a cloud of iterations that spread out both on diachronic and synchronic axes, version control allows the user to keep track of a textual genealogy that would otherwise be lost. 
 
	2.	Explain the difference between Git and GitHub.
  
  Git is a version control program that runs locally. Operating on a single user’s machine, it allows one to track the changes one makes to a particular document. GitHub, on the other hand, is a networked version of Git. It stores the iterations of a document on a remote server. Github allows the user to download an iteration, make changes, and upload that document as new iteration. This new iteration can exist in parallel to the original iteration, or else it can be ultimately merged with that original iteration. Github is especially useful for collaboration because it allows multiple users to simultaneously download the master document, make changes, and then upload their iterations for review, comparison, and potential reconciliation.
 
	3.	In a few sentences, explain what a "commit" is.
  
A commit is a “save as” of a document that is being managed with Git version control. Version control allows the user to easily visualize and reconcile the differences between commits. Each commit includes a “note” describing the changes that were made in the new iteration of the document being produced.

	4.	What is a "branch" in Git terms?

A branch is a new iteration of a document created by a collaborator on that document. By making a branch, the collaborator creates a duplicate document on which changes can be made that might or might not later be integrated into the master document. Each branch can have branches of its own, which can take the document in divergent directions. As a document accumulates branches, these can be visualized in a “document tree.”

	5.	What is a repository? Explain what happens when you "push" to and "pull" from a repository.
  
  A repository is a folder containing all the necessary information required for the user to read and interact with a version-controlled document. It includes all of the divergent iterations (“commits”) of that document which existed throughout the history of that document’s existence, allowing the user to form branches off of any of those iterations and take the document in new directions. When you push to a repository, you upload a “commit” of your document to the repository, so that your commit will exist as a branch in that repository that might subsequently be merged with the master document. When you pull from a repository, you download the contents of that repository to your machine so that you may create a new branch of the project. You can later push your changes to the original remote repository if you have the appropriate permissions in that repository. If you do not have those permissions, you can make a “pull request” of that original repository, and your changes will be reviewed by an administrator before being pulled into that repository.  

	6.	What is involved in the "clone" operation?
  
The clone operation creates a copy of a remote repository. This copy is owned by the user executing the command, allowing that user to access and modify anything in the copied repository. This operation is useful for allowing the user to take the project in a different direction, starting at any particular point in the document’s history. The clone operation is also known as “forking” a repository.

	7.	Find an example of Git being used for a peer production project. In several paragraphs answer the following: Who are they? What do they do? Who maintains the repository? What are the rules for contributing?
  
I found that Git is used to manage the development of Audacity, a popular open source audio editor licensed under the GNU General Public License. The Github repository for the Audacity source code can be found here: https://github.com/audacity/audacity Audacity was created in 1999 by Dominic Mazzoni, who has since retired from the project. Audacity is now in the hands of a small group of lead developers that volunteer their time and effort to maintain the project. These developers include, as listed on the project’s Github page, Paul Licameli, James Crook, and Martyn Shaw. However there also appears to be a larger, more informal community of Audacity developers that correspond on a developers’ mailing list <https://sourceforge.net/projects/audacity/lists/audacity-devel>. On this mailing list, the developer community discusses the goals for Audacity and development needs. The lead developers also periodically organize “hackathons” to promote further Audacity development. Because none of the lead Audacity developers “owns” the project and none of them are paid, anybody could conceivably work their way into the “inner circle” simply by virtue of devoting enough time and energy to the project. 

The lead Audacity developers state that they welcome pull requests to the Audacity Github repository, although they advise that major pull requests be first discussed on the mailing list. Pull requests are reviewed by lead developers and are either accepted, rejected, tabled, or sent back for revision. Sometimes the merits of pull requests that the Github project receives are discussed on the mailing list. Examining the history of pull requests for Audacity, it appears that many recent contributions are small translation corrections. These apply to versions of the software that operate in languages other than English. While it seems that small translation correction pull requests are often accepted, many others are put up for discussion in a special Audacity translation mailing list that is also maintained by the Audacity developers. 

	8.	Submit this worksheet (in .txt or .md plain text format) by filing a pull request to our Github repository. 
