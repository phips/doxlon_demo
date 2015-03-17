# Go agentless! - Ansible talk @DOXLON December 3rd 2014

Configuration Management tools are an enabler to greater things - they should
smooth the path to delivering for your customers. Tonight we'll show you why
Ansible is the simplest way to automate IT.

# Spinning up EC2 instances

ansible-playbook plays/launch.yml -e '{"count":"5","tags":{"env":"prod","type":"web"}}'
