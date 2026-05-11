## project overview

this project is a beginner soc home lab.

i used splunk and a linux vm to collect logs and review security events.

the main goal was to practice basic soc work.

i looked at ssh login activity failed login attempts sudo activity and user activity.

this project helped me understand how raw linux logs can become useful security information.

## tools used

1. splunk enterprise
2. ubuntu linux vm
3. ssh
4. linux auth logs
5. spl search queries

## skills practiced

1. log monitoring
2. failed ssh login detection
3. linux authentication log analysis
4. splunk dashboard creation
5. alert setup
6. basic soc investigation
7. documentation

## lab setup

i installed splunk on a linux vm.

i added linux auth logs into splunk.

the main log source used in this project was

```text
/var/log/auth.log
