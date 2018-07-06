---
status: in progress
---

# OSG User School Materials

## Monday

### Monday Morning: Introduction to HTC

- Lecture: Introduction to HTC ([PDF](/materials/day1/files/osgus18-day1-part1-intro-to-htc.pdf))
- [Exercise 1.1: Log in to the local submit machine and look around](/materials/day1/part1-ex1-login.md)
- [Exercise 1.2: Experiment with basic HTCondor commands](/materials/day1/part1-ex2-commands.md)
- [Exercise 1.3: Run jobs!](/materials/day1/part1-ex3-jobs.md)
- [Exercise 1.4: Read and interpret log files](/materials/day1/part1-ex4-logs.md)
- [Exercise 1.5: Determining Resource Needs](/materials/day1/part1-ex5-request.md)
- [Exercise 1.6: Remove jobs from the queue](/materials/day1/part1-ex6-remove.md)
- [Bonus Exercise 1.7: Compile and run some C code](/materials/day1/part1-ex7-compile.md)

### Monday Morning: More HTCondor

- Lecture: More HTCondor ([PDF](/materials/day1/files/osgus18-day1-part2-more-htcondor.pdf))
- [Exercise 2.1: Explore `condor_q`](/materials/day1/part2-ex1-queue.md)
- [Exercise 2.2: Explore `condor_status`](/materials/day1/part2-ex2-status.md)
- [Exercise 2.3: Work with input and output files](/materials/day1/part2-ex3-files.md)
- [Exercise 2.4: Use `queue <em>N</em>`, `$(Cluster)`, and `$(Process)`](/materials/day1/part2-ex4-queue-n.md)
- [Exercise 2.5: Use `queue matching`, and a custom variable](/materials/day1/part2-ex5-queue-matching.md)
- [Exercise 2.6: Use `queue from`, and custom variables](/materials/day1/part2-ex6-queue-from.md)

### Monday Afternoon: Retrying jobs and Workflows with DAGMan

- Lecture: Intermediate HTCondor: Workflows ([PDF](/materials/day1/files/osgus18-day1-part3-dagman1.pdf))
- [Exercise 3.1: A job that needs retries](/materials/day1/part3-ex1-job-retry.md)
- [Exercise 3.2: A brief detour through the Mandelbrot set](/materials/day1/part3-ex2-mandelbrot.md)
- [Exercise 3.3: Coordinating set of jobs: A simple DAG](/materials/day1/part3-ex3-simple-dag.md)
- [Exercise 3.4: A more complex DAG](/materials/day1/part3-ex4-complex-dag.md)

### Monday Afternoon: Intermediate Workflows with DAGMan

- Lecture: HTCondor: More on Workflows ([PDF](/materials/day1/files/osgus18-day1-part4-dagman2.pdf))
- [Exercise 4.1: Handling jobs that fail with DAGMan](/materials/day1/part4-ex1-failed-dag.md)
- [Exercise 4.2: Simpler DAGs with variable substitutions](/materials/day1/part4-ex2-dag-vars.md)
- [Exercise 4.3: Using DAG SPLICE for node organization](/materials/day1/part4-ex3-dag-splice.md)
- [Bonus Exercise 4.4: HTCondor challenges](/materials/day1/part4-ex4-challenges.md) (If and only if you have time)

## Tuesday

### Tuesday Morning: Introduction to Distributed HTC and Overlay Systems

- Lecture: Introduction to DHTC ([PDF](/materials/day2/files/osgus18-day2-part1-intro-to-dhtc.pdf))
- [Exercise 1.1: Refresher - Submitting multiple jobs](/materials/day2/part1-ex1-submit-refresher.md)
- [Exercise 1.2: Log in to the OSG submit machine](/materials/day2/part1-ex2-login-scp.md)
- [Exercise 1.3: Running jobs in the OSG](/materials/day2/part1-ex3-submit-osg.md)

### Tuesday Morning: Comparing Local and Remote HTC

- Lecture: What is different about overlay systems?
  ([PDF](/materials/day2/files/osgus18-day2-part2-overlay-differences.pdf))
- [Exercise 2.1: Hardware differences in the OSG](/materials/day2/part2-ex1-hardware-diffs.md)
- [Exercise 2.2: Software differences in the OSG](/materials/day2/part2-ex2-software-diffs.md)

### Tuesday Afternoon: Security in OSG

- Lecture: Security in OSG ([PDF](/materials/day2/files/osgus18-day2-part3-security.pdf))

### Tuesday Afternoon: Troubleshooting jobs

- Lecture: Troubleshooting jobs ([PDF](/materials/day2/files/osgus18-day2-part4-troubleshooting.pdf))
- [Exercise 3.1: Troubleshooting a DAG](/materials/day2/part3-ex1-troubleshooting.md)

### Tuesday Afternoon: Connecting to OSG

- Lecture: Ways to Connect to OSG ([PDF](/materials/day2/files/osgus18-day2-part5-ways-to-connect.pdf))

## Wednesday

### Wednesday Morning: Software Portability

- Lecture: Software Portability for DHTC ([PDF](/materials/day3/files/osgus18-day3-part1-software-portability.pdf))
- [Exercise 1.1: Compiling programs for portability](/materials/day3/part1-ex1-compiling.md)
- [Exercise 1.2: Using a pre-compiled binary](/materials/day3/part1-ex2-precompiled.md)
- [Exercise 1.3: Using a wrapper script](/materials/day3/part1-ex3-wrapper.md)
- [Exercise 1.4: Pre-packaging code](/materials/day3/part1-ex4-prepackaged.md)
- [Bonus Exercise 1.5: Passing Arguments Through the Wrapper Script](/materials/day3/part1-ex5-arguments.md)

