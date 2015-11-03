# meetup wix

## Scale your teams without going insane
*Ittai Golde*

what am I login for in  an engineer?
* no ego
* language is a tool
* values development velocity
* code and system ownership
* productive
* XFN - cross functions
* know the whole system 0 from design to deployment
* everyone codes!

### development velocity (unrelated to agile!)

make thing faster
* proper IDE
* tooling
* flexible budget
* available resources - the manager job is to remove all the obstacle
* remove obsacles

make things slower
* Meetings
* Silo'ing
* compartmentalization
* 10bis / cibus

### Tooling
* project memory
  * wiki everything
  * Quip...
* communication
  * IRC
  * slack
  * hipchat
  * bot intergation!

### interview
* everyone interviews - every engineer need to give two hours of interviews
* if there's a doubt, there's no doubt (including false negative)
* everyone codes in interviews
* multiple interviews
* check for culture fit
* everyone is calibrated
* known pool of questions - no trick questions!


### workplan
* create a measurable workplan
  * "increase use engagement" - bad
  * "increase messages by sender by 25%" - good
  * "make the system faster" - bad
  * "decrease page load time by 50%" - good
* breakdown to engineer level
* allows tracking of progress

### how we work
* measure everything
  * concurrent connections
  * time spent (and where)
  * traffic bandwidth
  * requests
  * error
* measure
  * aggregate
  * transitive
* allow drill down
  * process / machine / cluster / DC / System
* measure developer velocity
  * SLA - time to fix bugs
  * Fix
  * number of deploys
  * impact
* automatic alarms by comparison
  * week over week
  * day over day
* automatic alarms by absolutes
  * CPU
  * bandwidth
  * storage
  * memory

### Continues integration
* single repo
* automatic build
* unit test
* integration test

### development
* small diffs
* mandatory
  * code review
  * unit tests
  * integration test - include E2E
* changes with measurable impact

### deployment
* incremental rollout via canaries
  * measure! (drill down is your firend)
* rollback / full deploy based on result
* allow time for metrics to settle
* Build A/B testing framework

### roles
* PM
  * flow
  * metrics
  * design
* developer
  * code
  * review
  * deploy
  * monitor
  * fix

### Testing (do we need QA?) - for web systems
* unit test
* integration test
* automatic test in build
* regression tests
* alerted on changes
* weekly bug review
* A/B, canary user testing

## Scaling to 70 million users
*Yoav Abrahami*

* plan for gradual rewrite
* split the system by SLA and release cycle
* use mysql as noSql server
* use managed hosting
* people are the key - give people the responsibility
  * how to hire the people they want to work with 3 questions
    * what have you done? why you did that?
    * solving question, example how do I build ecommerce? (design conversation)
    * write code

solution
* Continues delivery
* micro services - per team
  * independent deployment
  * independent OS process
  * independent database

### companies vs guilds
* companies focus on products
* guilds focus on technology


**keywords**
* circular list
* python stack overflow
* colabe edit
* computer science 101
* go
* irb
* monolite
* hops in micro services
