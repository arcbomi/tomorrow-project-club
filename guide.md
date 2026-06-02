# Open Source Community Battle Club Guide

This is the main handbook for the club.

The club builds useful open source projects in short 4-week seasons. Two teams compete, but the goal is bigger than winning. Members learn teamwork, leadership, communication, project management, and how to ship real public software.

If you want the detail for a specific part, use the linked docs:

- [Seed Project Playbook](seed-project/README.md)
- [Beginner Pipeline](beginner-pipeline/README.md)
- [Maintainers](maintainers/README.md)
- [Infra Rules](infra/README.md)
- [Official Projects Archive](club-official-projects/README.md)

## 1. What This Club Is

- The club is for building real public projects that help school or community life.
- Anyone can join, and anyone can leave at any time.
- Members work in two teams.
- Teams choose a project, build it in one month, and show it in a final public showcase.
- The competition should feel exciting, but it must stay kind, fair, and beginner-friendly.

## 2. Quick Glossary

| Term | Simple meaning |
|---|---|
| Season | One 4-week club project round |
| Cycle | The same 4-week round; use it as another word for season |
| Roadmap | The plan for what the team will build and when |
| Architecture | The way the project is put together |
| Blocker | Something that stops work from moving forward |
| Deliverable | Something the team must finish and show |
| MVP | The smallest version of the project that still works |
| Maintainer | A person who looks after part of the project |
| Issue | A task or problem written in the repository |
| Pull request | A proposed change to the code or docs |
| Release | A named version of the project that people can use |

## 3. How One Month Works

| Week | Main focus | Main output |
|---|---|---|
| Week 1 | Team formation and planning | Teams, roles, repository, roadmap, starter tasks |
| Week 2 | Core development | Working MVP, basic UI, first demo, blocker list |
| Week 3 | Expansion and stabilization | Better features, cleaner UI, fixes, docs draft |
| Week 4 | Final battle and showcase | Code freeze, final demo, voting, judging, archive |

## 4. Team Roles

Each person picks one main role and may pick one support role if the team is small.

| Role | What this person does | Good first task |
|---|---|---|
| Main Leader | Runs the team, keeps the schedule, removes blockers, and keeps the team focused | Open the meeting agenda and assign the first tasks |
| Secondary Leader | Acts as backup leader, records decisions, and steps in when the main leader is absent | Write the first meeting notes |
| Project Manager | Turns the idea into tasks, tracks the roadmap, and keeps the backlog organized | Create the issue board and labels |
| Frontend Developer | Builds the user interface and client-side behavior | Create the app shell or first screen |
| Backend Developer | Builds APIs, data, auth, and server logic | Stub the first endpoint or data model |
| UI/UX Designer | Makes wireframes, layouts, and usability improvements | Draw the first user flow |
| DevOps Engineer | Sets up repo structure, CI, deployment, and release checks | Add the basic repository setup and workflow file |
| QA Tester | Finds bugs, writes test cases, and checks the demo before release | Create a smoke test checklist |
| Documentation Writer | Writes README files, setup steps, and release notes | Draft the project intro and setup section |
| Community Manager / Presenter | Explains the project to others, prepares slides, and helps with voting | Write a 60-second project pitch |
| Maintainer / Release Manager | Reviews changes, tags releases, and keeps the handoff clean | Make the release checklist |

## 5. Week 1 to Week 4

### Week 1

Goal:

- Form the teams
- Choose roles
- Pick the project
- Create the repository
- Build the first roadmap

What leaders do:

- Introduce themselves
- Explain their style
- Keep the meeting moving
- Help the team choose a useful project

What members do:

- Vote for the team leaders anonymously
- Choose a role title
- Help pick the project idea
- Add starter tasks to the board

What beginners do:

- Join onboarding
- Learn the repository
- Pick a small first task
- Ask for help early

Deliverables:

- Team list
- Role list
- Repository
- Roadmap
- Task board

### Week 2

Goal:

- Build the MVP
- Show something working
- Find blockers early

What leaders do:

- Keep scope small
- Remove blockers
- Make sure every person has work

What members do:

- Start implementation
- Merge the first useful changes
- Demo progress in the weekly check-in

What beginners do:

- Work on a starter issue
- Pair with a mentor
- Learn issue and pull request flow

Deliverables:

- Working prototype
- Basic UI
- First internal demo
- Blocker list

### Week 3

Goal:

- Improve the project
- Fix problems
- Prepare the presentation

What leaders do:

- Decide what gets polished
- Check whether the team is on schedule
- Make sure docs are being written

What members do:

- Add features carefully
- Fix bugs
- Improve the user experience
- Test the project more seriously

What beginners do:

- Help with UI fixes
- Improve docs
- Run tests
- Translate or polish text where needed

Deliverables:

- Stable demo
- Better UI
- Documentation draft
- Release candidate plan

