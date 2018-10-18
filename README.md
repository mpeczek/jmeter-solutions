# parametrized-thread-group.jmx

jmeter -n -t parametrized-thread-group.jmx -l ./test-results.jtl -j ./test.log -JstartThreads=1 -JaddThreads=1 -JaddThreadsInterval=6 -JmaxThreads=3 -JmaxThreadsHold=11
