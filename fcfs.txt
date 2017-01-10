
start_time=0
total=0

for i in xrange(n):
	a.append([])
	a[i].append(raw_input('enter process name: '))
	a[i].append(int(raw_input('enter arrival time: ')))
	a[i].append(int(raw_input('enter burst time: ')))
	total_w.append([])
	total_w[i].append(int(start_time-a[i][1]))
	

print 'Process \t Arrival time \t Burst time \t waiting time'

