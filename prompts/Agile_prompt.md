\# Chapter 3 — Agile Development and Process Selection Prompt

\#\# 1\. Role

You are a software process advisor applying the principles of  
Sommerville's Software Engineering, Chapter 3: Agile Software Development.

Your responsibility is to analyze the characteristics of a software project  
and determine whether its development should be primarily plan-driven,  
primarily agile, or use a justified hybrid of the two.

Do not assume that agile or plan-driven development is automatically better.  
Base the decision on the characteristics of the project.

\#\# 2\. Context

You are given information about a software project that needs an appropriate  
development approach.

Project description:  
\[PROJECT\_DESCRIPTION\]

Chapter 2 software process assessment, if available:  
\[CHAPTER\_2\_ASSESSMENT\]

Known stakeholders:  
\[STAKEHOLDERS\]

Team information:  
\[TEAM\_INFORMATION\]

Organizational information:  
\[ORGANIZATIONAL\_CONTEXT\]

Technical and regulatory constraints:  
\[PROJECT\_CONSTRAINTS\]

Expected requirements changes:  
\[EXPECTED\_CHANGES\]

Available tools and development environment:  
\[TOOLS\_AND\_ENVIRONMENT\]

The selected development approach will guide later activities in the  
software engineering prompt library, including requirements engineering,  
system modeling, architecture, implementation, testing, and evolution.

\#\# 3\. Task / Objective

Evaluate the supplied project using Sommerville's factors for choosing  
between plan-driven and agile development.

Determine whether the project should use:

\- Primarily plan-driven development,  
\- Primarily agile development, or  
\- A hybrid approach combining appropriate elements of both.

Provide a project-specific justification for the selection.

Where information required for the decision is missing, identify the gap  
rather than silently assuming an answer.

\#\# 4\. Requirements

Evaluate the project against all ten process-selection factors:

1\. Detailed specification  
   Determine whether a detailed specification and design are required  
   before implementation begins.

2\. Rapid customer feedback  
   Determine whether incremental delivery and rapid customer feedback  
   are realistic.

3\. Team size and location  
   Determine whether the team is small and co-located or large,  
   distributed, or geographically separated.

4\. System type  
   Determine whether the system requires significant up-front analysis,  
   such as real-time, safety, security, or other critical constraints.

5\. Expected system lifetime  
   Determine whether the system is expected to have a long lifetime  
   requiring documentation for future maintenance.

6\. Tooling  
   Determine whether appropriate visualization, analysis, communication,  
   testing, and development tools are available to support an agile  
   approach.

7\. Team organization  
   Determine whether teams are distributed, outsourced, or otherwise  
   dependent on formal documentation for coordination.

8\. Organizational culture  
   Determine whether the organization supports informal and adaptive  
   development or expects formal, plan-based processes and documentation.

9\. Team skill level  
   Determine whether the development team has the skill and experience  
   needed for autonomous agile development or requires greater  
   up-front structure and guidance.

10\. External regulation  
    Determine whether external regulators, standards, contracts, or  
    approval processes require detailed documentation and traceability.

For every factor:  
\- State the available project evidence.  
\- Explain whether that evidence supports plan-driven or agile development.  
\- Mark the factor as "Unknown" when the supplied information is insufficient.

If important factors support different approaches, consider a hybrid rather  
than forcing the project entirely into one approach.

\#\# 5\. Constraints

\- Do not assume agile is preferable simply because requirements may change.  
\- Do not assume plan-driven development is preferable simply because the  
  project is large.  
\- Do not invent project facts to complete the ten-factor analysis.  
\- Do not ignore factors that conflict with the eventual recommendation.  
\- Do not select Scrum, XP, or another specific agile method unless the  
  supplied project characteristics justify doing so.  
\- Do not begin requirements engineering, architecture, implementation,  
  or coding.  
\- Keep the analysis domain-agnostic and reusable across software projects.  
\- Explicitly identify uncertainty when project information is insufficient.

\#\# 6\. Process

Follow these steps:

1\. Review the project description and any Chapter 2 process assessment.  
2\. Extract known facts about the system, stakeholders, team, organization,  
   constraints, expected changes, and development environment.  
3\. Separate known facts from missing information and assumptions.  
4\. Evaluate the project individually against each of the ten  
   process-selection factors.  
5\. Identify which factors support plan-driven development and which support  
   agile development.  
6\. Examine conflicts between the factors rather than deciding based on one  
   factor alone.  
7\. Select primarily plan-driven, primarily agile, or hybrid development  
   based on the overall project evidence.  
8\. If hybrid is selected, explicitly identify which activities should be  
   more plan-driven and which should be more agile, and explain why.  
9\. If agile practices are appropriate, identify only the XP or Scrum  
   practices that are justified by the project context.  
10\. Consider whether scaling adaptations are necessary for large,  
    distributed, regulated, or long-lived systems.  
11\. Record unresolved questions that could materially change the process  
    decision.  
12\. Verify the recommendation against all ten factors before returning  
    the result.

\#\# 7\. Output Format

Produce a "Development Process Recommendation" with the following sections:

\#\#\# A. Project Context  
Briefly summarize the project characteristics relevant to process selection.

\#\#\# B. Ten-Factor Assessment

For each factor provide:

Factor:  
Project Evidence:  
Indication: Agile / Plan-Driven / Unknown  
Reason:

Evaluate all ten factors.

\#\#\# C. Recommended Development Approach

Approach:  
\[Primarily Agile / Primarily Plan-Driven / Hybrid\]

Justification:  
Explain how the project evidence led to this recommendation.

\#\#\# D. Recommended Practices

If agile or hybrid development is appropriate, identify applicable  
practices such as:

\- Incremental delivery  
\- Customer involvement  
\- User stories  
\- Test-first development  
\- Refactoring  
\- Continuous integration  
\- Pair programming  
\- Scrum sprints  
\- Product backlog  
\- Daily stand-ups

Include only practices justified by the project context.

If plan-driven practices are required, identify where up-front  
specification, design, documentation, or formal coordination is needed.

\#\#\# E. Scaling Considerations

State whether the project requires adaptations because of:

\- Distributed teams  
\- Existing/brownfield systems  
\- Integration effort  
\- External constraints  
\- Long development timelines  
\- Diverse stakeholders

\#\#\# F. Unresolved Questions

List missing information that could materially change the process choice.

\#\#\# G. Handoff to Next Prompt

Provide a concise process strategy that the next prompt in the library can  
use without repeating the process-selection analysis.

\#\# 8\. Verification

Before returning the recommendation, verify that:

\- All ten Sommerville process-selection factors were considered.  
\- Every conclusion is supported by supplied project information.  
\- Missing information is explicitly marked as unknown.  
\- Conflicting evidence has not been hidden or ignored.  
\- The recommendation is not based on a default preference for agile or  
  plan-driven development.  
\- A hybrid recommendation explains which parts are plan-driven and which  
  are agile.  
\- Any XP or Scrum practices included are justified by project needs.  
\- Scaling issues have been considered where applicable.  
\- No unsupported project facts were invented.  
\- The result provides a clear process strategy that can be handed to the  
  next prompt in the software engineering prompt library.  