### Week 4

Goal:

- Freeze the project
- Rehearse the demo
- Present in public
- Record the winner and the official archive

What leaders do:

- Stop risky feature changes
- Make sure the final story is clear
- Prepare the team for questions

What members do:

- Finish the final demo
- Check the release
- Practice the presentation
- Prepare evidence of contribution

What beginners do:

- Help with slides, notes, screenshots, or demo support
- Double-check docs and bug fixes
- Join the final presentation if possible

Deliverables:

- Code freeze
- Final demo
- Vote results
- Scorecard
- Archive handoff

## 6. Meeting Format

Use the same 10-minute meeting structure every week so everyone knows what is coming.

| Minute | What to say | What to do |
|---|---|---|
| 0-1 | Today we need clear owners, blockers, and next steps. | Start the timer and state the meeting goal |
| 1-3 | What changed since last week? | Each team gives a short progress update |
| 3-5 | What is blocked right now? | List blockers and ask for help |
| 5-7 | What decisions do we need today? | Approve scope changes, role swaps, or priorities |
| 7-9 | What will be done by next meeting? | Assign exact tasks and owners |
| 9-10 | Repeat the commitments. | Confirm the action items and close |

Simple host script:

- Today our goal is ...
- Since last time, we finished ...
- Our biggest blocker is ...
- By next meeting, we will deliver ...

## 7. Beginner Pipeline

The club should never leave beginners without a first task.

### Stage 1: Orientation

- Meet the team
- Learn the project idea
- Learn GitHub basics
- Learn where issues and pull requests live
- Learn the club safety rules

### Stage 2: Starter Task

- Pick a small, safe task right away
- Good starter tasks are docs, QA, UI polish, translations, or a tiny fix
- The task should be small enough to finish in one session

### Stage 3: Paired Pull Request

- Open the first pull request with help from a mentor or maintainer
- Review the comments together
- Learn how to update the work without fear

### Stage 4: Independent Task

- After one merged pull request, try a slightly larger task
- The beginner should still get help, but less direct hand-holding

### Stage 5: Contributor Growth

- After two successful pull requests and one demo contribution, the member can take on a larger role
- The goal is confidence, not speed

Rules for beginners:

- Never wait around for "real work"
- Keep a starter-issue queue ready
- Explain the project in plain language
- Praise progress, not just final results

## 8. Tech Rules and License

- Implementation code must use Go, JavaScript, or TypeScript.
- Markdown, JSON, YAML, HTML, and CSS are allowed as support files.
- Public repositories are required.
- Do not put student names, photos, emails, or sensitive school data in public repos.
- MIT is the default license for club-authored projects.
- Third-party code, fonts, icons, and assets must be license-safe and documented.

## 9. Maintainer System

Maintainers are stewards, not bosses.

| Maintainer type | Main job |
|---|---|
| Club Maintainer | Keeps the shared rules, templates, and license policy in order |
| Project Maintainer | Owns one project repo, reviews PRs, and approves merges |
| Area Maintainer | Watches one area such as frontend, backend, docs, QA, or release work |

Guardrails:

- No self-merges
- At least one reviewer for every pull request
- Weekly health checks for maintainer activity
- If a maintainer misses two weekly check-ins, the role should be paused and replaced
- If someone leaves the club, they should hand off open work before stepping away

## 10. Final Showcase and Voting

The final week should feel fair and simple.

Showcase rules:

- Freeze code and slides before the event
- Give both teams the same room, screen, time, and rules
- Use a live demo, not only screenshots
- Keep the presentation easy for non-technical people to follow

10-minute showcase flow:

| Minute | What to say or do |
|---|---|
| 0-1 | Say the project name, the problem, and who it helps |
| 1-3 | Start the live demo |
| 3-5 | Explain the core idea and why it matters |
| 5-7 | Show the stack, repo, license, and open source proof |
| 7-9 | Explain each member's contribution and what they learned |
| 9-10 | Q&A |

Voting and judging:

- Judges score the teams using a rubric
- Audience voting is allowed, but it only decides People's Choice
- The main winner should come from judge scores, not popularity
- Tie-breakers should use usefulness first, then open source quality, then technical execution, then a judge-chair decision

Archive rules:

- Record the winning project in the official archive
- Include the summary, team members, repo link, release link, demo link, screenshots, scorecard, primary maintainer, backup maintainer, and maintainer handoff notes

## 11. FAQ and Safety Rules

- Can someone join late? Yes. Give them onboarding and a starter task.
- Can someone leave? Yes. Ask them to hand off unfinished work first.
- Can roles change? Yes, but only during the weekly review, not in a way that breaks the team.
- Can the club use private school data? No.
- Can the club be toxic or exclusive? No. Beginners must be welcomed.
- What if a team is stuck? Break the work into smaller issues and ask a maintainer for help.
