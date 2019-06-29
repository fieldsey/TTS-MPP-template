# TTS-MPP-prototype
A prototype repository, outlining how the TTS MPP would look in practice. Don't forget to take a look at the repository that explains [the TTS MPP process](https://github.com/fieldsey/TTS-MPP-process/). Please give any and all feedback you have through our "[indefinite RFI](https://forms.gle/Lo38qwjTyE7hCPUG7)", which we will never close. Thank you!

## Opportunities
There are currently no user stories that need assistance. When a user story is ready to be posted, it will be posted to this repo's [Issues tab](https://github.com/fieldsey/TTS-MPP-prototype/issues) and follow the following format:

> ### {{User-Story-Title}}
> 
> * **Link to Issue:** [Issue number XX](URL)
> * **When the Q&A period will close:** MONTH DD, YYYY at 5:00pm, eastern
> * **When the responses must be submitted:** MONTH DD, YYYY at 5:00pm, eastern

## Workflow
When awarding a new microconsulting engagement, these are the steps we follow:

* When we have a user story that needs to be completed, we will create an Issue in the repo. The solicitation period opens when the Issue is created.
* For each user story, contractors should post any questions they have or clarifications they’d like in the comments of the issue. In an effort to promote consistency and transparency, questions received via any other medium will not be answered.
* Each Issue will contain a link to a Google Form that will be used to collect vendor’s responses. We will not be able to consider responses sent via any other medium.
* When the question and answer and/or response periods close, we will comment on the Issue indicating as such. The Issue itself will be left open until an award is made.
* When an award is made, we will comment on the Issue, indicating to who and for how much.
* Upon award, a directory will be created in the repository named `yyyy-mm-dd {{User-Story-Title}}`, where `yyyy-mm-dd` is the date that the award was made (so that they will be shown in order) and `{{User-Story-Title}}` is the name of the Issue the folder is associated with.
* Inside this directory, a `README.md` file will be created, including the information from the Issue as well as metrics related to the number and value of the responses provided. An empty directory called `Deliverables` will also be created.
* In a comment in the user story’s Issue, we will link to the corresponding `README.md` file for future reference then close the Issue. When the Issue is closed, the award has been issued.

When a vendor submits a deliverable, these are the steps we follow to accept it:

* To submit their final deliverables, vendors should fork the TTS MPP public repo then create a pull request back to the master branch of the TTS MPP public repo with the deliverables added in `yyyy-mm-dd {{User-Story}}/deliverables`.
* We will review the deliverables, and if they meet the Definition of Done outlined in the Issue, we will merge the request, indicating acceptance. Should there be any questions or issues related to the deliverables, we will post them as comments in the merge request itself.
* All deliverables following this process will be open source in accordance with the [18F Open Source Policy](https://18f.gsa.gov/open-source-policy/). Any deliverable not intended to be viewed publicly will be specified in the user story’s Issue and will follow a different process, determined on a case-by-case basis.

## Early end to an auction
We reserve the right to delete a competition, prohibit responses, and forego delivery at any point in the process outlined above. We will not issue payment to a contractor until that contractor's code has been deemed acceptable per the requirements outlined in the Issue and their pull request has been merged.

## Participating
The requirements to participate are outlined in [PARTICIPATING.md](https://github.com/fieldsey/TTS-MPP-template/blob/master/PARTICIPATING.md).

## Source-selection method
We use competitions to determine the source for any given purchase. Eligible contractors can place bids on a competition during its bidding period. Once that period ends, the winner will be selected by the person who initiated the competition based on the best perceived combination of price and perceived risk, where evidence provided with the bid will be used to help assess risk. For example, a bidder may include with their bid a pointer to previously published work they completed which demonstrates they have the skills and knowledge to tackle the current work. This reduces the perceived risk that the bidder won't be able to deliver on the requirements.

In the event that a winner is either (a) unable to deliver on a competition by the delivery deadline assigned to them or (b) delivers code that is deemed unacceptable, we reserve the right to reject the work, choose a new winner from previous bidders on the competition, or re-run the competition.
