##############################
#My Docker Configuration File#
##############################

FROM akhi4u/vistrails:latest
MAINTAINER akhi4u <acamisetty@gmail.com>

#Add tb.vt to container
ADD tb.vt /opt/A2/tb.vt

#Add script to container
ADD run_workflow.py /opt/A2/run_workflow.py

#Run workflow
ENTRYPOINT ["python", "-u", "/opt/A2/run_workflow.py", \
  "/opt/A2/tb.vt", "parameterized"]
  
##############################
#My Docker Configuration File#
##############################