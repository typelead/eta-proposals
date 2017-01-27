# Eta Proposals

This repository contains Eta Proposals (EPs) that specify precise changes to any
of the following:

- compiler
- runtime system
- standard libraries
- [eta-lang.org](http://eta-lang.org) website
- package manager
- community

that have a significant impact on the user experience of the Eta programming 
language, associated tools, and libraries.

# Starting an EP

When you have an idea for a major change and you are interested in writing a
detailed proposal for it, you proceed as follows:

1. Post on the various communication channels to solicit feedback on the initial
   sketch of your idea, such as:

   - [Gitter](https://gitter.im/typelead/eta)
   - [Slack](https://www.hamsterpad.com/chat/eta-lang)
   - [Google Group](https://groups.google.com/forum/#!forum/eta-discuss)
   
   This step is not required, but it is a good way to test the waters before 
   devoting time to contemplating a design and/or implementation plan for your 
   idea.

2. If the feedback seems pretty positive, file an issue here and the core Eta
   developers and other stakeholders will provide further feedback. Once it's clear
   that the proposal is desirable and feasible, a member of the TypeLead 
   organization will give the go ahead to write a detailed proposal. 
   
3. To write a proposal, you should:
    
   a. Fork this repository.

   b. Copy the template `proposals/EP000-template.md` to 
      `proposals/EP000-[proposal-title].md` where `[proposal-title]` should be an
      informative but concise title that describes the contents of the proposal.

   c. Address the questions in the template in a clear and detailed manner.

   d. Submit a pull request once you are done.

# Lifecycle of an EP

Once you have submitted a pull request, the Eta Proposal Process starts.

1. Your proposal will receive feedback from the community and you should revise the
   proposal accordingly. TypeLead members may organize meetings over Skype/Hangouts
   if the proposal has large tradeoffs.
  
2. If it is clear the proposal will not be beneficial to the Eta ecosystem, a 
   TypeLead member will close the pull request with a reason.
   
3. If it is clear that the proposal, if implemented, can improve the user 
   experience of the Eta ecosystem, and the proposal is complete, a TypeLead 
   member will merge the pull request.
   
# Implementing an EP

Once a proposal has been merged, it can be in one of two states (indicated by a 
label): **active** or **postponed**.

If it is **active**, it means the EP can be implemented in the near future. 
Proposals in this category will also be assigned one of three priority labels:

- **low**: Indicates that the proposal is relatively unimportant and can be
  implemented at any time.

- **medium**: Indicates that the proposal may be implemented in the coming weeks.

- **high**: Indicates that the proposal may be implemented within the next couple 
  of days or within the next week.

If it is **postponed**, it means the EP will not be implemented in the near future,
but the status may change to **active** if conditions permit.

Moreover, if an implementation plan has not been specified in the proposal, a 
TypeLead member will provide a brief sketch of the implementation plan.

# Commenting on an EP

When commenting on a proposal, the following guidelines should be followed:

- **React to posts.** Use GitHub's reactions to posts if you have nothing 
  substantial to say.

- **Be respectful about potential flaws.** Do not try to bring down the proposal
  creator or other commentors. 

- **Give a proper arguments.** Your arguments should be straight to the point.

# Questions

If you have any questions about the process, please:

- file an [issue](https://github.com/typelead/eta-proposals/issues/new)

- discuss with us on [Gitter](https://gitter.im/typelead/eta) 
