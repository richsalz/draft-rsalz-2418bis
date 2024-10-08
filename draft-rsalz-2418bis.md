---
title: "IETF Working Group Guidelines and Procedures"
abbrev: "wg-guidelines"
docname: draft-rsalz-2418bis-latest
submissiontype: IETF
category: bcp
ipr: trust200902
area: General
workgroup: xxxxxxx
keyword: process
stand_alone: yes
smart_quotes: no
obsoletes: 2418, 3934
updates: 7475, 7776, 8717, 9141
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: R. Salz
    name: Rich Salz
    organization: Akamai Technologies
    email: rsalz@akamai.com
 -
    ins: S. Bradner
    name: Scott Bradner
    organization: SOBCO
    email: sob@sobco.com

venue:
 repo: https://github.com/richsalz/draft-rsalz-2418bis.md

normative:

informative:
  bis2026: I-D.draft-rsalz-2026bis

--- abstract

The Internet Engineering Task Force (IETF) has responsibility for
developing and reviewing specifications intended as Internet
Standards. IETF activities are organized into working groups (WGs).
This document describes the guidelines and procedures for formation
and operation of IETF working groups. It also describes the formal
relationship between IETF participants WG and the Internet Engineering
Steering Group (IESG) and the basic duties of IETF participants,
including WG Chairs, WG participants, and IETF Area Directors.

This document obsoletes
RFC2418, and RFC3934.
It also includes the changes from RFC7475, and with {{bis2026}}, obsoletes it.
It also includes a summary of the changes implied in RFC7776 and
incorporates the changes from RFC8717 and RFC9141.

--- middle


