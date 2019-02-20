## Terminology

<span/>

-   **Candidate** - someone who wishes to be certified as a FIWARE Expert
-   **FIWARE Expert** - someone registered as competent in FIWARE technologies - i.e. a successful candidate
-   **Examiner** - A registered FIWARE Expert who has been accepted to judge FIWARE Expert certifications
-   **Trainee Examiner** - A registered FIWARE Expert who wishes to become an Examiner
-   **Standards Committee** - A subgroup of “ancient masters” who define the current examination process. When setting
    up the board, a number of people must be automatically assumed to be competent before others can apply.
-   **Body-of-Work** - A series of PRs on git repos, a publicly available slideset from presentations on FIWARE or
    webinar or other software, hardware or documentary evidence.

## The Board of Examiners

-   Candidate Examinations are to be judged by a board of three examiners

In the ideal case, any decisions made by the board will be unanimous, however since there are an odd number of board
members any decisions will always have a majority and minority. This can then be discussed.

-   The board of examiners are chosen at random from the current list of examiners

Randomizing the board to avoid bias or collusion.

-   Ideally each board of examiners should consist of examiners coming from separate institutions, however at a minimum,
    no more that two examiners may come from a single institution

An exception can be made for a board containing three examiners associated with the FIWARE Foundation itself

-   No more than one examiner may be associated with the same institution as the candidate

An exception can be made for a board containing two examiners associated with the FIWARE Foundation itself

-   Additional Examiners and Trainee Examiners may sit-in on the board as non-voting members. They are expected to take
    part in the board discussions and are also expected to mark candidates but their marks are not considered for the
    final result

This allows any competent FIWARE expert to review the examination process of any board, It also helps to keep the
examination procedure open and transparent, and ensures that the standards are consistent

## Candidate Grading

-   A current marking sheet and a set of questions will be defined by the standards committee <br/><br/>
-   Each mark on the mark sheet will consist of two types of sections:
    -   General
    -   Essential <br/><br/>
-   The following sections have been defined:
    -   Discussion of the body-of-work
    -   Discussion on correct Architecture of a “Powered by FIWARE” solutions/platform
    -   Discussion on NGSI interfaces
    -   Discussion on “FIWARE-ready” technologies
    -   Discussion on the FIWARE Catalogue <br/><br/>
-   Each section will be graded over a series of subsections. Examiners will be provided with a marking sheet for each
    examination. <br/><br/>
-   During each section of the examination, each examiner should grade the section as A- Excellent Pass, B- Good Pass,
    C- Pass, D- Borderline or E- Fail or along with comments justifying their decisions <br/><br/>
-   At the end of the examination, the board should discuss the results come to a common conclusion of each section and
    provide an overall mark of PASS or FAIL
    -   General sections may be passed with an overall mark of A or B, C - some subsections could be rated D
    -   Essentials sections must be passed with a mark of A or B, C - no subsections can be rated D <br/><br/>
-   The result of the grading should be sent to the FIWARE foundation

The idea here is that a core standards committee of “ancient masters” can maintain and update a standard as changes are
made to the overall goals and ideas of the FIWARE Foundation. The examiners are applying the standard based on a sample
list of questions.

Which sections are essential and which are general is up for discussion

The range A-E allows for more fine distinctions than just pass fail and ensures trainee examiners have a common
understanding of what is and what isn’t accepted.

## Candidate Examination Procedure

-   A Candidate must submit a body of work for review which defines their basic competence in FIWARE

There should be a small but significant barrier to entry.This could be a series pull requests on git repos, a publicly
available slideset or webinar or other documentary evidence.

-   Each item from the body of work should be available publicly and linked to the online presence of the candidate

This is a simple quality check. If I have an online presence and I link items which are of poor quality, my reputation
will suffer

-   If the body of work is not public, the examiners must sign a non-disclosure agreement, and the discussion of the
    body-of-work may take place in camera.

As discussed in July, some candidates may not be giving presentations or contributing to Open Source directly or may
only be able to provide sufficient proprietary code. I would expect this to be a minority of cases.

-   The examiners should review the body of work prior to the examination and decide if it is sufficient for the
    candidate to proceed. If it is not judged to be sufficient, amendments/additions should be requested prior to the
    examination

We need to make sure there is enough to discuss - this is just a check on the “small but significant” barrier and it
would be pointless to proceed if someone would be rejected at the first hurdle. The review doesn’t need to be much. As I
pointed out in July, one simple PR is not sufficient. Slides from one 30 minute presentation on FIWARE probably is
though.

