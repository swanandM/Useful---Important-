 FIO is a workload generator that can be used both for benchmark and stress/hardware verification.
 
 fio was created to allow benchmarking specific disk IO workloads. It can issue its IO requests using one of many synchronous and asynchronous IO APIs, and can also use various APIs which allow many IO requests to be issued with a single API call. You can also tune how large the files fio uses are, at what offsets in those files IO is to happen at, how much delay if any there is between issuing IO  requests, and what if any filesystem sync calls are issued between each IO request.
 
 
 One line installation on Ubuntu 14.04 LTE --- sudo apt-get install fio
 
 Make a new file named test.fio in a directory (e.g. swan)
 Copy the content of test.fio file in it.
 
 How to run the test --- fio test.fio
 
 Also see the sample output attached.