# Introduction

        NOTE: This document started with the raw text of RFC 2418, and
        subsequent drafts each incorporated the text of RFC 3934, RFC
        7475, RFC 7776, RFC 8717 (although the change to "Managing
        Director, Secretariat" does not seem right), and RFC 9141.
        A final update addressed all the errata. We have submitted this
        to the GENDISPATCH working group to determine the next steps.

The Internet, a loosely-organized international collaboration of
autonomous, interconnected networks, supports host-to-host
communication through voluntary adherence to open protocols and
procedures defined by Internet Standards.  There are also many
isolated interconnected networks, which are not connected to the
global Internet but use the Internet Standards. Internet Standards are
developed in the Internet Engineering Task Force (IETF).  This
document defines guidelines and procedures for IETF working groups.
The Internet Standards Process of the IETF is defined in {{bis2026}}. The
organizations involved in the IETF Standards Process are described in
{{!RFC9281}} as are the roles of specific individuals.

The IETF is a large, open community of network designers, operators,
vendors, users, and researchers concerned with the Internet and the
technology used on it. The primary activities of the IETF are
performed by committees known as working groups. There are currently
more than 100 working groups. (See the
[Datatracker web page](https://datatracker.ietf.org/wg/) for an
up-to-date list of IETF Working Groups.)
Working groups tend to have a narrow focus and a lifetime bounded by
the completion of a specific set of tasks, although there are
exceptions.

For management purposes, the IETF working groups are collected
together into areas, with each area having a separate focus.  For
example, the security area deals with the development of
security-related technology.  Each IETF area is managed by one or more
Area Directors (ADs).  There are currently seven areas in the IETF but the
number changes from time to time.
(See the [IETF web page](https://www.ietf.org/technologies/areas/)
for a list
of the current areas, the Area Directors for each area, and a list of
which working groups are assigned to each area.)

In many areas, the Area Directors have formed an advisory group or
directorate.  These comprise experienced members of the IETF and the
technical community represented by the area.  The specific name and the
details of the role for each group differ from area to area, but the
primary intent is that these groups assist the Area Director(s), e.g.,
with the review of specifications produced in the area.

The IETF area directors are selected by a nominating committee, which
also selects an overall chair for the IETF.  The nominations process
is described in {{?RFC8713}}.

The area directors sitting as a body, along with the IETF Chair,
comprise the Internet Engineering Steering Group (IESG). The IETF
Managing Director, IETF Secretariat, and the IAB Chair
are ex-officio members of the IESG.
There are also liaisons from IANA, the RFC Production Center,
the Secretariat, and another from the IAB.
The IESG approves IETF Standards and approves the
publication of other IETF documents.  (See {{bis2026}}.)

The IETF Secretariat provides staff and administrative support for
the operation of the IETF.

There is no formal membership in the IETF.  Participation is open to
all.  This participation may be by on-line contribution, attendance at
face-to-face sessions, or both.  Anyone from the Internet community
who has the time and interest is urged to participate in IETF meetings
and any of its on-line working group discussions. Participation is by
individual technical contributors, rather than by formal
representatives of organizations.

This document defines procedures and guidelines for the formation and
operation of working groups in the IETF. It defines the relations of
working groups to other bodies within the IETF. The duties of working
group Chairs and Area Directors with respect to the operation of the
working group are also defined.

## IETF approach to standardization

Familiarity with The Internet Standards Process {{bis2026}} is essential for a
complete understanding of the philosophy, procedures and guidelines
described in this document.

## Roles within a Working Group

The document, "Organizations Involved in the IETF Standards Process"
{{RFC9281}} describes the roles of a number of individuals within a working
group, including the working group chair and the document editor.
These descriptions are expanded later in this document.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Working group formation {#sec2}

IETF working groups (WGs) are the primary mechanism for development of
IETF specifications and guidelines, many of which are intended to be
standards or recommendations. A working group may be established at
the initiative of an Area Director or it may be initiated by an
individual or group of individuals. Anyone interested in creating an
IETF working group MUST obtain the advice and consent of the IETF Area
Director(s) in whose area the working group would fall and MUST
proceed through the formal steps detailed in this section.

Working groups are typically created to address a specific problem or
to produce one or more specific deliverables (a guideline, standards
specification, etc.).  Working groups are generally expected to be
short-lived in nature.  Upon completion of its goals and achievement
of its objectives, the working group is terminated. A working group
may also be terminated for other reasons (see {{sec4}}).
Alternatively, with the concurrence of the IESG, Area Director, the WG
Chair, and the WG participants, the objectives or assignment of the
working group may be extended by modifying the working group's charter
through a rechartering process (see {{sec5}}).

## Criteria for formation {#sec21}

When determining whether it is appropriate to create a working group,
the Area Director(s) and the IESG will consider several issues:

- Are the issues that the working group plans to address clear and
relevant to the Internet community?

- Are the goals specific and reasonably achievable, and achievable
within a reasonable time frame?

- What are the risks and urgency of the work, to determine the level
of effort required?

- Do the working group's activities overlap with those of another
working group?  If so, it may still be appropriate to create the
working group, but this question must be considered carefully by the
Area Directors as subdividing efforts often dilutes the available
technical expertise.

- Is there sufficient interest within the IETF in the working group's
topic with enough people willing to expend the effort to produce the
desired result (e.g., a protocol specification)?  Working groups
require considerable effort, including management of the working group
process, editing of working group documents, and contributing to the
document text.  IETF experience suggests that these roles typically
cannot all be handled by one person; a minimum of four or five active
participants in the management positions are typically required in
addition to a minimum of one or two dozen people that will attend the
working group meetings and contribute on the mailing list.  NOTE: The
interest must be broad enough that a working group would not be seen
as merely the activity of a single vendor.

- Is there enough expertise within the IETF in the working group's
topic, and are those people interested in contributing in the working
group?

- Does a base of interested consumers (end-users) appear to exist for
the planned work?  Consumer interest can be measured by participation
of end-users within the IETF process, as well as by less direct means.

- Does the IETF have a reasonable role to play in the determination of
the technology?  There are many Internet-related technologies that may
be interesting to IETF members but in some cases the IETF may not be
in a position to effect the course of the technology in the "real
world".  This can happen, for example, if the technology is being
developed by another standards body or an industry consortium.

- Are all known intellectual property rights relevant to the proposed
working group's efforts issues understood?

- Is the proposed work plan an open IETF effort or is it an attempt to
"bless" non-IETF technology where the effect of input from IETF
participants may be limited?

- Is there a good understanding of any existing work that is relevant
to the topics that the proposed working group is to pursue?  This
includes work within the IETF and elsewhere.

- Do the working group's goals overlap with known work in another
standards body, and if so is adequate liaison in place?

Considering the above criteria, the Area Director(s), using his or her
best judgement, will decide whether to pursue the formation of the
group through the chartering process.

## Charter {#sec22}

The formation of a working group requires a charter which is primarily
negotiated between a prospective working group Chair and the relevant
Area Director(s), although final approval is made by the IESG with
advice from the Internet Architecture Board (IAB).  A charter is a
contract between a working group and the IETF to perform a set of
tasks.  A charter:

1. Lists relevant administrative information for the working group;

2. Specifies the direction or objectives of the working group and
describes the approach that will be taken to achieve the goals; and

3. Enumerates a set of milestones together with time frames for their
completion.

When the prospective Chair(s), the Area Director and the IETF
Secretariat are satisfied with the charter form and content, it
becomes the basis for forming a working group. Note that an Area
Director MAY require holding an exploratory Birds of a Feather (BOF)
meeting, as described below, to gage the level of support for a
working group before submitting the charter to the IESG and IAB for
approval.

Charters may be renegotiated periodically to reflect the current
status, organization or goals of the working group (see {{sec5}}).
Hence, a charter is a contract between the IETF and the working group
which is committing to meet explicit milestones and delivering
specific "products".

Specifically, each charter consists of the following sections:

Working group name
: A working group name should be reasonably descriptive or identifiable.
Additionally, the group shall define an acronym (maximum 8 printable ASCII
characters) to reference the group in the IETF directories, mailing lists, and
general documents.

Chair(s)
: The working group may have one or more Chairs to perform the
administrative functions of the group. The email address(es) of the
Chair(s) shall be included.  Generally, a working group is limited to
two chairs.

Area and Area Director(s)
: The name of the IETF area with which the working group is affiliated and the
name and electronic mail address of the associated Area Director(s).

Responsible Area Director
: The Area Director who acts as the primary IESG contact for the working group.

Mailing list
: An IETF working group MUST have a general Internet mailing list.  Most
of the work of an IETF working group will be conducted on the mailing
list. The working group charter MUST include:

1. The address to which a participant sends a subscription request and the
procedures to follow when subscribing,

2. The address to which a participant sends submissions and special
procedures, if any, and

3. The location of the mailing list archive. A message archive MUST be
maintained in a public place which can be accessed via the
web.

Description of working group
: The focus and intent of the group shall be set forth briefly. By
reading this section alone, an individual should be able to decide
whether this group is relevant to their own work. The first paragraph
must give a brief summary of the problem area, basis, goal(s) and
approach(es) planned for the working group.  This paragraph can be
used as an overview of the working group's effort.

To facilitate evaluation of the intended work and to provide on-going
guidance to the working group, the charter must describe the problem
being solved and should discuss objectives and expected impact with
respect to:

- Architecture

- Operations

- Security

- Network management

- Scaling

- Transition (where applicable)

Goals and milestones
: The working group charter MUST establish a timetable for specific work
items.  While this may be renegotiated over time, the list of
milestones and dates facilitates the Area Director's tracking of
working group progress and status, and it is indispensable to
potential participants identifying the critical moments for input.
Milestones shall consist of deliverables that can be qualified as
showing specific achievement; e.g., "Internet-Draft finished" is fine,
but "discuss via email" is not. It is helpful to specify milestones
for every 3-6 months, so that progress can be gauged easily.  This
milestone list is expected to be updated periodically (see {{sec5}}).

An example of a WG charter is included as {{sample-charter}}.

## Charter review & approval

Proposed working groups often comprise technically competent
participants who are not familiar with the history of Internet
architecture or IETF processes.  This can, unfortunately, lead to good
working group consensus about a bad design.  To facilitate working
group efforts, an Area Director may assign a Consultant from among the
ranks of senior IETF participants.  (Consultants are described in
{{wg-consultant}}.)  At the discretion of the Area Director, approval of a new
WG may be withheld in the absence of sufficient consultant resources.

Once the Area Director (and the Area Directorate, as the Area Director
deems appropriate) has approved the working group charter, the charter
is submitted for review by the IAB and approval by the IESG.  After a
review period of at least a week the proposed charter is posted to the
IETF-announce mailing list as a public notice that the formation of
the working group is being considered.  At the same time the proposed
charter is also posted to the "new-work" mailing list.  This mailing
list has been created to let qualified representatives from other
standards organizations know about pending IETF working groups.  After
another review period lasting at least a week the IESG MAY approve the
charter as-is, it MAY request that changes be made in the charter, or
MAY decline to approve chartering of the working group

If the IESG approves the formation of the working group it remands the
approved charter to the IETF Secretariat who records and enters the
information into the IETF tracking database.  The working group is
announced to the IETF-announce a by the IETF Secretariat.

## Birds of a Feather (BOF)

Often it is not clear whether an issue merits the formation of a
working group.  To facilitate exploration of the issues the IETF
offers the possibility of a Birds of a Feather (BOF) session, as well
as the early formation of an email list for preliminary discussion. In
addition, a BOF may serve as a forum for a single presentation or
discussion, without any intent to form a working group.

A BOF is a session at an IETF meeting which permits "market research"
and technical "brainstorming".  Any individual may request permission
to hold a BOF on a subject. The request MUST be filed with a relevant
Area Director who must approve a BOF before it can be scheduled. The
person who requests the BOF may be asked to serve as Chair of the BOF.

The Chair of the BOF is also responsible for providing a report on the
outcome of the BOF.  If the Area Director approves, the BOF is then
scheduled by submitting a request to agenda@ietf.org with copies to
the Area Director(s). A BOF description and agenda are required
before a BOF can be scheduled.

Available time for BOFs is limited, and BOFs are held at the
discretion of the ADs for an area.  The AD(s) may require additional
assurances before authorizing a BOF.  For example,

- The Area Director MAY require the establishment of an open email
list prior to authorizing a BOF.  This permits initial exchanges and
sharing of framework, vocabulary and approaches, in order to make the
time spent in the BOF more productive.

- The Area Director MAY require that a BOF be held, prior to
establishing a working group (see {{sec22}}).

- The Area Director MAY require that there be a draft of the WG
charter prior to holding a BOF.

- The Area Director MAY require that a BOF not be held until an
Internet-Draft describing the proposed technology has been published
so it can be used as a basis for discussion in the BOF.

In general, a BOF on a particular topic is held only once (ONE slot at
one IETF Plenary meeting). Under unusual circumstances Area Directors
may, at their discretion, allow a BOF to meet for a second time. BOFs
are not permitted to meet three times.  Note that all other things
being equal, WGs will be given priority for meeting space over BOFs.
Also, occasionally BOFs may be held for other purposes than to discuss
formation of a working group.

Usually the outcome of a BOF will be one of the following:

- There was enough interest and focus in the subject to warrant the
formation of a WG;

- While there was a reasonable level of interest expressed in the BOF
some other criteria for working group formation was not met (see
{{sec21}}).

- The discussion came to a fruitful conclusion, with results to be
written down and published, however there is no need to establish a
WG; or

- There was not enough interest in the subject to warrant the
formation of a WG.

#  Working Group Operation

The IETF has basic requirements for open and fair participation and
for thorough consideration of technical alternatives.  Within those
constraints, working groups are autonomous and each determines most of
the details of its own operation with respect to session
participation, reaching closure, etc. The core rule for operation is
that acceptance or agreement is achieved via working group "rough
consensus".  WG participants should specifically note the requirements
for disclosure of conflicts of interest in {{RFC9281}}.

A number of procedural questions and issues will arise over time, and
it is the function of the Working Group Chair(s) to manage the group
process, keeping in mind that the overall purpose of the group is to
make progress towards reaching rough consensus in realizing the
working group's goals and objectives.

There are few hard and fast rules on organizing or conducting working
group activities, but a set of guidelines and practices has evolved
over time that have proven successful. These are listed here, with
actual choices typically determined by the working group participants
and the Chair(s).

## Session planning {#sess-planning}

For coordinated, structured WG interactions, the Chair(s) MUST publish
a draft agenda well in advance of the actual session. The agenda
should contain at least:

- The items for discussion;

- The estimated time necessary per item; and

- A clear indication of what documents the participants will need to
read before the session in order to be well prepared.

Publication of the working group agenda shall include sending a copy
of the agenda to the working group mailing list and to
agenda@ietf.org.

All working group actions shall be taken in a public forum, and wide
participation is encouraged. A working group will conduct much of its
business via electronic mail distribution lists but may meet
periodically to discuss and review task status and progress, to
resolve specific issues and to direct future activities.  IETF Plenary
meetings are the primary venue for these face-to-face working group
sessions, and it is common (though not required) that active "interim"
face-to-face meetings, telephone conferences, or video conferences may
also be held.  Interim meetings are subject to the same rules for
advance notification, reporting, open participation, and process,
which apply to other working group meetings.

All working group sessions (including those held outside of the IETF
meetings) shall be reported by making minutes available.  These
minutes should include the agenda for the session, an account of the
discussion including any decisions made, and a list of attendees. The
Working Group Chair is responsible for insuring that session minutes
are written and distributed, though the actual task may be performed
by someone designated by the Working Group Chair. The minutes shall be
submitted in printable ASCII text for publication in the IETF
Proceedings, and for posting in the IETF Directories and are to be
sent to: minutes@ietf.org

## Session venue

Each working group will determine the balance of email and
face-to-face sessions that is appropriate for achieving its
milestones. Electronic mail permits the widest participation;
face-to-face meetings often permit better focus and therefore can be
more efficient for reaching a consensus among a core of the working
group participants.  In determining the balance, the WG must ensure
that its process does not serve to exclude contribution by email-only
participants.  Decisions reached during a face-to-face meeting about
topics or issues which have not been discussed on the mailing list, or
are significantly different from previously arrived mailing list
consensus MUST be reviewed on the mailing list.

### IETF Meetings

If a WG needs a session at an IETF meeting, the Chair must apply for
time-slots as soon as the first announcement of that IETF meeting is
made by the IETF Secretariat to the WG-chairs list.  Session time is a
scarce resource at IETF meetings, so placing requests early will
facilitate schedule coordination for WGs requiring the same set of
experts.

The application for a WG session at an IETF meeting MUST be made to
the IETF Secretariat at the address agenda@ietf.org.  Some Area
Directors may want to coordinate WG sessions in their area and request
that time slots be coordinated through them.  If this is the case it
will be noted in the IETF meeting announcement. A WG scheduling
request MUST contain:

- The working group name and full title;

- The amount of time requested;

- The rough outline of the WG agenda that is expected to be covered;

- The estimated number of people that will attend the WG session;

- Related WGs that should not be scheduled for the same time slot(s); and

- Optionally a request can be added for the WG session to be
transmitted over the Internet in audio and video.

NOTE: While open discussion and contribution is essential to working
group success, the Chair is responsible for ensuring forward progress.
When acceptable to the WG, the Chair may call for restricted
participation (but not restricted attendance!) at IETF working group
sessions for the purpose of achieving progress. The Working Group
Chair then has the authority to refuse to grant the floor to any
individual who is unprepared or otherwise covering inappropriate
material, or who, in the opinion of the Chair is disrupting the WG
process.  The Chair should consult with the Area Director(s) if the
individual persists in disruptive behavior.

### On-line

It can be quite useful to conduct email exchanges in the same manner
as a face-to-face session, with published schedule and agenda, as
well as on-going summarization and consensus polling.

Many working group participants hold that mailing list discussion is
the best place to consider and resolve issues and make decisions. The
choice of operational style is made by the working group itself.  It
is important to note, however, that Internet email discussion is
possible for a much wider base of interested persons than is
attendance at IETF meetings, due to the time and expense required to
attend.

As in face-to-face sessions, occasionally one or more individuals may
engage in behavior on a mailing list that, in the opinion of the WG
chair, is disruptive to the WG process.  Unless the disruptive
behavior is severe enough that it must be stopped immediately, the
WG chair should attempt to discourage the disruptive behavior by
communicating directly with the offending individual.  If the
behavior persists, the WG chair should send at least one public
warning on the WG mailing list.  As a last resort and typically after
one or more explicit warnings and consultation with the responsible
Area Director, the WG chair may suspend the mailing list posting
privileges of the disruptive individual for a period of not more than
30 days.  Even while posting privileges are suspended, the individual
must not be prevented from receiving messages posted to the
list.  Like all other WG chair decisions, any suspension of posting
privileges is subject to appeal, as described in {{bis2026}}.

This mechanism is intended to permit a WG chair to suspend posting
privileges of a disruptive individual for a short period of
time.  This mechanism does not permit WG chairs to suspend an individual's
posting privileges for a period longer than 30 days regardless of the
type or severity of the disruptive incident.  However, further
disruptive behavior by the same individual will be considered
separately and may result in further warnings or suspensions.  Other
methods of mailing list control, including longer suspensions, must
be carried out in accordance with other IETF-approved procedures.  See
{{?RFC3683}} for one set of procedures already defined and
accepted by the community.

## Session management

Working groups make decisions through a "rough consensus" process.
IETF consensus does not require that all participants agree although
this is, of course, preferred.  In general, the dominant view of the
working group shall prevail.  (However, it must be noted that
"dominance" is not to be determined on the basis of volume or
persistence, but rather a more general sense of agreement.) Consensus
can be determined by a show of hands, humming, or any other means on
which the WG agrees (by rough consensus, of course).  Note that 51% of
the working group does not qualify as "rough consensus" and 99% is
better than rough.  It is up to the Chair to determine if rough
consensus has been reached.

It can be particularly challenging to gauge the level of consensus on
a mailing list.  There are two different cases where a working group
may be trying to understand the level of consensus via a mailing list
discussion. But in both cases the volume of messages on a topic is
not, by itself, a good indicator of consensus since one or two
individuals may be generating much of the traffic.

In the case where a consensus which has been reached during a
face-to-face meeting is being verified on a mailing list the people
who were in the meeting and expressed agreement must be taken into
account.  If there were 100 people in a meeting and only a few people
on the mailing list disagree with the consensus of the meeting then
the consensus should be seen as being verified.  Note that enough time
should be given to the verification process for the mailing list
readers to understand and consider any objections that may be raised
on the list.  The normal two week last-call period should be
sufficient for this.

The other case is where the discussion has been held entirely over the
mailing list.  The determination of the level of consensus may be
harder to do in this case since most people subscribed to mailing
lists do not actively participate in discussions on the list. It is
left to the discretion of the working group chair how to evaluate the
level of consensus.  The most common method used is for the working
group chair to state what he or she believes to be the consensus view
and. at the same time, requests comments from the list about the
stated conclusion.

The challenge to managing working group sessions is to balance the
need for open and fair consideration of the issues against the need to
make forward progress.  The working group, as a whole, has the final
responsibility for striking this balance.  The Chair has the
responsibility for overseeing the process but may delegate direct
process management to a formally-designated Facilitator.

It is occasionally appropriate to revisit a topic, to re-evaluate
alternatives or to improve the group's understanding of a relevant
decision.  However, unnecessary repeated discussions on issues can be
avoided if the Chair makes sure that the main arguments in the
discussion (and the outcome) are summarized and archived after a
discussion has come to conclusion. It is also good practice to note
important decisions/consensus reached by email in the minutes of the
next \'live' session, and to summarize briefly the decision-making
history in the final documents the WG produces.

To facilitate making forward progress, a Working Group Chair may wish
to decide to reject or defer the input from a member, based upon the
following criteria:

Old
: The input pertains to a topic that already has been resolved and is
redundant with information previously available;

Minor
: The input is new and pertains to a topic that has already been
resolved, but it is felt to be of minor import to the existing
decision;

Timing
: The input pertains to a topic that the working group has not yet
opened for discussion; or

Scope
: The input is outside of the scope of the working group charter.

## Contention and appeals {#appeals}

Disputes are possible at various stages during the IETF process. As
much as possible the process is designed so that compromises can be
made, and genuine consensus achieved; however, there are times when
even the most reasonable and knowledgeable people are unable to agree.
To achieve the goals of openness and fairness, such conflicts must be
resolved by a process of open review and discussion.

Formal procedures for requesting a review of WG, Chair, Area Director
or IESG actions and conducting appeals are documented in The Internet
Standards Process {{bis2026}}.

# Working Group Termination {#sec4}

Working groups are typically chartered to accomplish a specific task
or tasks.  After the tasks are complete, the group will be disbanded.
However, if a WG produces a Proposed or Draft Standard, the WG will
frequently become dormant rather than disband (i.e., the WG will no
longer conduct formal activities, but the mailing list will remain
available to review the work as it moves to Draft Standard and
Standard status.)

If, at some point, it becomes evident that a working group is unable
to complete the work outlined in the charter, or if the assumptions
which that work was based have been modified in discussion or by
experience, the Area Director, in consultation with the working group
can either:

1. Recharter to refocus its tasks,

2. Choose new Chair(s), or

3. Disband.

If the working group disagrees with the Area Director's choice, it may
appeal to the IESG (see {{appeals}}).

# Rechartering a Working Group {#sec5}

Updated milestones are renegotiated with the Area Director and the
IESG, as needed, and then are submitted to the IESG Secretariat:
iesg-secretary@ietf.org.

Rechartering (other than revising milestones) a working group follows
the same procedures that the initial chartering does (see {{sec2}}).
The revised charter must be submitted to the IESG and IAB for
approval.  As with the initial chartering, the IESG may approve new
charter as-is, it may request that changes be made in the new charter
(including having the Working Group continue to use the old charter),
or it may decline to approve the rechartered working group.  In the
latter case, the working group is disbanded.

# Staff Roles

Working groups require considerable care and feeding.  In addition to
general participation, successful working groups benefit from the
efforts of participants filling specific functional roles.  The Area
Director must agree to the specific people performing the WG Chair,
and Working Group Consultant roles, and they serve at the discretion
of the Area Director.

## WG Chair

The Working Group Chair is concerned with making forward progress
through a fair and open process, and has wide discretion in the
conduct of WG business.  The Chair must ensure that a number of tasks
are performed, either directly or by others assigned to the tasks.

The Chair has the responsibility and the authority to make decisions,
on behalf of the working group, regarding all matters of working group
process and staffing, in conformance with the rules of the IETF.  The
AD has the authority and the responsibility to assist in making those
decisions at the request of the Chair or when circumstances warrant
such an intervention.

The Chair's responsibility encompasses at least the following:

- Ensure WG process and content management

The Chair has ultimate responsibility for ensuring that a working
group achieves forward progress and meets its milestones.  The Chair
is also responsible to ensure that the working group operates in an
open and fair manner.  For some working groups, this can be
accomplished by having the Chair perform all management-related
activities.  In other working groups -- particularly those with large
or divisive participation -- it is helpful to allocate process and/or
secretarial functions to other participants.  Process management
pertains strictly to the style of working group interaction and not to
its content. It ensures fairness and detects redundancy.  The
secretarial function encompasses document editing.  It is quite common
for a working group to assign the task of specification Editor to one
or two participants.  Sometimes, they also are part of the design
team, described below.

- Moderate the WG email list

The Chair should attempt to ensure that the discussions on this list
are relevant and that they converge to consensus agreements. The Chair
should make sure that discussions on the list are summarized and that
the outcome is well documented (to avoid repetition).
They may need to consult with the Ombudsteam (see {{ombudsteam}}) if they
feel harassment is involved.
The Chair also
may choose to schedule organized on-line "sessions" with agenda and
deliverables.  These can be structured as true meetings, conducted
over the course of several days (to allow participation across the
Internet).

Organize, prepare and chair face-to-face and on-line formal sessions.

- Plan WG Sessions

The Chair must plan and announce all WG sessions well in advance (see
{{sess-planning}}).

- Communicate results of sessions

The Chair and/or Secretary must ensure that minutes of a session are
taken and that an attendance list is circulated (see {{sess-planning}}).

Immediately after a session, the WG Chair MUST provide the Area
Director with a very short report (approximately one paragraph, via
email) on the session.

- Distribute the workload

Of course, each WG will have participants who may not be able (or want)
to do any work at all. Most of the time the bulk of the work is done
by a few dedicated participants. It is the task of the Chair to
motivate enough experts to allow for a fair distribution of the
workload.

- Document development

Working groups produce documents and documents need authors. The Chair
must make sure that authors of WG documents incorporate changes as
agreed to by the WG (see {{doc-editor}}).

- Document publication

The Chair and/or Document Editor will work with the RFC Editor to
ensure document conformance with RFC publication requirements {{?RFC7322}} and
to coordinate any editorial changes suggested by the RFC Editor.  A
particular concern is that all participants are working from the same
version of a document at the same time.

- Document implementations

Under the procedures described in {{bis2026}}, the Chair is responsible for
documenting the specific implementations which qualify the
specification for Draft or Internet Standard status along with
documentation about testing of the interoperation of these
implementations.

## WG Secretary

Taking minutes and editing working group documents often is performed
by a specifically-designated participant or set of participants.  In
this role, the Secretary's job is to record WG decisions, rather than
to perform basic specification.

## Document Editor {#doc-editor}

Most IETF working groups focus their efforts on a document, or set of
documents, that capture the results of the group's work.  A working
group generally designates a person or persons to serve as the Editor
for a particular document.  The Document Editor is responsible for
ensuring that the contents of the document accurately reflect the
decisions that have been made by the working group.

As a general practice, the Working Group Chair and Document Editor
positions are filled by different individuals to help ensure that the
resulting documents accurately reflect the consensus of the working
group and that all processes are followed.

## WG Facilitator

When meetings tend to become distracted or divisive, it often is
helpful to assign the task of "process management" to one participant.
Their job is to oversee the nature, rather than the content, of
participant interactions.  That is, they attend to the style of the
discussion and to the schedule of the agenda, rather than making
direct technical contributions themselves.
They may need to consult with the Ombudsteam (see {{ombudsteam}})
if they feel harassment is involved.

## Design teams

It is often useful, and perhaps inevitable, for a sub-group of a
working group to develop a proposal to solve a particular problem.
Such a sub-group is called a design team.  In order for a design team
to remain small and agile, it is acceptable to have closed membership
and private meetings.  Design teams may range from an informal chat
between people in a hallway to a formal set of expert volunteers that
the WG chair or AD appoints to attack a controversial problem.  The
output of a design team is always subject to approval, rejection or
modification by the WG as a whole.

## Working Group Consultant {#wg-consultant}

At the discretion of the Area Director, a Consultant may be assigned
to a working group.  Consultants have specific technical background
appropriate to the WG and experience in Internet architecture and IETF
process.

## Area Director

Area Directors are responsible for ensuring that working groups in
their area produce coherent, coordinated, architecturally consistent
and timely output as a contribution to the overall results of the
IETF.

## Ombudsteam {#ombudsteam}

As noted in {{!RFC7776}}:

> IETF Participants must not engage in harassment while at IETF
> meetings, virtual meetings, or social events or while participating
> in mailing lists.  This document lays out procedures for managing and
> enforcing this policy.

The Ombudsteam is a resource for the entire IETF intended to address
issues of harassment, and all WG participants should feel free to
engage with the team if they feel there is an issue.

#  Working Group Documents

## Session documents

All relevant documents to be discussed at a session should be
published and available as Internet-Drafts at least two weeks before a
session starts.  Any document which does not meet this publication
deadline can only be discussed in a working group session with the
specific approval of the working group chair(s).  Since it is
important that working group members have adequate time to review all
documents, granting such an exception should only be done under
unusual conditions.  The final session agenda should be posted to the
working group mailing list at least two weeks before the session and
sent at that time to agenda@ietf.org for publication on the IETF web
site.

## Internet-Drafts (I-D)

The Internet-Drafts directory is provided to working groups as a
resource for posting and disseminating in-process copies of working
group documents. This repository is replicated at various locations
around the Internet. It is encouraged that draft documents be posted
as soon as they become reasonably stable.

It is stressed here that Internet-Drafts are working documents and
have no official standards status whatsoever. They may, eventually,
turn into a standards-track document or they may sink from sight.
Internet-Drafts are submitted to: internet-drafts@ietf.org

The format of an Internet-Draft is mostly the same as for an RFC
{{?RFC7322, Section 4}}; details can also be found at
<https://authors.ietf.org>. In addition, an I-D must contain:

- The I-D filename; and

- The expiration date for the I-D.

- Standard boilerplate which can be found in Section 6 of the
[Trust Legal Provisions](https://trustee.ietf.org/documentation/trust-legal-provisions)

The tooling available to authors automates most the above.

## Request For Comments (RFC) {#rfc-doc}

The work of an IETF working group often results in publication of one
or more documents, as part of the Request For Comments (RFCs) {{bis2026}}
series. This series is the archival publication record for the
Internet community. A document can be written by an individual in a
working group, by a group as a whole with a designated Editor, or by
others not involved with the IETF.

NOTE: The RFC series is a publication mechanism only and publication
does not determine the IETF status of a document.  Status is
determined through separate, explicit status labels assigned by the
IESG on behalf of the IETF.  In other words, the reader is reminded
that all Internet Standards are published as RFCs, but NOT all RFCs
specify standards {{?RFC1796}}.

## Working Group Last-Call

When a WG decides that a document is ready for publication it may be
submitted to the IESG for consideration. In most cases the
determination that a WG feels that a document is ready for publication
is done by the WG Chair issuing a working group Last-Call.  The
decision to issue a working group Last-Call is at the discretion of
the WG Chair working with the Area Director.  A working group
Last-Call serves the same purpose within a working group that an IESG
Last-Call does in the broader IETF community (see {{bis2026}}).

## Submission of documents

Once that a WG has determined at least rough consensus exists within
the WG for the advancement of a document the following must be done:

- The version of the relevant document exactly as agreed to by the WG
MUST be in the Internet-Drafts directory.

- The relevant document MUST be formatted according to {{rfc-doc}}.

- The WG Chair MUST send email to the relevant Area Director.  A copy
of the request MUST be also sent to the IESG Secretariat.  The mail
MUST contain the reference to the document's ID filename, and the
action requested.  The copy of the message to the IESG Secretariat is
to ensure that the request gets recorded by the Secretariat so that
they can monitor the progress of the document through the process.

Unless returned by the IESG to the WG for further development,
progressing of the document is then the responsibility of the IESG.
After IESG approval, responsibility for final disposition is the joint
responsibility of the RFC Editor, the WG Chair and the Document
Editor.

# Review of documents

The IESG reviews all documents submitted for publication as RFCs.
Usually minimal IESG review is necessary in the case of a submission
from a WG intended as an Informational or Experimental RFC. More
extensive review is undertaken in the case of standards-track
documents.

Prior to the IESG beginning their deliberations on standards-track
documents, IETF Secretariat will issue a "Last-Call" to the IETF
mailing list (see {{bis2026}}). This Last Call will announce the intention of
the IESG to consider the document, and it will solicit final comments
from the IETF within a period of two weeks.  It is important to note
that a Last-Call is intended as a brief, final check with the Internet
community, to make sure that no important concerns have been missed or
misunderstood. The Last-Call should not serve as a more general,
in-depth review.

The IESG review takes into account responses to the Last-Call and will
lead to one of these possible conclusions:

1. The document is accepted as is for the status requested.
This fact will be announced by the IETF Secretariat to the IETF
mailing list and to the RFC Editor.

2. The document is accepted as-is but not for the status requested.
This fact will be announced by the IETF Secretariat to the IETF
mailing list and to the RFC Editor (see {{bis2026}} for more details).

3. Changes regarding content are suggested to the author(s)/WG.
Suggestions from the IESG must be clear and direct, so as to
facilitate working group and author correction of the specification.
If the author(s)/WG can explain to the satisfaction of the IESG why
the changes are not necessary, the document will be accepted for
publication as under point 1, above.  If the changes are made the
revised document may be resubmitted for IESG review.

4. Changes are suggested by the IESG and a change in status is recommended.
The process described above for 3 and 2 are followed in that order.

5. The document is rejected.
Any document rejection will be accompanied by specific and thorough
arguments from the IESG. Although the IETF and working group process
is structured such that this alternative is not likely to arise for
documents coming from a working group, the IESG has the right and
responsibility to reject documents that the IESG feels are fatally
flawed in some way.

If any individual or group of individuals feels that the review
treatment has been unfair, there is the opportunity to make a
procedural complaint. The mechanism for this type of complaints is
described in {{bis2026}}.

# Security Considerations

Documents describing IETF processes, such as this one, do not have an
impact on the security of the network infrastructure or of Internet
applications.

It should be noted that all IETF working groups are required to
examine and understand the security implications of any technology
they develop.  This analysis must be included in any resulting RFCs in
a Security Considerations section.  Note that merely noting a
significant security hole is no longer sufficient.  IETF developed
technologies should not add insecurity to the environment in which
they are run.

# IANA Considerations

This document has no IANA actions.

# Change Log

- Draft 0: Translated the nroff source of RFC 2418 into markdown. Changed
the intellectual proper notices the current ones.

- Draft 1: Incorporated RFC 3934. Fixed a few minor typo's and cut/paste
errors. Fixed updates/obsoletes headers and comments.

- Draft 2: Incorporate RFC 7475.
Fix internal references.

- Draft 3: Incorporate RFC 8717.

- Draft 4: Incoroporate RFC 9141.

- Draft 5: Incorporate RFC 7776.
Text reviewed by Adrian Farrel, one of the RFC authors,
since it is not really directly including text from the RFC.

- Draft 6: Addressed the editorial issues found by the following
errata: 6787.
Errata 3752. 6130, 7408 were previously fixed.

--- back

# Appendix:  Sample Working Group Charter {#sample-charter}
{:numbered="false"}

~~~
Working Group Name:
    IP Telephony (iptel)

IETF Area:
    Transport Area

Chair(s):
    Jonathan Rosenberg <jdrosen@bell-labs.com>

Transport Area Director(s):
    Scott Bradner <sob@harvard.edu>
    Allyn Romanow <allyn@mci.net>

Responsible Area Director:
    Allyn Romanow <allyn@mci.net>

Mailing Lists:
    General Discussion:iptel@lists.research.bell-labs.com
    To Subscribe: iptel-request@lists.research.bell-labs.com
    Archive: http://www.bell-labs.com/mailing-lists/siptel

Description of Working Group:

Before Internet telephony can become a widely deployed service, a
number of protocols must be deployed. These include signaling and
capabilities exchange, but also include a number of "peripheral"
protocols for providing related services.

The primary purpose of this working group is to develop two such
supportive protocols and a framework document. They are:

1. Call Processing Syntax. When a call is setup between two endpoints,
the signaling will generally pass through several servers (such as an
H.323 gatekeeper) which are responsible for forwarding, redirecting,
or proxying the signaling messages. For example, a user may make a
call to j.doe@bigcompany.com. The signaling message to initiate the
call will arrive at some server at bigcompany. This server can inform
the caller that the callee is busy, forward the call initiation
request to another server closer to the user, or drop the call
completely (among other possibilities). It is very desirable to allow
the callee to provide input to this process, guiding the server in its
decision on how to act. This can enable a wide variety of advanced
personal mobility and call agent services.

Such preferences can be expressed in a call processing syntax, which
can be authored by the user (or generated automatically by some tool),
and then uploaded to the server. The group will develop this syntax,
and specify means of securely transporting and extending it. The
result will be a single standards track RFC.

2. In addition, the group will write a service model document, which
describes the services that are enabled by the call processing syntax,
and discusses how the syntax can be used. This document will result in
a single RFC.

3. Gateway Attribute Distribution Protocol. When making a call between
an IP host and a PSTN user, a telephony gateway must be used. The
selection of such gateways can be based on many criteria, including
client expressed preferences, service provider preferences, and
availability of gateways, in addition to destination telephone number.
Since gateways outside of the hosts' administrative domain might be
used, a protocol is required to allow gateways in remote domains to
distribute their attributes (such as PSTN connectivity, supported
codecs, etc.) to entities in other domains which must make a selection
of a gateway. The protocol must allow for scalable, bandwidth
efficient, and very secure transmission of these attributes. The group
will investigate and design a protocol for this purpose, generate an
Internet Draft, and advance it to RFC as appropriate.

Goals and Milestones:

May 98    Issue first Internet-Draft on service framework
Jul 98    Submit framework ID to IESG for publication as an RFC.
Aug 98    Issue first Internet-Draft on Call Processing Syntax
Oct 98    Submit Call processing syntax to IESG for consideration
      as a Proposed Standard.
Dec 98    Achieve consensus on basics of gateway attribute
      distribution protocol
Jan 99    Submit Gateway Attribute Distribution protocol to IESG
      for consideration as a RFC (info, exp, stds track TB
~~~

# Acknowledgments
{:numbered="false"}

We gratefully acknowledge those who have contributed to the development of
IETF RFC's and the processes that create both the content and documents.  In
particular, we thank the authors of all the documents that updated
{{?RFC2418}}.

We also thank Sandy Ginoza of the Secretariat for sending all the
sources of {{?RFC2418}} and the subsequent documents,
and John Klensin for his support and cooperation during the process
of creating this document.