-   The F2F examination will consist of the following parts (as defined by the committee):
    -   Discussion of the body-of-work
    -   Teaching/ Demonstration of one or several aspects of FIWARE
    -   Discussion on correct Architecture for “Powered by FIWARE” solutions/platforms
    -   Discussion on NGSI interfaces
    -   Discussion on “FIWARE-ready” technologies

See Candidate Grading for more details

This list of areas to examine is a proposal, but should be defined by the standards committee. I am assuming that an
expert will need to show competency across all aspects of FIWARE, but the examination will only have time to test
certain areas. It should be decided which of the aspects are considered essentials and which can be graded less
harshly - for example I see body-of-work as not as significant as teaching/demoing

-   The Discussion of the body-of-work is expected to take 10 minutes. The candidate will field questions about the
    body-of-work submitted and how it relates to FIWARE. The criteria for marking will include
    -   Is the body-of-work significant?
    -   Does the body-of-work fit within the FIWARE ecosystem?
    -   Does the candidate show understanding of how and where their work fits within FIWARE

This is ensuring that a candidate understands what FIWARE is and has been able to make a contribution to FIWARE somehow.

-   Teaching/ Demonstration of one or several aspects of FIWARE is expected to take 20 minutes. The candidate will
    describe and demonstrate on screen and answer randomly selected questions from a previously published list which
    covers common FIWARE use-cases (see below). It is assumed that a reasonable baseline for the question will be
    provided rather than starting from a blank canvas. The criteria for marking will include
    -   Does the candidate understand which FIWARE components should be used?
    -   Can the candidate explain how different enablers can be provisioned?

This assumes that a FIWARE expert has at least some knowledge across all enablers. The list of questions is public and
can be practiced by the candidate (and thus learns FIWARE). I’d assume that demo on the screen should be sufficient -
basically someone talking through what they would be doing. There should be a discussion on what materials should be
available and what if any should be banned.

-   Discussion on correct architecture for “Powered by FIWARE” solutions/platforms is expected to take 10 minutes. The
    candidate will be given a description of one or more fictitious problem and is expected to define how and where
    Generic Enablers should be used to develop a smart solution which solves the given problem. It is expected that the
    candidate should be able to identify a variety of forms of context data and be able maximise the correct use of
    context throughout the system

This assumes the FIWARE Expect can correctly design an end-to-end system using FIWARE. Example products should be based
on real-life examples such as IMPACT Growth success stories or Smart Cities. It should also discuss what processing
should be done where. Define the flow of context data through the system and which elements would not benefit from the
addition of FIWARE.

-   The Discussion on NGSI interfaces is expected to take 5 minutes. The candidate will need to be able to show
    competency in the understanding of Core context

At the moment this would be NGSI v2, but could include LD at a later date. Questions would include how to design a data
model, what makes a good entity, what fields should metadata etc, principles of REST etc. Although this is basic stuff
it has been added as a separate section since isn’t covered directly in the preceding sections.

-   The Discussion on “FIWARE-ready” technologies is expected to take 5 minutes. The candidate will need to be able to
    describe what would be sufficient for a device to be FIWARE ready and what does and doesn’t count as Powered by
    FIWARE.

Given that one of the aims of the Experts Certification program is to be able to certify IoT devices, it makes sense
that part of the procedure is to run a certification test for FIWARE-ready IoT devices. The discussions can be based on
real devices and/or passing/failing candidates from impact Growth and so on. It should be possible for a candidate to
recognise and describe the minimum threshold.

## Trainee Examiners

A FIWARE Expert may request to be join to the board of examiners. The trainee examiner should be invited to join a
series of FIWARE Expert boards and take part in discussions and markings as a non-voting member. Regarding the
transition of trainee examiner to examiner, this should typically occur after a set number of similar markings to the
rest of the board (e.g. 3 non-voting boards with similar marks should be sufficient.)

## Standards Committee

The standards committee shall consist of a core group of six FIWARE Examiners of long standing. At least two of the six
members shall come from the FIWARE foundation

Appointments to the standards committee shall be ratified by the FIWARE TSC

The standards committee may co-opt other FIWARE Experts to help draft and maintain the standards as necessary

For example if a new incubated enabler is added to the list, the list of questions should be reviewed or amended to
ensure that the new GE is covered by the list of questions. It may help to get the expert in that area to help draft the
relevant questions
