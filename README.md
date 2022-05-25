# .github
# Meyer Lab ReadMe
## Linux Machine Specs
DNS entry	IP address (DNS)	IP (1Gbps intranet)	IP (20gbps infiniband)	CPU	CPU Freq (GHz)	# of CPU	# of Threads	Total RAM (GB)	RAID (total size)	Benchmark score per thread
meyer.berkeley.edu	128.32.88.9	192.168.0.26	192.168.1.26	Xeon E5-2670	2.6	2	32	128		1466
meyer4.berkeley.edu	128.32.88.102	192.168.0.25	192.168.1.25	Xeon E5-2670	2.6	2	32	118	/what1 (39TB)	1466
meyer7.berkeley.edu	128.32.88.184	192.168.0.22	192.168.1.22	Xeon E5-2620 v4	2.1	1	16	256		1582
meyer9.berkeley.edu	128.32.88.186	192.168.0.23	192.168.1.23	Xeon E5-2670	2.6	2	32	56	/what4 (26TB)	1466
meyer10.berkeley.edu	128.32.88.187	192.168.0.20	192.168.1.20	Ryzen 7 1800X	3.2	1	16	64	/what3 (102TB)	2178
meyer12.berkeley.edu	128.32.88.189	192.168.0.24	192.168.1.24	EPYC 7401P	2	1	48	128		1830
meyer32.mcb.berkeley.edu	128.32.88.130	192.168.0.21	192.168.1.21	Xeon E5-2670	2.6	2	32	64	/what2 (95TB)	1466
										
(Mac Pro)		192.168.0.31		Xeon W-3245	3.2	1	32	192		2531
(SP8 PC)			192.168.1.12							

Notes:
_- Leave at least 2 threads for the operating system and other processes to avoid slow down of the whole system when running your jobs.
- Benchmark scores are PassMark.  
- Benchmark score is shown here as a clue.  Actual performance will vary with what you do.
- Mac Pro is connected to airworm4 for the internet access.  
- sudoers are Miki and Matthew on these machines
- All Linux machines run "stable" release of Debian
- For R, a repository with newer version of packages on campus is used.  Watch out for bugs as they are not "bug-free"_
- Source: Google sheet [here]([url](https://docs.google.com/spreadsheets/d/1fpQsdqZNJdOhjlHE9Ld4hPGy5QZ_tywZROQtIjrfATE/edit#gid=0)).

## 
