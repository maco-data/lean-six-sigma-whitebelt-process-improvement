# Lean Six Sigma White Belt Process Improvement Project

I created this repository to document my Lean Six Sigma White Belt process improvement project. I am using this project to practice structured problem solving, reduce waste, and build a clear record of my work from problem discovery through results.

## Project Focus

I will improve the request and approval phase of the fund replenishment process for the company's certified mail service provider.

The certified mail service provider remotely prints company letters and sends them through certified mail. I do not plan to name the provider in this project documentation.

Currently, three authorized agents usually notice that funds are depleted only when we try to submit a prepared letter and an insufficient funds banner appears. This issue usually happens bi-weekly. When funds are not available, certified letters cannot be sent, legal notices are delayed, customers are affected, and operations are delayed.

The full replenishment process can be delayed by a minimum of three hours. If the issue happens mid-shift, the delay can extend until the next business day because of the time difference with the provider and their operating hours.

My focus is to improve how letter volume and fund usage are tracked so the team can identify the need for replenishment earlier. I also want to improve how the IT Manager and Director of Operations are notified so approval can happen faster and the IT Manager can contact the provider in time.

To support this improvement, I plan to use a letter tally or log, a low-balance reminder, and a prepaid threshold so the team can request replenishment before the service reaches insufficient funds.

## Problem Statement

The certified mail fund replenishment process creates delays because the team does not have early visibility into the available fund balance. Although we know the cost of each type of letter, we do not always know how much funding has been added or how close the balance is to being depleted.

When funds run out, the issue is usually discovered only after an authorized agent attempts to submit a prepared letter and receives an insufficient funds banner. At that point, the client file is paused while the team moves on to other tasks and waits for the fund replenishment process to be completed.

Based on the last three months of mail activity, the team sends an average of 45 letters per week. Approximately 87.50% are validation letters, including legal notices, sent as Certified Mail with Electronic Return Receipt. The remaining 12.50% are cancellation letters, also known as revoke representation letters, sent as First Class Mail.

There is no single fixed deadline for every letter, but delays can affect the validation process and create uneasiness for customers who may feel that no action is being taken on their accounts. Timely mailing is especially important for legal notices, particularly when a customer may be involved in a lawsuit.

The main problem I am focusing on is the lack of early visibility into fund usage, which can delay certified mail processing and pause affected client files until funds become available again.

## Goal

I want to reduce certified mail interruptions caused by insufficient funds by improving how the team identifies low balance, notifies the IT Manager, and requests replenishment before funds are depleted.

My goal is to help the team submit replenishment requests at least one business day before funds run out within 30 days of implementing the improvement.

I want the improvement to focus on prevention by avoiding insufficient funds instead of only reacting after the balance has already been depleted. The process should also support faster approval so the IT Manager can request authorization and replenish the service in time.

The target is to maintain enough prepaid funds to cover at least one week of average mail activity, based on the current average of 45 letters per week.

This goal should benefit customers by helping maintain confidence that their account validation process is moving forward. It should also benefit the authorized agents by helping us complete assigned certified mail tasks without unnecessary pauses.

## Lean Six Sigma Level

White Belt

I am documenting this as a White Belt project because this is my first Lean Six Sigma project and I am focusing on learning the basics of process improvement.

At the White Belt level, I want to show that I understand how to identify waste, delays, process flow issues, basic data collection opportunities, customer impact, and simple improvement ideas.

I observed the negative impact this situation is having on the department, so I am using this project to document the issue, track the process, and recommend improvements. My role is to organize the information clearly and propose the improvement to management.

For this project, I will use basic Lean Six Sigma tools such as process observation, waste identification, basic data collection, a tally or log, and a simple before-and-after comparison.

This project is scoped at the White Belt level, so I am not using advanced statistical analysis. I understand that more advanced analysis may be more appropriate for future Yellow Belt or Green Belt projects if the process needs deeper measurement, variation analysis, or larger-scale improvement.

My learning goal is to practice identifying a real process problem, defining the project scope, collecting simple evidence, and proposing a practical improvement.

## Method

I will use basic Lean Six Sigma tools to understand the current certified mail fund replenishment process, identify the main causes of delay, and propose a practical improvement.

First, I will create a SIPOC overview to define the Suppliers, Inputs, Process, Outputs, and Customers involved in the certified mail funding process. This will help me understand who is involved, what information is needed, what steps happen, and who is affected when funds are not available.

I will also prepare a current-state process map in SVG format to show the flow from preparing a letter to discovering insufficient funds, notifying the IT Manager, receiving approval from the Director of Operations, contacting the provider, and waiting for the funds to become available.

For data collection, I will use a Google Sheets spreadsheet to track letter activity and funding issues. The tracking log will include the letter tally, weekly mail count, type of letter, date sent, estimated funds used, insufficient fund incidents, and time delayed.

I will use the 5 Whys root cause analysis method to better understand why the issue happens. This analysis may include causes such as lack of balance visibility, no prepaid threshold, no early alert, or an unclear notification trigger.

I will identify process waste by estimating waiting time, rework, interruptions, delayed customer response, and unnecessary follow-up from the last three months when possible.

The main improvement tool I plan to use is a low-balance reminder connected to a prepaid threshold. This threshold will be supported by the weekly tally or log so the team can request replenishment before funds are depleted.

I will compare the process before and after the improvement. Before the improvement, funds usually run out bi-weekly and can create a minimum three-hour delay. After the improvement, my goal is for replenishment requests to be submitted at least one business day before funds run out, with no client file pauses caused by insufficient funds.

## Project Deliverables

The README will remain the central documentation page for this project. It will summarize the project focus, problem statement, goal, method, deliverables, success measures, and learning goals.

I will create a separate SIPOC file to define the Suppliers, Inputs, Process, Outputs, and Customers involved in the certified mail fund replenishment process.

The current-state process map will be included as `current-state-process-map.svg`. This map will show the current flow from preparing a certified letter to discovering insufficient funds, notifying the IT Manager, receiving approval, contacting the provider, and waiting for funds to become available.

I will create a separate root cause analysis file named `root-cause-analysis.md`, where I will document the 5 Whys analysis and the likely causes of the current delay.

To avoid exposing company data, I will not include real tracking records in this repository. Instead, I will include a sanitized tracking log template at `templates/mail-tracking-log-template.csv`. This template will show the fields I plan to use for tracking letter volume, letter type, estimated fund usage, insufficient fund incidents, and delay time.

## Success Measures

I may track metrics such as:

- Percentage of incomplete requests
- Average time to complete a request
- Number of clarification messages needed
- Number of rework loops
- User satisfaction or feedback

## Repository Status

This project is in the planning stage. My next step is to choose the specific process I want to improve and collect baseline data.

## Learning Goals

Through this project, I aim to:

- Practice Lean Six Sigma thinking at a White Belt level
- Learn how to define and scope a process improvement project
- Build confidence using basic improvement tools
- Document a project clearly for professional growth
- Create a foundation for future Yellow Belt or Green Belt learning