### Wednesday Morning: Software Limitations

- Lecture: Considerations for licensing and programming packages
  ([PDF](/materials/day3/files/osgus18-day3-part2-software-license-interpret.pdf))
- [Exercise 1.6: Compile and run Matlab code](/materials/day3/part2-ex1-matlab.md)
- [Exercise 1.7: Pre-packaging Python](/materials/day3/part2-ex2-python-built.md)
- [Exercise 1.8: In-job installation of Python](/materials/day3/part2-ex3-python-install.md)
- [Bonus Exercise 1.9: Using containers](/materials/day3/part2-ex4-containers.md)

### Wednesday Afternoon: On Your Own

- [Ideas for activities](UserSchool15WedActivities)

## Thursday

### Thursday Morning: OSG Connect

- Lecture: OSG Connect ([PDF](/materials/day4/files/osgus18-day4-part1-osg-connect.pdf))
- [Exercise 1.1: Get acquainted with OSG Connect](/materials/day4/part1-ex1-connect-intro.md)
- [Exercise 1.2: Do the OSG Connect "quickstart"](/materials/day4/part1-ex2-connect-quickstart.md)
- [Exercise 1.3: Try an OSG Connect software module](/materials/day4/part1-ex3-connect-modules.md)
- [Exercise 1.4: Try Singularity Container Job on the OSG (Optional)](/materials/day4/part1-ex4-singularity.md)

### Thursday Morning: Data Handling

- Lecture: Overall data considerations ([PDF](/materials/day4/files/osgus18-day4-part2-overall-data.pdf))
- [Exercise 2.1: Understanding your data requirements](/materials/day4/part2-ex1-data-needs.md)
- [Exercise 2.2: HTCondor file transfer and compression](/materials/day4/part2-ex2-file-transfer.md)
- [Exercise 2.3: Splitting large input data](/materials/day4/part2-ex3-blast-split.md)

### Thursday Afternoon: Data Handling (continued)

- Lecture: Solutions for large input data ([PDF](/materials/day4/files/osgus18-day4-part3-large-input.pdf))
- [Exercise 3.1: Using a web proxy for large, shared input](/materials/day4/part3-ex1-blast-proxy.md)
- [Exercise 3.2: Using StashCache for large, shared input](/materials/day4/part3-ex2-stashcache-shared.md)
- [Exercise 3.3: Using StashCache for large, unique input](/materials/day4/part3-ex3-stashcache-unique.md)

### Thursday Afternoon: Data Handling (continued)

- Lecture: Large output and shared file systems; Data summary
  ([PDF](/materials/day4/files/osgus18-day4-part4-output-shared-fs.pdf))
- [Exercise 4.1: Using a local shared filesystem for large input files](/materials/day4/part4-ex1-input.md)
- [Exercise 4.2: Using a local shared filesystem for large output files](/materials/day4/part4-ex2-output.md)

The submit host `user-training.osgconnect.net` will be active for about two weeks.  For long term use, please
[sign up for OSG Connect](/materials/connect.md).
If you have any questions about the signup process, please email
<user-support@opensciencegrid.org>

## Friday

### Friday Morning: From Science to Production Workflows

- Lecture: From Science to Real Workflow ([PDF](/materials/day5/files/osgus18-day5-part1-real-workflows.pdf))
- [Exercise 1.1: Learn about Joe’s Desired Computing Work](/materials/day5/part1-ex1-science-intro.md)
- [Exercise 1.2: Plan Overall Workflow](/materials/day5/part1-ex2-plan-workflow.md)

### Friday Morning: From Science to Production Workflows

- Lecture: From Workflow to Automated Production
  ([PDF](/materials/day5/files/osgus18-day5-part2-production-workflows.pdf))
- [Exercise 1.3: Execute Joe’s Workflow](/materials/day5/part2-ex1-execute-workflow.md)
- [Bonus Exercise 1.4: Further Optimization and Scaling](/materials/day5/part2-ex2-workflow-tuning.md)

### Friday Afternoon: HTC Showcase

- Talk: [Dane Morgan](http://directory.engr.wisc.edu/mse/faculty/morgan_dane), Engineering:
  *HTC for Engineering Better Materials* ([PDF](/materials/day5/files/osgus18-day5-part3-showcase1-dmorgan.pdf))
- Talk: [Megan Frayer](https://payseur.genetics.wisc.edu/member.html), Genetics:
  *Using HTC in Genomic Ancestry Analysis* ([PDF](/materials/day5/files/osgus18-day5-part3-showcase2-mfrayer.pdf))
- Talk: [William Cocke](https://www.math.wisc.edu/~boston/), Mathematics:
  *Building a Character Table Database: A Use of Condor in Pure Math*
  ([PDF](/materials/day5/files/osgus18-day5-part3-showcase3-wcocke.pdf))
- Talk: [Edgar Spalding](http://www.botany.wisc.edu/spalding.htm), Botany:
  *HTC As a Tool to Study How Plant Genomes Function*
  ([PDF](/materials/day5/files/osgus18-day5-part3-showcase4-espalding.pdf))

### Friday Afternoon: Foundations of HTC

- Lecture: The Principles of HTC ([PDF](/materials/day5/files/osgus18-day5-part4-htc-principles.pdf))

### Friday Afternoon: Wrap Up

- Lecture: Where to Go and What to Do Next ([PDF](/materials/day5/files/osgus18-day5-part5-whats-next.pdf))
