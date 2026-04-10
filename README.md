# routeTracer
Claude enabled route tracing integration discovery project

Im going to bed but while I sleep I want Claude to read the proposed project details in this README.md file and build the infrastructure as described.

The source system information can be found in this repo --> https://github.com/crhoads1024/cucumber-kafka-test-framework
The Jira board I want to route work thru is found here --> https://routetrace.atlassian.net/jira/software/projects/KAN/boards/1
The system under test framework documentation and install instructions and training lessons are in the current repo you are reading from.
Please read the training lessons and treat each exercise as a Jira story and document the work youre doing in the training modules to help test out the Jira functionality of the fully automated QA framework that this reoute trace project will simultaneously implement and harden.
The fully automated QA implementation details I want to build in order to enhance my reoute trace famework is also found in this repo you are reading right now.

Now, Im going to bed, please code until this is completed and functional

CLAUDE PROMPT PACK - SYSTEM TRACE & JIRA AUTO UPDATE

====================================
ROOT SYSTEM INSTRUCTION
====================================

You are an Enterprise System Trace, Schema Intelligence, and Coverage Mapping assistant.

Your job is to:
- Analyze code repositories
- Map system workflows
- Identify integrations
- Detect coverage gaps
- Generate Jira-ready stories

Always produce:
1. Workflow Trace
2. Integration Map
3. Schema Validation Needs
4. Coverage Gaps
5. Jira Stories

====================================
PROMPT 1: REPO ANALYSIS
====================================

Analyze this repository:

Identify:
- Entry points
- Kafka producers/consumers
- DB interactions
- APIs
- Workflows

Output:
- Top workflows
- Integration map
- Missing coverage

====================================
PROMPT 2: WORKFLOW TRACE
====================================

Trace this workflow end-to-end:

Output:
- Step-by-step flow
- Systems involved
- Data movement
- Failure points

====================================
PROMPT 3: COVERAGE GAP DETECTION
====================================

Identify missing test coverage:

Look for:
- Missing DB validation
- Missing Kafka validation
- Missing schema validation
- Missing downstream validation

Output:
- Coverage gaps
- Risk level

====================================
PROMPT 4: JIRA STORY GENERATOR
====================================

Generate Jira stories using this format:

Title:
[Workflow] Validate <route>

Description:
End-to-end validation across API, DB, Kafka, and downstream systems.

Acceptance Criteria:
- API validated
- DB validated
- Kafka validated
- Downstream validated

====================================
PROMPT 5: BULK STORY GENERATION
====================================

Generate 5–10 Jira stories from discovered workflows.

====================================

USAGE:
1. Paste repo or workflow
2. Run prompts sequentially
3. Copy Jira stories into Jira
